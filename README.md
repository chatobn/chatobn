## Hi there 👋

<!--
**chatobn/chatobn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
// NOTE - Requires jQuery
setInterval(function() {
  var lastSeen = $('.pane-header .chat-body .emojitext').last().text();
  console.log(Math.floor(Date.now() / 1000) + ", " + lastSeen);
}, 1000);
