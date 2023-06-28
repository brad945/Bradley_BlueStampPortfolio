# Lie Detector 
<!--Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
-->
Have you ever wanted to test out your friends' honesty? Now you can with this easy-to-build lie detector.
For my project I built a lie detector that lights up whenever it detects that someone may be lying. The only catch are this project's limitations in the factors in which it takes into account when determining if the user is lying or not, which includes condensation of the skin, and heartrate. Some of my biggest challenges and triumphs were soldering all of the components onto my final board, and coding an algorithm that determines the lighting up of the LED lights for when a "lie" is detected. 


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Bradley Tsou | Carlmont High School | Mechanical/Electrical Engineering | Incoming Junior

<!--
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)    
-->

  
# Final Milestone
<!--
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE
-->

<iframe width= "825" height="480" src="https://www.youtube.com/embed/wyVMV2opp0s" title="Bradley Milestone 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



For my third and final milestone I finalized my code and fixed everything into my 3D printed case. I also re-modified my finger wraps to be made out of velcro, aluminum foil, and electrical tape. For my code, the main issue was that there were two Serial.print() functions/statements, and I found out that you can only have one Serial.print() statement in a code, or else your values and code will malfunction like mine did. 

One small challenge for my 3D case was that the hole for where the arduino cable would go through was slightly offset of where I wanted it to be, so I learned how to dremel and modified it to my liking. Another one of my challenges was trying to get the board to be elevated inside of the case so that the LEDs could poke through their designated hole at the top. Apart from learning how to dremel, I also learned and used a file to make some of the cuts with the dremel more clean and smooth. 

Some of my biggest challenges in general I faced during my time at Bluestamp were mainly small minute details, and they taught me how sometimes the most trivial things can play a major role in determining your project's success and functionability. Some examples included accidentally creating a bridge between two ports or holes when soldering, or missing an end bracket ("}") in some places in my code, sometimes at the end of a loop or if-statement. For soldering, the more I practiced, the better I got, and for catching errors in my code, I learned how important organization is, especially because even the slightest mistake in the code stopped the entire program from working, and was usually tucked and hidden in a small  unexpected place in the hundreds of lines of code that I had. 

I feel that I can keep and retain many of the key skills that I learned all at Bluestamp - such as soldering, filing, dremeling, and working with circuitry and breadboards in general - to help me in my future path for engineering. I wish to not only expand my knowledge and experience in a potential future job but also to obtain more engineering skills and hone them down to perfection. 







# Second Milestone


<iframe width="825" height="480" src="https://www.youtube.com/embed/kPkh-QVg0Vo" title="Bradley T. Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



For my second milestone, I successfully transferred all of my components from my "draft" breadboard to a more professional soldering board. This process was very tedious and was actually much more difficult than I thought, as it was essentially all just soldering and de-soldering. I learned many things through doing this, such as learning new and better ways to solder and de-solder, and just getting better at both in general. 

My first main difficulty was dealing with a "faulty" solder board. It took a few tries and hours until I decided to use a new soldering board, since the one I was using would not stick with the solder at all. For example, the solder would be touching a wire and the board, and once you took the soldering iron away, the solder would sometimes just fall off. I was able to de-solder some things, but other components such as the actual Arduino Nano chip itself had to be replaced. 

My second main difficulty was a gap in my knowledge of breadboards. I based my breadboard model on a picture that was slightly vague in the instructions, and just blindly copied from the picture. It turns out that the breadboard was flipped upside down when I copied it, so I plugged my ground cable into the positive ground when it should have been in the negative. This caused even more problems in and of itself, as it fried my LEDs, and at the time I did not know why they were frying (I also learned that positive and negative current flow do not go well together!).

What I still need to do before my final milestone is completed is to finish up all my code for the project. Right now, I have a constant number that acts as a range for detecting when someone is "lying", but now I am trying to implement a code or algorithm that calculates an actual range to detect any lies. 






# First Milestone


<iframe width="825" height="480" src="https://www.youtube.com/embed/iHqNppQKoe8" title="Bradley T. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


My project is a lie detector, and it functions using an Arduino Nano and the Arduino IDE software. So far I have made a basic breadboard and successfully written some basic code that lights up the LEDs whenever there is a "change" in the input. There are 3 LEDs, a 2k resistor, and 6 wires in total. 3 of the wires go to the 3 LEDs, one acts as a ground cable to connect the LEDs to the Nano chip, and the remaining two are for the user's finger skin inputs. I also decided to solder some wires onto the Arduino Nano on the breadboard instead of just plugging them in, for some more soldering practice, but this turned out to be much harder than I had thought.

One change that I noticed was that there was a difference in the original description/instructions of the lie detector, and that was that the range of the serial plotter (in voltage) differed depending on who was tested. In the original, the range was from 10-30, for myself it was from 900-1000, and for someone else it was in the 300s. 

So far I have hard-coded it to fit my fingers’ range of 900-1000, and I hope to implement a method in the code in which it will automatically detect a lie and won’t have to be hard-coded to tailor an individual person’s fingers. One main struggle that I faced was trying to solder the wires to the Arduino Nano board, especially when they were right next to each other, only millimeters away. This was also especially hard because the soldering iron’s tip was larger/wider than the distances between two pins, so it was very easy to accidentally create bridges in the soldering. 





  
# Starter Project

<iframe width="825" height="480" src="https://www.youtube.com/embed/8aJUYWMVYZE" title="Bradley T. Starter Project" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 
For my starter project I made an LED cat lamp. This project was relatively simple, all it required was for me to assemble the pieces of the lamp such as the body of the cat, and then attached all of the components such as the LED light or photoresister by soldering them onto their correct place. The final part was to put on all the other pieces for extra looks - such as adding the cat's arms - and installing the battery. 
 


  
 
<!--# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

![lie detector schematics ](https://github.com/brad945/Bradley_BlueStampPortfolio/assets/136377695/b94a1574-4d65-4eaf-bc99-27134af4d54e)


-->

# Code

```c++

int bpmcount = 0;
bool tf = true;
bool ft = true;
long count = 0;
long delaycheck = 0;
int const PULSE_SENSOR_PIN = 0;  // 'S' Signal pin connected to A0
int Signal;                      // Store incoming ADC data. Value can range from 0-1024
int Threshold = 550;             // Determine which Signal to "count as a beat" and which to ignore.
const int buzzer = 9;


#define USE_ARDUINO_INTERRUPTS true  // Set-up low-level interrupts for most acurate BPM math.
#include <PulseSensorPlayground.h>   // Includes the PulseSensorPlayground Library.

//  Variables
const int PulseWire = 0;      // PulseSensor PURPLE WIRE connected to ANALOG PIN 0
const int LED = LED_BUILTIN;  // The on-board Arduino LED, close to PIN 13.
//int Threshold = 550;           // Determine which Signal to "count as a beat" and which to ignore.
// Use the "Gettting Started Project" to fine-tune Threshold Value beyond default setting.
// Otherwise leave the default "550" value.

PulseSensorPlayground pulseSensor;

void setup() {
  Serial.begin(9600);
  pinMode(buzzer, OUTPUT);
  pinMode(LED_BUILTIN, OUTPUT);
  pinMode(2, OUTPUT);   // Green LED
  pinMode(6, OUTPUT);   // Yellow LED
  pinMode(11, OUTPUT);  // Red LED
  digitalWrite(2, HIGH);
  delay(250);
  digitalWrite(6, HIGH);
  delay(250);
  digitalWrite(11, HIGH);
  delay(250);
  pulseSensor.analogInput(PulseWire);
  pulseSensor.blinkOnPulse(LED);  //auto-magically blink Arduino's LED with heartbeat.
  pulseSensor.setThreshold(Threshold);

  // Double-check the "pulseSensor" object was created and "began" seeing a signal.
  if (pulseSensor.begin()) {
    Serial.println("We created a pulseSensor Object !");  //This prints one time at Arduino power-up,  or on Arduino reset.
  }
}

void loop() {

  if (ft) {
    Serial.print("Calibrating.");
    ft = false;
    //delay(500);
  }
  if (!ft && bpmcount < 7) {
    Serial.print(".");
    digitalWrite(2, LOW);  // Green LED
    digitalWrite(6, LOW);  // Yellow LED
    digitalWrite(11, LOW);
    bpmcount++;
    delay(800);
  }

  if (bpmcount == 51) {
    Serial.println(" ");
    bpmcount++;
  }


  if (pulseSensor.sawStartOfBeat()) {  // Constantly test to see if "a beat happened".
    bpmcount == 50;
    bpmcount++;
    int myBPM = pulseSensor.getBeatsPerMinute();  // Calls function on our pulseSensor object that returns BPM as an "int".                                              // "myBPM" hold this BPM value now.
                                                  //Serial.print("BPM: ");                         // Print phrase "BPM: "
                                                  //Serial.println(myBPM);                         // Print the value inside of myBPM.
    if (myBPM > 108) {
      Serial.println("♥  A HeartBeat Happened ! ");
      Serial.print("-------------------------------------------------- LYING: ");
      Serial.print(myBPM);
      Serial.println(" BPM");
      digitalWrite(2, LOW);  // Green LED
      digitalWrite(6, LOW);  // Yellow LED
      digitalWrite(11, HIGH);
      tone(buzzer, 500);

    } else if (myBPM > 90) {
      Serial.println("♥  A HeartBeat Happened ! ");
      Serial.print("------------------------------------------------ MAYBE LYING: ");
      Serial.print(myBPM);
      Serial.println(" BPM");
      digitalWrite(2, LOW);   // Green LED
      digitalWrite(6, HIGH);  // Yellow LED
      digitalWrite(11, LOW);
      noTone(buzzer);

    } else {
      Serial.println("♥  A HeartBeat Happened ! ");
      Serial.print("----------------------------------------------- NOT LYING: ");
      Serial.print(myBPM);
      Serial.println(" BPM");
      digitalWrite(2, HIGH);  // Green LED
      digitalWrite(6, LOW);   // Yellow LED
      digitalWrite(11, LOW);
      noTone(buzzer);
    }
  }
}


```




# CAD Files

[case - main - bradley (1).zip](https://github.com/brad945/Bradley_BlueStampPortfolio/files/11885519/case.-.main.-.bradley.1.zip)

[case - lid - bradley (1).zip](https://github.com/brad945/Bradley_BlueStampPortfolio/files/11885522/case.-.lid.-.bradley.1.zip)


 




 
<!--
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Nano | The main component for the project, the microcontroller/chip | ~$25 | <a href="https://store-usa.arduino.cc/products/arduino-nano?srsltid=AR57-fBz_6umi3ljqdw_ObH-j1NlSPWRbpcJ4VfUPAbstS5qWNifoB0aOiA"> Link </a> |
|:--:|:--:|:--:|:--:|
| LED lights | Lights up when detects lie or vice versa | $12 for 450 | <a href="https://www.amazon.com/DiCUNO-450pcs-Colors-Emitting-Assorted/dp/B073QMYKDM/ref=sr_1_2_sspa?crid=CKYH6HRO418J&keywords=led+lights+breadboard+singular&qid=1687977865&sprefix=led+lights+breadbaord+singul%2Caps%2C197&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
|:--:|:--:|:--:|:--:|
| Male to Male wires | Connects all the components on the board | $6.50 for 80 | <a href="https://www.amazon.com/GenBasic-Solderless-Dupont-Compatible-Breadboard-Prototyping/dp/B01L5UJ36U/ref=sr_1_2?crid=X626UMDSFLWM&keywords=male+to+male+wires&qid=1687978076&sprefix=male+to+male+wire%2Caps%2C139&sr=8-2"> Link </a> |
|:--:|:--:|:--:|:--:|

| Heartrate sensor | Sensor for heartrate upon touch with skin | $25 | <a href="https://pulsesensor.com/products/pulse-sensor-amped
"> Link </a> |
|:--:|:--:|:--:|:--:|


# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.

-->
