<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale-1.0">
  <title>color Blindness Test/title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>color Blindness Test</h1>
    <div id="test">
      <p>what number or shape do you see?</p>
      <div class="color-blind-test" data-answer="3">
        <img src="images/ishihara_1.png" alt="color blind test image">
      </div>
      <div class="color-blind-test" data-answer="8">
        <img src="images/ishihara_2.png" alt="color blind test image">
      </div>
      <div class="color-blind-test" data-answer="5">
        <img src="images/ishihara_3.png" alt="Color blind test images">
      </div>
      <button id="submitBtn">Submit</button>
      <p id="result"></p>
    </div>
  </div>
   <script src="script.js"></script>
 </body>
 </html>
