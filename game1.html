<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zero-G Chase Game</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background-color: #111;
      color: white;
      font-family: Arial, sans-serif;
    }
    #gameArea {
      position: relative;
      width: 100vw;
      height: 100vh;
      background: radial-gradient(circle, #111, #000);
      overflow: hidden;
    }
    .astronaut, .object {
      position: absolute;
      width: 50px;
      height: 50px;
      border-radius: 50%;
    }
    .astronaut {
      background-color: #00f;
    }
    .object {
      background-color: #ff0;
    }
    #scoreboard {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 20px;
    }
  </style>
</head>
<body>
  <div id="gameArea">
    <div id="scoreboard">Score: 0</div>
    <div id="astronaut" class="astronaut"></div>
    <div id="object" class="object"></div>
  </div>

  <script>
    const astronaut = document.getElementById('astronaut');
    const object = document.getElementById('object');
    const scoreboard = document.getElementById('scoreboard');

    let score = 0;
    let astronautPos = { x: 100, y: 100 }; // Initial position
    let astronautVelocity = { x: 0, y: 0 }; // Initial velocity
    let objectPos = { x: Math.random() * window.innerWidth, y: Math.random() * window.innerHeight };
    const speed = 0.5; // Control sensitivity

    // Initial positions
    function setPosition(element, pos) {
      element.style.left = pos.x + 'px';
      element.style.top = pos.y + 'px';
    }
    setPosition(astronaut, astronautPos);
    setPosition(object, objectPos);

    // Update astronaut's velocity based on key presses
    window.addEventListener('keydown', (event) => {
      switch (event.key) {
        case 'ArrowUp':
          astronautVelocity.y -= speed;
          break;
        case 'ArrowDown':
          astronautVelocity.y += speed;
          break;
        case 'ArrowLeft':
          astronautVelocity.x -= speed;
          break;
        case 'ArrowRight':
          astronautVelocity.x += speed;
          break;
      }
    });

    // Game loop to move the astronaut and check for collisions
    function gameLoop() {
      // Update position based on velocity
      astronautPos.x += astronautVelocity.x;
      astronautPos.y += astronautVelocity.y;

      // Check for wall collisions (simulate zero-G bounce)
      if (astronautPos.x < 0 || astronautPos.x > window.innerWidth - 50) {
        astronautVelocity.x = -astronautVelocity.x;
      }
      if (astronautPos.y < 0 || astronautPos.y > window.innerHeight - 50) {
        astronautVelocity.y = -astronautVelocity.y;
      }

      // Check if astronaut collects the object
      if (Math.abs(astronautPos.x - objectPos.x) < 50 && Math.abs(astronautPos.y - objectPos.y) < 50) {
        score++;
        scoreboard.innerText = 'Score: ' + score;

        // Move object to a new random position
        objectPos = {
          x: Math.random() * (window.innerWidth - 50),
          y: Math.random() * (window.innerHeight - 50),
        };
        setPosition(object, objectPos);
      }

      // Apply velocity to astronaut's position
      setPosition(astronaut, astronautPos);

      requestAnimationFrame(gameLoop); // Continue the loop
    }

    // Start the game loop
    gameLoop();
  </script>
</body>
</html>
