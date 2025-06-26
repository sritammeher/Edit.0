# <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Simple Photo Editor</title>
<link rel="stylesheet" href="style.css" />
</head>
<body>
<h1>Photo Editor</h1>

<input type="file" id="upload" accept="image/*" />

<canvas id="canvas"></canvas>

<div class="controls">
  <label>Brightness
    <input id="brightness" type="range" min="0" max="200" value="100" />
  </label>
  <label>Contrast
    <input id="contrast" type="range" min="0" max="200" value="100" />
  </label>
  <button id="download">Download</button>
</div>

<script src="script.js"></script>
</body>
</html>
You can edit your photo 
