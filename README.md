# unit-4-game
<!DOCTYPE html>
<html>
<head>
  <title>simple crystal game</title>
</head>
<body>

<script type="text/javascript">
<img src="http://cdn.playbuzz.com/cdn/35910209-2844-45c0-b099-f4d82878d54f/00261fda-4062-4096-81fd-8cf96b9034e8.jpg" alt="crystals">

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

<script type="text/javascript">

 <style type="text/css">

    .crystal-image {
      width: 300px;
      height: 300px;
    }
  </style>

   <div id="crystals">

    <img class="crystal-image" src="http://cdn.playbuzz.com/cdn/35910209-2844-45c0-b099-f4d82878d54f/00261fda-4062-4096-81fd-8cf96b9034e8.jpg" alt="crystals">

  </div>
  <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

  <script type="text/javascript">

    var counter = 0;
  $("#crystals").on("click", ".crystal-image", function() {
       counter += 1;
 alert("You clicked this crystal " + counter + " times!");

counter += 10;
alert("Your new score is: " + counter);

 var targetNumber = 50;
  $("#number-to-guess").text(targetNumber);
   var counter = 0;
  $("#crystals").on("click", ".crystal-image", function() {

    counter += 10;

    alert("Your new score is: " + counter);

  });



