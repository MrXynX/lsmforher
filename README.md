<html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Why Would I Find Someone Better, If You Are the Best One?</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: yellow;
      color: black;
      overflow: hidden;
    }

    .page {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      background-color: yellow;
    }

    .content {
      background: white;
      padding: 20px 30px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
      max-width: 600px;
      width: 90%;
      font-size: 1.2rem;
      line-height: 1.8;
      color: black;
      white-space: normal;
      word-wrap: break-word;
      display: inline-block;
      text-align: left;
    }

    .highlight {
      color: cyan;
      font-weight: bold;
    }

    .highlight-red {
      color: red;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <!-- Page Content -->
  <div class="page" id="first-page">
    <div class="content">
      <h1>Why Would I Find Someone Better, If You Are the Best One?</h1>
      <p>Minsan, naiisip ko, <br><br>
      Bakit ko pa hahanapin ang mas magaling, <br>
      Eh ikaw na nga ang pinaka-perfect na tao para sa’kin? <br><br>
      Alam mo ba, every time I’m with you, I just feel like everything falls into place. <br>
      Hindi ko na kailangang maghanap pa ng iba. <span class="highlight">Why would I?</span> <br><br>
      Kasi ikaw yung magaan kasama, ikaw yung nagpapatawa sa’kin kahit ang bigat ng araw ko. <br>
      You get me like no one else does. Hindi ko na kailangan magpaliwanag, <br>
      <span class="highlight">kasi ikaw lang, sapat na.</span> <br><br>
      Siguro, maraming ibang tao na baka magustuhan ko, <br>
      pero sa lahat ng yun, ikaw lang yung natutunan kong mahalin ng buo. <br><br>
      Hindi ko na kailangang maghanap pa ng "<span class="highlight">better</span>", kasi I’ve found the <span class="highlight">best</span> already. <br>
      And that’s you. Palagi’t palagi, <span class="highlight">ikaw lang.</span> <br><br>
      Kaya't here's the truth: I’m never letting go, because why would I find someone <span class="highlight">better</span>, <br>
      when you're already the <span class="highlight">best</span>? <br><br>
      <span class="highlight-red">Mahal na mahal kita.</span> <br></p>
    </div>
  </div>

  <!-- Script for Music -->
  <audio id="background-music" loop>
    <source src="https://audio.jukehost.co.uk/IEEeBmgcBSRv8iWqg8QaB2AsOzII4HUK" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  <script>
    // Play music on user interaction
    document.body.addEventListener('click', function () {
      const music = document.getElementById('background-music');
      music.play();
    }, { once: true });
  </script>
</body>
</html>
