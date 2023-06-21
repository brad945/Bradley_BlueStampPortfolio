# Lie Detector 
<!--Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
-->
Have you ever wanted to test out your friends' honesty? Now you can with this easy-to-build lie detector.
For my project I built a lie detector that lights up whenever it detects that someone may be lying. The only catch are this project's limitations in the factors in which it takes into account when determining if the user is lying or not, which includes condensation of the skin, and heartrate. Some of my biggest challenges and triumphs were soldering all of the components onto my final board, and coding an algorithm that determines the lighting up of the LED lights for when a "lie" is detected. 


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Bradley T | Carlmont | Mechanical Engineering | Incoming Junior

<!--
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)    
-->

  
<!--# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
-->
# Second Milestone
<!--For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone
-->
For my second milestone, I successfully transferred all of my components from my "draft" breadboard to a more professional soldering board. This process was very tedious and was actually much more difficult than I thought. I learned many things through doing this, such as learning new and better ways to solder and de-solder, and just getting better at both in general. 

My first main difficulty was dealing with a "faulty" solder board. It took a few tries and hours until I decided to use a new soldering board, since the one I was using would not stick with the solder at all. For example, the solder would be touching a wire and the board, and once you took the soldering iron away, the solder would sometimes just fall off. I was able to de-solder some things, but other components such as the actual Arduino Nano chip itself had to be replaced. 

My second main difficulty was an error in my knowledge of breadboards. I based my breadboard model on a picture that was slightly vague in the instructions, and just blindly copied from the picture. It turns out that the breadboard was flipped upside down when I copied it, so I plugged my ground cable into the positive ground when it should have been in the negative. This caused even more problems in and of itself, as it fried my LEDs, and at the time I did not know why they were frying (I also learned that positive and negative current flow do not go well together!).

What I still need to do before my final milestone is completed is to finish up all my code for the project. Right now, I have a constant number that acts as a range for detecting when someone is "lying", but now I am trying to implement a code or algorithm that calculates an actual range to detect any lies. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


<!-- # First Milestone
For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project -->

<!--**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**-->

# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/iHqNppQKoe8" title="Bradley T. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


My project is a lie detector, and it functions using an Arduino Nano and the Arduino IDE software. So far I have made a basic breadboard and successfully written some basic code that lights up the LEDs whenever there is a "change" in the input. There are 3 LEDs, a 2k resistor, and 6 wires in total. 3 of the wires go to the 3 LEDs, one acts as a ground cable to connect the LEDs to the Nano chip, and the remaining two are for the user's finger skin inputs. More specifically, a change that I noticed was that there was a difference in the original description/instructions of the lie detector, and that was that the range of the serial plotter (in voltage) differed depending on who was tested. In the original, the range was from 10-30, for myself it was from 900-1000, and for someone else it was in the 300s. So far I have hard-coded it to fit my fingers’ range of 900-1000, and I hope to implement a method in the code in which it will automatically detect a lie and won’t have to be hard-coded to tailor an individual person’s fingers. One main struggle that I faced was trying to solder the wires to the Arduino Nano board, especially when they were right next to each other, only millimeters away. This was also especially hard because the soldering iron’s tip was larger/wider than the distances between two pins, so it was very easy to accidentally create bridges in the soldering. 



  
 
 
<!--# Schematics 
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
-->
 
 


  
# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/8aJUYWMVYZE" title="Bradley T. Starter Project" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 
For my starter project I made an LED cat lamp. This project was relatively simple, all it required was for me to assemble the pieces of the lamp such as the body of the cat, and then attached all of the components such as the LED light or photoresister by soldering them onto their correct place. The final part was to put on all the other pieces for extra looks - such as adding the cat's arms - and installing the battery.
 

 
<!--
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.

-->
