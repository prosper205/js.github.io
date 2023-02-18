<html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name ="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="style.css">
<title>DRAW WITH ME:) </title>
<form>
<input type="text" class="screen" placeholder="PROSPER">
</form>

</head>
<body>
<section class="container">
<div id="toolbar">
<h1>DRAW....</h1>
<label for="stroke">Stroke</label>
<input id="stroke" name='stroke' type="color">
<label id="lineWidth">Line Width</label>
<input for="lineWidth" name='lineWidth' type="number" value="5">
<button id="clear">Clear</button>
</div>
<div class="drawing-board">
<canvas id="drawing-board"></canvas>
</div>
</section>
<script src="app.js"></script>
</body>
</html>
