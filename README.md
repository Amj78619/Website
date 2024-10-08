<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Counter App</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="counter-app">
    <h1>Simple Counter</h1>
    <div id="counter" class="counter-display">0</div>
    <div class="controls">
      <button onclick="increment()">Increment</button>
      <button onclick="decrement()">Decrement</button>
      <button onclick="reset()">Reset</button>
    </div>
  </div>
  <script src="app.js"></script>
</body>
</html>
