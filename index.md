# BlueStamp PyPortal Titano Weather Station
The PyPortal Titano Retro Weather Station displays the local temperature, weather conditions, time, and date. It also contains a customizable alarm system, with multiple daily and weekly alarms. Packed in a cool 3-D printed case, the Retro Weather Station looks like a small television. 

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Pranati T | Dougherty Valley High School | Computer Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my final milestone, I attached a 3-D printed case to my PyPortal setup. One struggle I had was that the case arrived, but no screws to fasten the case to the screen. I ended up using strings to tie the parts together, and it worked. This last milestone was the last aesthetic touch 
to my project. Moving forward, I am interested in exploring what I can connect this project to using the I2C connection. I have either the option of connecting another PyPortal or even an Arduino to the existing PyPortal. 


# Second Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/AbE_icsdvMQ?si=x97JDMhAw7-ACikj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my second milestone, I customized the display and sounds of the alarm system of the project. When an alarm comes, a custom image screen drawn by me appears, and an audio of my choice plays instead of the default robot. I faced the error that although my file types for the audio files matched the original ones, the sounds were not playing. After some research, I found that the only way to make custom WAV files play on the device is to convert them from MP3 to WAV file types using Audacity. Using the following tutorial: https://learn.adafruit.com/microcontroller-compatible-audio-file-conversion I was able to resolve this issue and make my audios play without any errors.  


# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/GuVc0ztC_dc?si=6TpYgbjbguBpFGdl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


My first milestone was assembling my baseline project and troubleshooting any errors I faced. I downloaded all of the files correctly, but repeatedly recieved an error in one of my code files. This code file was one of the files that came with the project bundle, so it did not make sense that there was an error in its code. After a few days of trying to fix the error, we realized that the device was not started up correctly. Following the steps to reboot the device fixed everything, and it magically began to work. In my next milestone, I want to make a second screen which can be switched to with the click of a button. This screen would display weekly alarms and their times. 

# Schematics 
![Headstone Image](3d_printing_circuit-diagram.jpg)

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
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Adafruit PyPortal Titano | The device on which the entire project is run | $59.95 | <a href="https://www.adafruit.com/product/4444"> Link </a> |
| STEMMA Wired Tactile Push-Button Pack - 5 Color Pack | Used for the dismiss/snooze commands on the alarms | $7.50 | <a href="https://www.adafruit.com/product/4431"> Link </a> |
| JST PH 2mm 3-pin Plug-Plug Cable - 100mm long | Used to connect the STEMMA Push-Buttons to the Pyportal Titano | $0.75 | <a href="https://www.adafruit.com/product/4336"> Link </a> |
| Mini Oval Speaker - 8 Ohm 1 Watt | Plays sounds that come from the device, connected directly to the PyPortal Titano | $1.95 | <a href="https://www.adafruit.com/product/3923"> Link </a> |
| Black Nylon Machine Screw and Stand-off Set – M2.5 Thread | Used to secure the 3-D printed case onto the PyPortal screen | $16.95 | <a href="https://www.adafruit.com/product/3299"> Link </a> |
| 5V 1A (1000mA) USB port power supply - UL Listed | Used to connect the PyPortal to a wall electrical outlet  | $5.95 | <a href="https://www.adafruit.com/product/501"> Link </a> |
| USB Type A to Type C Cable - approx 1 meter / 3 ft long | Used to connect PyPortal Titano to either a computer or other power source. When connected to a computer, the USB cable is used to save code from the computer and update the project screen. When used to plug into a wall electrical outlet, the cable works to supply power to the device. | $4.95 | <a href="https://www.adafruit.com/product/4474"> Link </a> |
| 8GB micro SD Card | Used to store high-storage files which the PyPortal Titano does not have the storage to store in itself | $9.95 | <a href="https://www.adafruit.com/product/2692"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
