<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Resume</title>
    <style>
      /* Global Styles */
      body {
        font-family: Arial, sans-serif;
        background-color: black;
        color: white;
        margin: 0;
        padding: 0;
        text-align: center;
      }

      h1 {
        color: yellow;
        margin-top: 20px;
      }

      p {
        color: lightgray;
      }

      /* Button Styles */
      .btn {
        display: inline-block;
        margin: 10px;
        padding: 10px 20px;
        font-size: 18px;
        font-weight: bold;
        text-transform: uppercase;
        color: white;
        border: 2px solid transparent;
        border-radius: 5px;
        transition: 0.3s;
        cursor: pointer;
      }

      /* Button Colors */
      .btn-blue {
        background-color: blue;
        border-color: blue;
      }

      .btn-red {
        background-color: red;
        border-color: red;
      }

      .btn-yellow {
        background-color: yellow;
        color: black;
        border-color: yellow;
      }

      /* Button Animations */
      .btn:hover {
        transform: scale(1.1);
        opacity: 0.8;
      }

      .btn:active {
        transform: scale(1.05);
      }

      /* Section Styles */
      .section {
        margin: 30px auto;
        max-width: 800px;
        border: 1px solid #333;
        padding: 20px;
        background: #222;
        border-radius: 10px;
        animation: fadeIn 1s ease-in-out;
      }

      /* Fade-in Animation */
      @keyframes fadeIn {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
    </style>
    <script>
      // JavaScript functions for button actions
      function showMore() {
        alert("Man Ali Hastam va Karam Config Game mode Haye Minecraft Va Amniateshan Hast Ke Ta Hadi Ba Java Va HTML ham Kar Mikonam");
      }

      function seeSkills() {
        alert("Config Minecraft - Java Va HTML 40%");
      }

      function viewPortfolio() {
        window.open("https://BeZudi.com", "_blank");
      }

      function contactMe() {
        alert("Gmail = fonnight7@gmail.com");
      }
    </script>
  </head>
  <body>
    <h1>Resume</h1>

    <!-- About Me Section -->
    <div class="section">
      <h2>(Darbareh Man)</h2>
      <p>
        Salam Man Ali Hastam !
      </p>
      <button class="btn btn-blue" onclick="showMore()">Bishtar Bekhoon</button>
    </div>

    <!-- Skills Section -->
    <div class="section">
      <h2>(Maharat-ha)</h2>
      <p>HTML Sade - Config Minecraft - Java 20%</p>
      <button class="btn btn-red" onclick="">(Maharat-ha)
    </div>

    <!-- Portfolio Section -->
    <div class="section">
      <h2>(Karha)</h2>
      <p>Proge Hamo Az inja Bebin</p>
      <button class="btn btn-yellow" onclick="viewPortfolio()">Didan Projheha</button>
    </div>

    <!-- Contact Section -->
    <div class="section">
      <h2>(Ertabat)</h2>
      <p>
        Gmail = fonnight7@gmail.com ya discord = usmamad
      </p>
      <button class="btn btn-blue" onclick="contactMe()">(Tamase ba Man)</button>
    </div>
  </body>
</html>
