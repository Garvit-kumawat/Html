
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Car Racing Game</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      overflow: hidden;
    }
    #startScreen, #gameOverScreen, #garageScreen {
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: #000000c0;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      z-index: 2;
    }
    #gameCanvas {
      background: #222;
      display: block;
      width: 100vw;
      height: 100vh;
    }
    #controls {
      position: absolute;
      bottom: 10px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 10px;
      z-index: 3;
    }
    .btn {
      padding: 10px 20px;
      font-size: 18px;
      cursor: pointer;
    }
    #ui {
      position: absolute;
      top: 10px;
      left: 10px;
      color: white;
      z-index: 3;
    }
    #miniMap {
      position: absolute;
      top: 10px;
      right: 10px;
      width: 150px;
      height: 150px;
      background: #333;
      border: 2px solid white;
      z-index: 3;
    }
  </style>
</head>
<body><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Car Racing Game</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      overflow: hidden;
    }
    #startScreen, #gameOverScreen, #garageScreen {
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: #000000c0;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      z-index: 2;
    }
    #gameCanvas {
      background: #222;
      display: block;
      width: 100vw;
      height: 100vh;
    }
    #controls {
      position: absolute;
      bottom: 10px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 10px;
      z-index: 3;
    }
    .btn {
      padding: 10px 20px;
      font-size: 18px;
      cursor: pointer;
    }
    #ui {
      position: absolute;
      top: 10px;
      left: 10px;
      color: white;
      z-index: 3;
    }
    #miniMap {
      position: absolute;
      top: 10px;
      right: 10px;
      width: 150px;
      height: 150px;
      background: #333;
      border: 2px solid white;
      z-index: 3;
    }
  </style>
</head>
<body>
