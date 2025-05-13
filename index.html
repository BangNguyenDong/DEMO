<!DOCTYPE html>
<html>
<head>
  <title>Game Khủng Long Mất Mạng</title>
  <link rel="stylesheet" href="https://pyscript.net/latest/pyscript.css" />
  <script defer src="https://pyscript.net/latest/pyscript.js"></script>
  <style>
    canvas {
      background: #eee;
      display: block;
      margin: auto;
      border: 2px solid black;
    }
    h2 {
      text-align: center;
    }
  </style>
</head>
<body>
  <h2>🐱‍🏍 Game Khủng Long Mất Mạng - Nhấn vào màn hình để nhảy</h2>
  <canvas id="game" width="800" height="200"></canvas>

  <py-script>
from js import document, requestAnimationFrame
import asyncio

canvas = document.getElementById("game")
ctx = canvas.getContext("2d")

# Khởi tạo vị trí và biến
dino_y = 150
velocity = 0
gravity = 0.6
is_jumping = False

cactus_x = 800
speed = 5
game_over = False

# Vẽ khủng long
def draw_dino():
    ctx.fillStyle = "green"
    ctx.fillRect(50, dino_y, 30, 30)

# Vẽ cactus
def draw_cactus():
    ctx.fillStyle = "red"
    ctx.fillRect(cactus_x, 150, 20, 40)

# Va chạm
def check_collision():
    global game_over
    if cactus_x < 80 and cactus_x + 20 > 50 and dino_y + 30 > 150:
        game_over = True

# Cập nhật trò chơi
def update():
    global dino_y, velocity, cactus_x, game_over

    ctx.clearRect(0, 0, 800, 200)

    # Cập nhật nhảy
    if dino_y < 150:
        velocity += gravity
        dino_y += velocity
    else:
        dino_y = 150
        velocity = 0
        is_jumping = False

    # Di chuyển chướng ngại vật
    cactus_x -= speed
    if cactus_x < -20:
        cactus_x = 800

    # Vẽ lại
    draw_dino()
    draw_cactus()
    check_collision()

    # Hiển thị Game Over nếu va chạm
    if game_over:
        ctx.font = "30px Arial"
        ctx.fillStyle = "black"
        ctx.fillText("Game Over!", 300, 100)
    else:
        requestAnimationFrame(update)

# Sự kiện nhấn chuột để nhảy
def jump(event):
    global is_jumping, velocity
    if not is_jumping and dino_y >= 150:
        velocity = -12
        is_jumping = True

# Gắn sự kiện
canvas.addEventListener("click", jump)

# Khởi chạy
update()
  </py-script>
</body>
</html>
