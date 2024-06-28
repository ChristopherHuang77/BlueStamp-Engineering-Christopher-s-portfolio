# Project Name Here
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Christopher Huang | Morrison Acdemy  | Computer Science | Incoming Sophomore

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/rinA1b9ITs4?si=fovmNqZjJNmS4dyF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I modified it to create a Crossy Road-like game. In my game, you are the red character who moves by tilting the screen. You must avoid white cells, reach the green cells, and score points. Each time you hit green, your score goes up, but hitting white decreases your lives. The game ends when you run out of lives. To create this, I leveraged the built-in accelerometer. During BlueStamp, I learned Arduino coding, video creation, and presentation skills. Some of my favorite experiences were seeing my code work and playing games during breaks. Now, I feel confident in working on similar projects.



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/7D08KzsVk9U?si=BM9KM_xidD9Fierq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

During this milestone I have managed to to display Conway's Game of Life on the LED display. At first, it was hard to get started on my Conway's Game of Life project for the LED display. My instructor helped by providing a structured framework that I just needed to fill in with the rule set. However, my code initially didn't work as intended. To address this, I tried a different approach suggested by my instructor and wrote the code differently. Conway's Game of Life is a zero-player game where each cell is either alive (light on) or dead (light off). The state of each cell in the next generation depends on its eight neighboring cells: a dead cell becomes alive with exactly three live neighbors, a live cell survives with two or three live neighbors, and a live cell dies of underpopulation with fewer than two or overpopulation with more than three live neighbors. I also implemented a colored variant that I thought was cool. To finnish this project I want to come up with a different game and project it onto the display.



# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/z4JYAGbOjJ8?si=VfJcBRMNVPYO6hDQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My project is made up of a LED display and a Adafruit Matrix Portal M4. During this first mile stone I have learned how to display different text on the LED display, how to change the position and color of the text, and how to move around shapes and pixels. Orginaly, when I first put in the code there was an error that I could not fix,  I asked my instructor and he helped me find a missing lybrary,  Adafruit GFX lybrary,  that was needed in the Adafuit Protomatter.  Another problem I ran into was my name was to long to fit on onw line on the display. I tried shrinking the text size, but it was the smallest size already, so instead I removed some spacing inbetween the letters. I also ran into a problem where the Adafruit Matrix Portal would not connect to the Aduino IDE, I fix it by double tapping the reset button and it connected. My plan to compleate the project is to look over the CircuitPython code for Conways Game of Life,  and rewrite it in aduino. 



# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials

| Matrix Portal Starter Kit | Constructing LED Display | $69.95 | <a href="https://www.adafruit.com/product/4812"> Link </a> |
| Bend Wire Stand | Stand for Finnal Project | $4.95 | <a href="https://www.adafruit.com/product/1679"> Link </a> |
| Screwdriver Set | Screw in Screws to Construct LED Display  | $7.95 | <a href="https://www.adafruit.com/product/424"> Link </a> |
| USB C to USB C | Connects Matrix Portal to Computer | $9.95 | <a href="https://www.adafruit.com/product/4199"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
