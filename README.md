# Welcome to Florian Liao's GitHub page!

<!DOCTYPE html>
<html>
<head>
  <script>
    var gifs = [
      "orange-cat-sleep.gif",
      "orange-cat.gif"
    ];
    var currentGifIndex = 0;
    var canClick = true;

    function switchGif() {
      if (canClick) {
        currentGifIndex = (currentGifIndex + 1) % gifs.length;
        var currentGif = gifs[currentGifIndex];
        if (currentGif === "orange-cat.gif") {
          canClick = false;
        } else {
          canClick = true;
        }
        document.getElementById('gifImage').src = currentGif;
      }
    }
  </script>
</head>
<body>
  <img id="gifImage" src="orange-cat-sleep.gif" width="100" height="100" alt="Orange Cat GIF" onclick="switchGif();">
</body>
</html>

***This orange cat is the mythological animal that guards my github page. It sometimes naps, so you can refresh the page to see if you can wake it up, or you can just click on it to wake it up.***





**huahuadeliaoliao/huahuadeliaoliao** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
