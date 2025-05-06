# 🦖 Shiny Dino Game

A fun and interactive side-scrolling dino game built with **R Shiny**, using JavaScript, custom images, and sound effects. Press the **spacebar** to make the dinosaur jump over the cactus. Score points and try not to crash!

## 🚀 Features

- Built with `shiny` and `shinyjs`
- Spacebar controls to jump
- Real-time collision detection
- Score counter with reset button
- Custom image sprites for the dinosaur and cactus
- Sound effect when jumping

## 📦 Requirements

Make sure these R packages are installed:

```r
install.packages("shiny")
install.packages("shinyjs")
🛠 How to Run
Save the game code to a file named app.R

Place these files in the same directory:

dino.png (dino sprite)

cactus.png (cactus sprite)

jump.mp3 (sound effect)

Open R or RStudio and run:

r
Copy
Edit
shiny::runApp("app.R")
🎮 Controls
Spacebar: Jump

Reset button: Restart the game

📁 Folder Structure
Copy
Edit
your-project-folder/
├── app.R
├── dino.png
├── cactus.png
└── jump.mp3
📸 Preview
(Optional: Insert screenshot or gif of the game in action)

🧠 Credits
Created by Rivcat
Powered by R Shiny + JavaScript
