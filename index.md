# Third Eye for The Blind
<!---
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
-->

My project, "Third Eye for the Blind" is a wearable technology project designed to assist visually impaired individuals in navigating their surroundings. The wearable device uses speakers, sensors, Bluetooth, and motors, providing real-time audio or haptic feedback for safer navigation. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Nabhan Singh | Design Tech High School | Electrical Engineering | Incoming Sophomore

<!---
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**
-->
![Headstone Image](Nabhan-Headshot.png){: height="50%" width="50%"}
  
# Final Milestone
<!---
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE
-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BH6_-c2tB2Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Since my previous milestone, I have made my project wearable and practical to use. I first downsized the project by about 50% and fit it all on one main surface. I put straps on the prototype so that anyone can wear them on their forearms/hands. I put the ultrasonic sensor on the back of the hand, the temperature sensor on the end of your middle finger, and moved the help button to an isolated place. I moved the button to a perf board and soldered it on. I hot-glued the battery pack to the side of the breadboard. I also made the wiring a tad bit cleaner

Without a doubt, my biggest challenge was the customization step. Specifically implementing the help button feature. When I started I had no idea what I was doing or how to even start. It stumped me for so long. Talking about starting, one other challenge was always starting everything. I believe in the phrase that the first step is always the hardest. This was the case for me throughout the whole project. Once I found out how to start everything else came relatively easy.

Some of my biggest triumphs was finishing the project. That was such a sign of relief. This was equally as fun as it was intense and this project was a lot of fun. So once I finished the project, I felt extremely accomplished and happy to bring my creation to life.
Finish.

Some things I learned were the basics of coding in C++. More specifically, I learned things like how to comment on lines of code, the different libraries, loops, conditional statements, arrays, functions, how to combine multiple sketches, and much more. Another thing I learned is how to handle audio files. I learned how to successfully condense and modify the files to a degree where you are able to upload them to an Arduino Nano without an SD card. One of the most important things that I learned was how to research key parts in my project, how to implement those parts, and be able to combine everything together to get a project of my design. 

I love learning new things. I want to learn about everything but one thing this camp helped foster was my fascination with electrical engineering. It drives technological advancement, requires problem-solving skills and creativity, has broad applicability across industries, encourages constant innovation, and involves collaboration and teamwork. These aspects make it an intellectually stimulating and rewarding field. 

# Second Milestone

<!---
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to YouTube, click Share -> Embed, and copy and paste the code to replace what's below.**
-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aJhYZ5yLmZg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

What I've added to my project is a temperature sensor that uses a speaker to tell you when an object is too hot and unsafe to touch, a Bluetooth module with a voltage divider and a button, and uploaded audio files to the board without an SD card. The temperature sensor can be used in a situation where something is too hot and unsafe to touch. Since the blind person can't see how far the aforementioned hot object is, this would tell you to not get closer. I added audio files to the board so that the speaker can tell you that something is not rather than having another sound to indicate that something is. I added a Bluetooth module with a button because I wanted to add a help button just in case the person is in an unsafe situation and needs to alert someone.

What has been surprising about this project is how much wire and space it takes. When I first started I thought this would barely take a space and I could add a lot of modifications. This was not the case. I thought I would need full body armor to fit the few modifications I added. Full body armor would be cool either way though. 

One challenge I faced was integrating the Bluetooth feature. When I first started I knew nothing about how to implement Bluetooth, but I knew I needed to find out if I wanted to create a help button. I ended up creating an app to connect to the Bluetooth module and receive help messages. That ended up not working. The Bluetooth module connected with my phone but not my app. So I ditched the app I so meticulously created and installed a serial monitor instead which worked much better.

For my final milestone, I need to do 3 things. The first thing is to find a way to reduce the amount of space my project takes up. Next, I need to make it wearable and not a hindrance for the user to wear. The final step would be to test it out. Once I complete all of those things I should be done


# First Milestone: Breadboard Prototype

<iframe width="560" height="315" src="https://www.youtube.com/embed/d5VwIi9DM20" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

There are 7 different parts. 
-  A slide switch: a switch that slides between 2 settings and I use it to switch between the buzzer and the motor.
-  LED: a semiconductor device that emits light when current flows through it and is used to indicate if the circuit is working.
-  200 ohms resistor: a  resistor that limits the flow of electrons through a circuit to around 200 ohms.
-  Ultrasonic sensor: an electronic device that measures the distance of a target object by emitting ultrasonic sound waves and converts the reflected sound into an electrical signal. Then those signals are used to turn on either the buzzer or the motor.
-  Arduino nano: is like the brain of the whole thing. It is a microcontroller that reads inputs and gives outputs.
-  Buzzer: an audio signaler device that is used to indicate to the user that something is close by.
-  DC 3V vibration motor: a small motor that vibrates when something is close by.

 In terms of technical progress, I finished creating and designing a working prototype, while also documenting every step of the processes. I created my working prototype using all the parts mentioned above. Thanks to the functionality of the breadboard I was able to test and try out different iterations of the prototype to find a way to make it work perfectly. Once I found the perfect layout for the mechanical parts, I put the code into the circuit and started to test it out. 

Some challenges were just finding out how to even start on the breadboard. I was completely lost at first and didn't know what I was doing. But with a little bit of guidance and knowledge, I figured out how to do it and do anything I like now.

What's next is to finish my second milestone by researching what I will do to customize my project and add features users may need. 

# Starter Project: Art Deco Mini Cat Lamp

<iframe width="560" height="315" src="https://www.youtube.com/embed/7I7oJT4viuw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


I had 5 different parts. The transistor, resistor, LED, photoresistor, a switch, and the battery 
For those who don't know, a transistor is a mini semiconductor that is used to amplify or switch electrical signals and power.  is an electrical component that limits or regulates the flow of electrical current in an electronic circuit. A photoresistor is a sensor that changes its resistance when light shines on it.

What I most enjoyed about this project is definitely soldering everything together. I enjoy soldering a lot.  It also helps teach my hand to be very steady and precise. There is one part I struggled with is desoldering the photoresistor because as you can see it is a bit twisted and high. I wasn't able to desolder it correctly so I had to resolve it and bend it up. It doesn't affect the performance of the project only the look

Then my next step is to start on my intermediate project which is the Third Eye for the Blind

<iframe width="560" height="315" src="https://www.youtube.com/embed/7I7oJT4viuw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!---
**Don't forget to replace the text below with the embedding for your milestone video. Go to YouTube, click Share -> Embed, and copy and paste the code to replace what's below.**
-->
# Schematics 
<!---
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resources for creating professional schematic diagrams, though BSE recommends Tinkercad because it can be done easily and for free in the browser. 
-->
# Code
<!---
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 
-->

```#include <PCM.h>
// speaker
const unsigned char sample[] PROGMEM = {
129, 129, 128, 127, 127, 127, 127, 127, 127, 127, 127, 128, 128, 127, 128, 129, 128, 128, 127, 126, 127, 128, 127, 126, 127, 128, 128, 128, 128, 128, 128, 128, 128, 127, 126, 127, 127, 126, 127, 128, 127, 128, 128, 128, 128, 129, 129, 128, 128, 127, 127, 128, 128, 127, 126, 126, 127, 128, 127, 127, 128, 129, 129, 129, 128, 127, 128, 128, 127, 126, 127, 127, 127, 128, 128, 128, 127, 127, 128, 127, 127, 128, 127, 127, 128, 129, 128, 128, 128, 128, 128, 128, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 128, 128, 128, 127, 127, 128, 128, 128, 127, 127, 127, 127, 128, 128, 127, 127, 128, 127, 127, 128, 128, 128, 128, 128, 128, 128, 128, 128, 127, 127, 128, 128, 127, 127, 128, 128, 127, 127, 127, 128, 128, 127, 128, 128, 127, 128, 128, 128, 127, 127, 127, 127, 127, 128, 128, 128, 128, 129, 127, 127, 128, 127, 126, 128, 127, 127, 129, 128, 128, 128, 128, 128, 127, 126, 126, 127, 127, 128, 128, 127, 129, 130, 128, 127, 128, 127, 126, 128, 128, 127, 127, 129, 128, 128, 129, 129, 127, 126, 127, 127, 127, 126, 126, 127, 128, 127, 127, 128, 127, 127, 128, 128, 127, 128, 128, 128, 128, 128, 128, 128, 127, 128, 128, 127, 126, 127, 128, 128, 127, 127, 127, 128, 128, 125, 128, 128, 124, 128, 129, 126, 129, 127, 126, 131, 128, 126, 129, 128, 128, 127, 125, 129, 128, 125, 128, 128, 126, 128, 129, 128, 127, 127, 128, 126, 123, 123, 127, 131, 129, 127, 124, 126, 134, 136, 130, 126, 126, 135, 138, 128, 124, 126, 123, 128, 126, 113, 115, 126, 133, 129, 117, 128, 150, 142, 128, 128, 125, 128, 136, 124, 107, 115, 136, 137, 124, 124, 132, 136, 137, 130, 119, 115, 125, 136, 124, 108, 124, 140, 133, 131, 131, 122, 131, 144, 133, 114, 117, 130, 133, 121, 111, 120, 130, 132, 136, 134, 129, 138, 146, 140, 129, 119, 122, 135, 127, 112, 115, 118, 121, 129, 122, 115, 123, 129, 138, 146, 135, 133, 149, 151, 139, 131, 121, 119, 121, 106, 98, 109, 114, 114, 123, 133, 139, 143, 143, 146, 144, 137, 137, 133, 121, 121, 123, 113, 108, 117, 120, 114, 115, 122, 131, 132, 123, 130, 148, 137, 121, 137, 139, 119, 125, 134, 120, 118, 132, 134, 124, 119, 122, 131, 133, 122, 115, 121, 133, 141, 133, 120, 132, 149, 139, 125, 127, 125, 125, 130, 120, 111, 124, 131, 128, 130, 129, 130, 145, 144, 124, 118, 132, 140, 131, 118, 118, 127, 137, 136, 118, 111, 133, 145, 125, 118, 130, 129, 132, 142, 130, 118, 127, 131, 129, 126, 115, 113, 123, 121, 113, 117, 123, 125, 131, 141, 140, 132, 137, 142, 133, 124, 122, 122, 121, 116, 114, 119, 120, 122, 128, 126, 126, 134, 140, 134, 131, 139, 138, 128, 129, 134, 127, 119, 121, 127, 125, 117, 118, 125, 122, 120, 124, 121, 123, 136, 142, 136, 136, 141, 144, 146, 140, 126, 123, 130, 125, 111, 105, 110, 117, 124, 126, 121, 126, 147, 154, 139, 131, 136, 138, 131, 118, 114, 126, 130, 122, 124, 133, 137, 138, 132, 125, 126, 125, 124, 123, 115, 117, 130, 132, 136, 145, 141, 139, 149, 153, 144, 131, 126, 131, 129, 114, 106, 119, 130, 124, 124, 132, 132, 137, 143, 135, 129, 133, 135, 134, 129, 126, 126, 124, 126, 128, 116, 110, 121, 125, 118, 114, 119, 128, 135, 130, 124, 126, 132, 133, 127, 119, 117, 120, 119, 116, 114, 112, 114, 121, 121, 115, 118, 129, 133, 128, 126, 126, 125, 129, 126, 116, 116, 125, 121, 116, 121, 125, 124, 125, 129, 129, 126, 126, 127, 123, 121, 123, 124, 125, 122, 123, 133, 135, 130, 132, 128, 120, 126, 132, 125, 118, 125, 134, 136, 135, 130, 127, 132, 137, 133, 126, 124, 136, 146, 140, 143, 156, 158, 157, 158, 156, 151, 141, 135, 139, 129, 120, 128, 134, 137, 146, 147, 146, 153, 152, 141, 130, 123, 122, 120, 113, 108, 112, 117, 120, 123, 125, 121, 120, 121, 120, 116, 111, 110, 115, 115, 111, 113, 112, 111, 116, 114, 108, 112, 116, 112, 113, 116, 115, 118, 120, 117, 118, 120, 119, 120, 117, 112, 116, 122, 117, 115, 124, 131, 128, 126, 131, 135, 131, 123, 121, 123, 120, 118, 118, 117, 124, 131, 127, 127, 132, 130, 129, 132, 128, 121, 123, 127, 123, 118, 119, 122, 128, 126, 123, 133, 139, 135, 142, 146, 141, 145, 147, 140, 142, 153, 156, 152, 157, 170, 171, 165, 162, 155, 147, 144, 134, 124, 127, 128, 124, 125, 138, 146, 141, 146, 159, 155, 145, 143, 139, 131, 128, 122, 112, 110, 116, 112, 103, 104, 111, 114, 114, 114, 117, 119, 121, 123, 120, 116, 121, 125, 117, 111, 113, 112, 109, 109, 103, 98, 101, 106, 110, 108, 106, 118, 130, 127, 126, 131, 131, 133, 135, 125, 116, 121, 122, 112, 108, 109, 110, 110, 116, 122, 123, 125, 138, 140, 130, 131, 137, 130, 120, 119, 116, 112, 116, 119, 117, 115, 114, 115, 118, 117, 118, 130, 143, 150, 161, 174, 183, 191, 196, 191, 178, 168, 160, 145, 125, 115, 110, 104, 105, 111, 115, 123, 139, 153, 160, 164, 170, 172, 169, 165, 154, 139, 132, 130, 124, 112, 104, 107, 111, 112, 111, 111, 114, 123, 129, 125, 121, 125, 127, 123, 119, 115, 110, 109, 110, 106, 101, 99, 102, 103, 101, 99, 100, 104, 108, 111, 114, 117, 119, 123, 125, 120, 116, 117, 116, 111, 112, 113, 111, 116, 123, 122, 121, 127, 129, 127, 128, 126, 124, 127, 127, 122, 118, 117, 114, 109, 105, 101, 95, 90, 97, 112, 122, 133, 161, 191, 209, 226, 238, 235, 225, 213, 189, 153, 125, 112, 100, 86, 85, 96, 106, 119, 141, 153, 149, 154, 165, 161, 149, 144, 143, 141, 140, 139, 138, 137, 139, 142, 138, 128, 122, 121, 115, 111, 110, 106, 103, 112, 121, 120, 121, 128, 131, 128, 122, 115, 108, 103, 100, 95, 92, 94, 98, 102, 106, 111, 114, 117, 121, 122, 119, 114, 113, 115, 112, 108, 108, 108, 107, 111, 116, 116, 118, 125, 131, 130, 127, 125, 123, 121, 116, 108, 99, 93, 93, 92, 87, 84, 91, 109, 130, 148, 166, 196, 228, 248, 252, 249, 238, 220, 190, 148, 108, 79, 59, 50, 55, 70, 92, 121, 151, 177, 190, 187, 185, 186, 172, 148, 131, 122, 114, 109, 104, 101, 110, 122, 127, 134, 143, 148, 153, 157, 151, 141, 134, 128, 120, 109, 103, 102, 101, 103, 108, 109, 107, 109, 112, 108, 102, 98, 97, 103, 107, 108, 112, 119, 123, 127, 126, 118, 114, 114, 108, 102, 100, 97, 101, 114, 121, 120, 124, 130, 133, 131, 126, 117, 110, 111, 111, 106, 101, 103, 107, 110, 112, 101, 87, 95, 115, 121, 133, 169, 204, 223, 243, 255, 255, 245, 222, 186, 141, 94, 51, 24, 21, 37, 55, 76, 117, 167, 197, 206, 211, 211, 199, 180, 156, 134, 122, 118, 114, 111, 109, 108, 113, 119, 119, 120, 127, 137, 150, 161, 165, 166, 166, 160, 147, 129, 109, 94, 85, 79, 77, 79, 86, 97, 108, 111, 114, 119, 121, 120, 120, 118, 114, 117, 120, 116, 110, 104, 99, 98, 97, 94, 96, 103, 109, 115, 122, 128, 133, 134, 129, 123, 120, 115, 110, 111, 110, 107, 105, 100, 92, 97, 106, 109, 126, 162, 193, 214, 234, 251, 255, 250, 227, 186, 139, 95, 54, 24, 18, 32, 53, 75, 108, 148, 180, 199, 212, 214, 203, 187, 167, 149, 138, 126, 117, 115, 110, 105, 106, 104, 98, 97, 98, 99, 110, 131, 147, 160, 177, 191, 199, 198, 185, 163, 142, 117, 90, 69, 57, 52, 55, 67, 87, 106, 121, 136, 149, 154, 152, 146, 134, 122, 110, 96, 86, 82, 80, 82, 88, 94, 99, 105, 112, 117, 118, 122, 126, 129, 133, 139, 141, 139, 134, 128, 121, 111, 92, 67, 58, 72, 89, 108, 146, 184, 213, 237, 254, 255, 248, 226, 190, 142, 92, 47, 18, 20, 41, 58, 77, 111, 154, 190, 205, 211, 216, 209, 192, 174, 160, 148, 138, 132, 125, 112, 98, 90, 83, 75, 70, 73, 85, 107, 131, 152, 168, 185, 195, 191, 177, 160, 139, 121, 111, 105, 98, 101, 112, 123, 128, 128, 126, 121, 113, 107, 102, 95, 96, 102, 110, 118, 122, 122, 119, 116, 110, 99, 88, 84, 83, 85, 90, 96, 105, 113, 121, 130, 130, 126, 130, 132, 126, 124, 120, 113, 108, 102, 96, 90, 85, 87, 105, 128, 148, 177, 212, 234, 250, 255, 249, 227, 201, 156, 105, 71, 41, 17, 22, 44, 62, 88, 129, 168, 197, 211, 215, 212, 204, 188, 168, 147, 132, 123, 113, 101, 92, 84, 78, 77, 79, 82, 91, 107, 128, 150, 168, 179, 188, 192, 182, 164, 143, 117, 97, 86, 75, 73, 86, 105, 125, 144, 162, 175, 177, 172, 161, 140, 119, 102, 89, 80, 77, 80, 90, 101, 111, 119, 123, 126, 123, 116, 110, 104, 100, 102, 104, 108, 112, 116, 122, 126, 125, 124, 121, 118, 117, 116, 114, 116, 116, 112, 110, 109, 108, 115, 129, 141, 159, 186, 208, 223, 237, 239, 223, 200, 171, 131, 91, 58, 36, 30, 39, 55, 79, 112, 146, 178, 198, 206, 208, 202, 187, 170, 152, 135, 120, 110, 104, 98, 92, 92, 92, 92, 96, 104, 114, 127, 143, 158, 168, 175, 179, 172, 161, 146, 124, 103, 89, 78, 72, 73, 84, 102, 121, 142, 164, 180, 189, 192, 187, 174, 154, 132, 108, 85, 68, 62, 60, 66, 79, 97, 114, 128, 139, 145, 144, 137, 127, 116, 106, 100, 97, 96, 101, 107, 111, 116, 122, 125, 125, 125, 124, 121, 118, 118, 115, 113, 116, 114, 113, 124, 136, 145, 158, 177, 194, 204, 208, 203, 187, 165, 143, 114, 86, 65, 54, 54, 66, 84, 107, 131, 155, 176, 187, 188, 183, 173, 161, 148, 134, 122, 113, 110, 108, 104, 102, 104, 104, 107, 111, 117, 125, 135, 146, 154, 159, 161, 159, 152, 141, 128, 113, 100, 92, 88, 89, 93, 102, 115, 131, 145, 155, 165, 174, 177, 173, 164, 151, 137, 123, 106, 89, 78, 74, 75, 83, 95, 107, 122, 135, 145, 147, 142, 136, 127, 115, 108, 103, 96, 97, 104, 110, 114, 117, 123, 127, 128, 130, 130, 130, 132, 134, 133, 130, 129, 128, 123, 121, 128, 135, 139, 152, 167, 179, 189, 195, 188, 172, 155, 135, 110, 89, 76, 69, 70, 83, 101, 118, 137, 158, 171, 175, 174, 170, 160, 149, 139, 130, 120, 116, 114, 110, 107, 107, 107, 107, 109, 115, 121, 128, 139, 147, 151, 154, 154, 148, 139, 129, 118, 108, 101, 96, 95, 98, 106, 115, 121, 130, 142, 150, 153, 157, 162, 162, 158, 153, 144, 129, 116, 103, 90, 81, 78, 81, 90, 101, 115, 129, 140, 145, 143, 137, 128, 115, 104, 97, 94, 95, 99, 108, 119, 128, 134, 137, 135, 128, 123, 122, 121, 120, 125, 131, 135, 139, 140, 138, 138, 139, 137, 133, 135, 143, 152, 161, 168, 168, 164, 155, 143, 128, 113, 101, 93, 92, 99, 110, 122, 139, 154, 162, 165, 165, 159, 149, 139, 131, 124, 119, 118, 118, 118, 120, 122, 121, 120, 119, 119, 120, 122, 128, 133, 138, 144, 145, 143, 138, 131, 122, 113, 108, 105, 103, 105, 111, 119, 126, 132, 137, 139, 140, 140, 140, 140, 143, 145, 145, 144, 140, 133, 123, 113, 102, 93, 89, 90, 95, 103, 115, 127, 136, 141, 142, 138, 130, 122, 113, 104, 100, 101, 103, 110, 118, 122, 125, 126, 128, 128, 128, 129, 130, 129, 132, 135, 135, 136, 135, 131, 126, 124, 123, 122, 128, 139, 148, 157, 165, 167, 165, 159, 147, 131, 117, 106, 98, 95, 99, 106, 117, 130, 140, 147, 151, 153, 151, 146, 140, 135, 131, 127, 125, 123, 122, 119, 117, 117, 115, 115, 117, 120, 124, 130, 137, 142, 144, 145, 142, 135, 128, 121, 114, 109, 108, 109, 113, 119, 125, 130, 133, 136, 137, 136, 134, 132, 131, 132, 133, 135, 139, 140, 139, 137, 133, 127, 121, 116, 110, 107, 109, 112, 116, 122, 127, 131, 132, 132, 128, 123, 117, 112, 108, 106, 108, 111, 116, 121, 126, 129, 131, 133, 132, 129, 128, 128, 128, 130, 131, 131, 130, 132, 133, 131, 129, 131, 133, 136, 141, 148, 154, 158, 160, 158, 152, 145, 135, 125, 116, 110, 109, 111, 117, 123, 130, 137, 142, 144, 143, 141, 139, 134, 131, 129, 126, 125, 125, 124, 122, 120, 119, 118, 118, 119, 120, 123, 127, 131, 132, 133, 133, 131, 128, 124, 120, 116, 115, 115, 116, 118, 121, 123, 125, 127, 128, 128, 127, 128, 128, 128, 128, 127, 127, 126, 126, 125, 126, 127, 128, 130, 133, 135, 135, 134, 131, 127, 122, 117, 113, 111, 110, 113, 117, 123, 128, 132, 134, 134, 131, 127, 121, 117, 114, 113, 114, 117, 122, 125, 129, 132, 135, 135, 133, 130, 127, 126, 126, 127, 127, 128, 128, 128, 127, 126, 123, 121, 123, 126, 129, 134, 140, 145, 148, 149, 146, 141, 137, 130, 123, 118, 115, 115, 117, 121, 125, 129, 132, 134, 135, 135, 134, 132, 131, 130, 130, 129, 128, 128, 127, 125, 125, 124, 124, 125, 127, 130, 133, 136, 137, 137, 136, 134, 130, 127, 125, 124, 123, 124, 126, 128, 130, 131, 132, 132, 131, 131, 129, 127, 127, 128, 127, 128, 129, 129, 129, 128, 127, 126, 125, 125, 125, 127, 129, 132, 135, 137, 139, 139, 136, 133, 129, 124, 119, 116, 115, 116, 118, 122, 126, 130, 133, 134, 134, 132, 129, 125, 121, 117, 115, 115, 115, 117, 120, 123, 125, 128, 130, 130, 130, 129, 128, 128, 128, 127, 127, 127, 126, 126, 125, 124, 125, 126, 128, 131, 135, 138, 140, 142, 142, 141, 138, 134, 129, 125, 121, 118, 118, 118, 120, 124, 127, 130, 133, 134, 135, 136, 134, 132, 129, 126, 124, 122, 119, 118, 118, 119, 121, 123, 125, 127, 129, 130, 130, 129, 127, 125, 124, 122, 121, 120, 120, 121, 122, 123, 123, 123, 124, 124, 124, 124, 124, 125, 126, 127, 127, 127, 127, 127, 126, 124, 124, 124, 124, 125, 126, 127, 128, 129, 130, 130, 129, 129, 129, 128, 128, 128, 128, 128, 128, 127, 127, 127, 128, 129, 131, 133, 134, 134, 135, 134, 131, 129, 127, 124, 123, 123, 124, 125, 127, 129, 131, 132, 134, 134, 133, 132, 131, 130, 128, 127, 126, 125, 124, 123, 123, 124, 125, 125, 126, 128, 130, 132, 133, 133, 132, 131, 129, 128, 127, 126, 125, 125, 126, 127, 129, 129, 130, 131, 131, 130, 128, 127, 128, 128, 128, 128, 128, 130, 131, 131, 130, 129, 128, 128, 128, 127, 126, 126, 128, 128, 128, 128, 128, 128, 128, 128, 127, 127, 128, 129, 128, 127, 126, 125, 124, 123, 123, 123, 124, 125, 127, 128, 128, 129, 129, 128, 127, 126, 126, 125, 126, 126, 126, 126, 127, 127, 127, 127, 126, 126, 125, 125, 124, 123, 124, 125, 127, 128, 129, 130, 130, 130, 128, 127, 125, 124, 124, 124, 124, 125, 127, 128, 128, 129, 130, 129, 128, 129, 128, 128, 128, 127, 127, 127, 127, 127, 127, 129, 129, 130, 130, 131, 131, 131, 130, 129, 128, 126, 125, 125, 124, 123, 124, 125, 126, 127, 128, 129, 129, 130, 130, 129, 127, 126, 124, 123, 121, 121, 121, 122, 124, 126, 127, 128, 130, 130, 130, 130, 128, 127, 127, 127, 125, 124, 123, 125, 126, 128, 130, 132, 133, 134, 135, 134, 131, 129, 127, 126, 126, 126, 126, 126, 127, 130, 131, 131, 131, 131, 132, 132, 132, 130, 129, 128, 129, 127, 125, 125, 126, 126, 126, 127, 127, 126, 127, 127, 126, 126, 126, 126, 128, 128, 128, 128, 127, 127, 127, 127, 126, 126, 127, 128, 129, 129, 129, 129, 130, 130, 129, 128, 127, 127, 127, 126, 126, 126, 127, 128, 128, 128, 128, 129, 130, 129, 129, 129, 127, 127, 128, 128, 127, 128, 129, 129, 129, 128, 127, 127, 126, 127, 128, 128, 128, 130, 131, 131, 131, 132, 131, 130, 129, 128, 126, 124, 122, 122, 122, 123, 124, 126, 128, 130, 131, 130, 128, 127, 125, 123, 122, 122, 123, 123, 123, 125, 125, 126, 127, 128, 128, 128, 128, 128, 127, 127, 126, 124, 123, 124, 123, 123, 123, 125, 126, 129, 132, 133, 134, 135, 135, 133, 130, 128, 124, 122, 121, 123, 125, 128, 131, 133, 135, 135, 134, 133, 130, 129, 128, 127, 127, 127, 126, 126, 126, 127, 127, 127, 128, 129, 129, 130, 128, 127, 125, 124, 125, 125, 126, 127, 128, 128, 128, 127, 125, 123, 123, 124, 125, 126, 127, 128, 129, 129, 129, 128, 127, 126, 126, 126, 127, 127, 127, 127, 127, 127, 127, 126, 127, 128, 129, 130, 130, 130, 129, 128, 128, 128, 128, 128, 128, 130, 130, 129, 128, 128, 128, 128, 128, 128, 127, 127, 127, 127, 127, 126, 126, 127, 127, 126, 126, 126, 126, 127, 128, 128, 128, 128, 127, 127, 126, 126, 126, 126, 127, 127, 128, 128, 128, 129, 129, 129, 128, 127, 127, 126, 125, 125, 125, 126, 127, 128, 129, 129, 128, 127, 127, 126, 125, 126, 127, 127, 127, 128, 129, 128, 128, 128, 127, 126, 127, 129, 129, 128, 129, 129, 129, 128, 127, 126, 126, 128, 129, 130, 130, 131, 131, 130, 129, 128, 127, 126, 126, 126, 126, 126, 125, 125, 125, 125, 125, 125, 127, 127, 127, 128, 128, 127, 127, 127, 126, 124, 125, 126, 125, 124, 125, 127, 127, 127, 127, 129, 129, 128, 128, 129, 128, 126, 126, 126, 126, 126, 127, 127, 126, 127, 129, 129, 128, 128, 129, 130, 130, 130, 129, 128, 128, 128, 127, 128, 128, 128, 129, 130, 130, 129, 129, 129, 129, 129, 129, 129, 128, 128, 128, 128, 128, 128, 129, 130, 130, 130, 129, 129, 128, 127, 127, 128, 128, 128, 128, 129, 129, 128, 128, 128, 128, 127, 126, 126, 126, 126, 126, 126, 127, 127, 127, 127, 126, 126, 126, 126, 126, 127, 127, 128, 127, 127, 127, 127, 126, 126, 126, 126, 126, 125, 126, 126, 126, 127, 127, 127, 128, 129, 128, 128, 127, 127, 126, 126, 126, 126, 126, 127, 128, 127, 127, 127, 126, 126, 125, 126, 126, 126, 127, 128, 128, 128, 128, 128, 127, 128, 127, 126, 126, 126, 126, 125, 126, 128, 128, 128, 129, 130, 129, 128, 129, 129, 128, 128, 128, 126, 126, 126, 126, 126, 126, 127, 127, 128, 129, 128, 128, 128, 128, 128, 128, 127, 126, 126, 128, 128, 127, 127, 127, 127, 128, 128, 127, 128, 129, 129, 128, 127, 128, 127, 126, 128, 129, 127, 127, 128, 128, 127, 127, 127, 125, 125, 127, 128, 126, 125, 128, 129, 129, 128, 128, 128, 127, 128, 128, 126, 126, 126, 127, 127, 126, 126, 127, 127, 127, 128, 128, 128, 128, 128, 129, 128, 127, 128, 128, 128, 128, 127, 127, 126, 126, 127, 127, 127, 128, 128, 128, 129, 128, 129, 129, 128, 128, 128, 127, 127, 127, 127, 128, 127, 128, 128, 128, 127, 127, 127, 127, 128, 128, 128, 128, 128, 129, 129, 128, 128, 128, 128, 128, 129, 128, 127, 127, 127, 127, 127, 128, 128, 129, 129, 129, 129, 129, 129, 129, 130, 130, 129, 129, 128, 128, 127, 127, 127, 127, 127, 127, 128, 128, 127, 128, 128, 128, 128, 128, 128, 127, 127, 127, 127, 127, 127, 127, 128, 127, 127, 127, 127, 127, 127, 126, 126, 127, 126, 127, 128, 127, 128, 129, 128, 127, 127, 128, 128, 126, 127, 127, 127, 127, 127, 127, 127, 128, 129, 129, 128, 128, 128, 129, 128, 127, 128, 128, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 128, 128, 127, 127, 128, 128, 127, 126, 127, 127, 126, 126, 127, 127, 127, 127, 127, 128, 128, 127, 127, 127, 127, 127, 127, 128, 127, 127, 128, 127, 127, 127, 127, 127, 127, 127, 127, 126, 126, 127, 126, 127, 127, 127, 128, 128, 126, 127, 128, 126, 127, 126, 127, 128, 127, 126, 128, 128, 126, 126, 127, 128, 127, 127, 127, 127, 127, 128, 127, 127, 128, 129, 129, 127, 127, 129, 128, 127, 129, 129, 128, 129, 128, 128, 129, 127, 128, 130, 129, 129, 130, 128, 129, 130, 128, 129, 130, 129, 130, 130, 129, 129, 129, 129, 129, 128, 130, 130, 128, 129, 129, 128, 129, 128, 128, 128, 128, 128, 128, 128, 128, 127, 128, 128, 127, 127, 127, 127, 128, 127, 127, 128, 127, 127, 128, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 126, 127, 127, 126, 126, 127, 127, 127, 126, 126, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 126, 126, 126, 127, 127, 127, 127, 126, 126, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 127, 128, 128, 127, 128, 128, 127, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 127, 127, 128, 127, 127, 128, 128, 128, 128, 128, 128, 129, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 128, 127, 128, 128, 127, 128, 128, 128, 128, 128, 128, 128, 127, 128, 128, 127, 128, 128, 128, 128, 128, 128, 128, 128, 128, 127, 128, 128, 127, 128, 127, 127, 128, 126, 127, 128, 126, 128, 127, 126, 131, 128, 124, 131, 128, 125, 132, 127, 124, 131, 129, 126, 129, 127, 126, 128, 127, 127, 128, 128, 128, 128, 129, 127, 126, 129, 126, 126, 129, 126, 126, 129, 127, 126, 129, 128, 128, 128, 127, 128, 128, 127, 128, 129, 128, 128, 129, 128, 129, 129, 127, 127, 128, 127, 127, 128, 127, 127, 127, 127, 129, 127, 125, 129, 130, 125, 127, 130, 126, 126, 129, 128, 125, 126, 128, 127, 126, 127, 128, 127, 128, 128, 127, 127, 127, 126, 127, 126, 127, 129, 127, 128, 129, 126, 127, 128, 126, 128, 127, 127, 131, 127, 127, 130, 126, 128, 129, 124, 129, 127, 124, 129, 124, 123, 131, 125, 124, 131, 127, 127, 129, 126, 130, 126, 125, 134, 128, 124, 132, 129, 128, 130, 124, 127, 130, 124, 123, 127, 128, 128, 126, 126, 125, 127, 131, 127, 125, 128, 127, 125, 127, 130, 125, 126, 134, 128, 124, 135, 128, 120, 133, 132, 126, 129, 126, 129, 131, 126, 131, 127, 124, 134, 127, 124, 132, 124, 125, 133, 126, 125, 129, 131, 132, 122, 127, 133, 123, 135, 136, 118, 132, 136, 120, 133, 133, 119, 135, 133, 121, 133, 128, 122, 131, 126, 123, 128, 124, 127, 127, 122, 133, 131, 119, 132, 135, 119, 127, 136, 123, 124, 135, 130, 125, 129, 131, 129, 125, 124, 132, 128, 119, 128, 133, 121, 123, 133, 128, 121, 122, 131, 129, 119, 129, 135, 117, 127, 138, 117, 121, 136, 125, 129, 131, 120, 127, 130, 126, 129, 126, 128, 128, 124, 128, 124, 129, 135, 120, 127, 132, 116, 134, 131, 114, 141, 130, 112, 140, 123, 115, 142, 124, 127, 136, 115, 136, 134, 107, 138, 138, 114, 134, 131, 120, 132, 127, 128, 132, 123, 126, 129, 126, 128, 127, 127, 126, 127, 130, 127, 127, 126, 130, 130, 117, 131, 137, 113, 132, 140, 113, 135, 138, 111, 133, 133, 117, 138, 125, 117, 143, 128, 120, 138, 122, 124, 140, 123, 122, 134, 124, 128, 131, 119, 130, 132, 120, 131, 129, 120, 132, 127, 124, 133, 120, 125, 133, 119, 130, 132, 114, 129, 134, 118, 126, 131, 123, 125, 129, 130, 126, 127, 130, 123, 130, 134, 123, 128, 133, 125, 129, 131, 122, 129, 134, 123, 127, 134, 125, 131, 134, 119, 129, 134, 120, 133, 128, 116, 134, 127, 126, 136, 115, 130, 143, 115, 131, 138, 116, 133, 129, 121, 136, 123, 127, 137, 120, 131, 133, 124, 140, 128, 122, 136, 121, 127, 138, 119, 126, 130, 119, 133, 132, 117, 124, 132, 125, 121, 132, 131, 119, 130, 134, 121, 128, 131, 125, 127, 126, 129, 129, 123, 132, 131, 121, 134, 136, 122, 123, 128, 131, 127, 127, 132, 121, 121, 137, 127, 120, 135, 131, 123, 132, 129, 122, 132, 130, 121, 132, 135, 118, 125, 140, 129, 122, 128, 129, 129, 128, 131, 128, 122, 131, 129, 119, 131, 131, 122, 131, 126, 123, 137, 127, 120, 135, 129, 119, 133, 133, 121, 131, 133, 116, 128, 139, 118, 122, 136, 122, 125, 135, 128, 122, 125, 132, 124, 122, 143, 125, 112, 143, 125, 110, 139, 127, 120, 137, 127, 127, 127, 125, 139, 124, 123, 137, 114, 128, 144, 111, 126, 143, 117, 127, 133, 118, 132, 134, 122, 126, 129, 128, 124, 127, 133, 123, 125, 137, 123, 120, 135, 128, 119, 132, 131, 120, 129, 133, 123, 125, 127, 126, 129, 126, 127, 129, 125, 130, 126, 122, 128, 127, 128, 129, 126, 131, 130, 126, 127, 127, 132, 128, 123, 135, 126, 121, 137, 126, 123, 136, 127, 127, 126, 122, 130, 123, 126, 134, 124, 129, 127, 124, 137, 120, 121, 139, 118, 127, 141, 119, 130, 133, 119, 131, 126, 127, 135, 118, 131, 133, 115, 136, 130, 117, 140, 127, 118, 135, 125, 126, 129, 125, 134, 123, 126, 139, 118, 125, 139, 116, 128, 139, 119, 125, 132, 128, 131, 124, 129, 132, 122, 130, 133, 123, 128, 127, 127, 133, 125, 125, 133, 125, 123, 131, 130, 124, 125, 130, 130, 125, 126, 127, 125, 128, 129, 129, 125, 122, 130, 130, 124, 128, 128, 126, 128, 128, 128, 124, 124, 133, 125, 124, 136, 121, 123, 138, 120, 123, 138, 121, 125, 140, 123, 120, 131, 130, 127, 126, 129, 129, 122, 131, 134, 122, 123, 132, 131, 125, 127, 130, 126, 127, 130, 124, 129, 130, 126, 133, 131, 125, 130, 129, 128, 128, 126, 132, 128, 123, 133, 126, 122, 133, 126, 124, 134, 129, 127, 128, 126, 129, 125, 123, 130, 126, 126, 129, 126, 129, 130, 126, 128, 128, 125, 128, 131, 128, 124, 127, 129, 125, 128, 131, 127, 127, 131, 130, 125, 128, 133, 126, 123, 129, 128, 127, 128, 125, 127, 129, 127, 127, 128, 129, 127, 128, 132, 124, 122, 135, 131, 122, 128, 129, 126, 129, 131, 126, 124, 132, 130, 120, 127, 132, 122, 127, 132, 124, 123, 127, 128, 126, 124, 128, 129, 125, 129, 128, 126, 130, 126, 126, 132, 125, 127, 133, 124, 127, 133, 123, 126, 133, 123, 125, 130, 125, 124, 128, 131, 128, 122, 130, 130, 121, 133, 133, 121, 128, 131, 127, 131, 127, 127, 131, 125, 129, 130, 124, 128, 128, 125, 129, 125, 125, 131, 127, 126, 129, 127, 127, 128, 129, 128, 125, 128, 131, 126, 125, 130, 129, 125, 128, 132, 126, 125, 131, 128, 125, 128, 128, 127, 126, 127, 126, 126, 129, 127, 124, 129, 130, 129, 129, 126, 128, 133, 129, 128, 129, 128, 128, 129, 127, 125, 126, 127, 125, 126, 127, 125, 126, 127, 127, 127, 126, 130, 130, 124, 129, 132, 126, 129, 132, 126, 128, 131, 128, 126, 127, 129, 127, 126, 128, 125, 126, 129, 126, 123, 125, 129, 129, 124, 128, 131, 124, 127, 133, 127, 128, 131, 128, 127, 131, 131, 126, 127, 132, 127, 124, 129, 126, 123, 128, 126, 123, 125, 125, 126, 126, 125, 128, 126, 126, 132, 128, 125, 131, 131, 129, 130, 130, 128, 129, 130, 130, 126, 126, 129, 127, 127, 130, 126, 124, 127, 128, 124, 126, 129, 128, 127, 130, 129, 128, 130, 130, 129, 130, 129, 126, 129, 130, 126, 126, 128, 127, 126, 127, 125, 123, 126, 127, 127, 126, 126, 128, 127, 126, 128, 129, 128, 127, 129, 129, 126, 125, 129, 127, 126, 128, 126, 124, 127, 128, 126, 125, 127, 127, 125, 129, 130, 123, 124, 132, 129, 125, 127, 128, 126, 128, 131, 127, 125, 129, 130, 129, 129, 125, 127, 131, 129, 126, 125, 126, 128, 129, 127, 126, 125, 127, 129, 127, 127, 127, 126, 128, 130, 127, 126, 128, 129, 128, 127, 128, 128, 127, 128, 129, 127, 126, 128, 127, 127, 127, 128, 128, 127, 128, 128, 126, 127, 129, 125, 126, 129, 128, 126, 126, 128, 128, 126, 129, 129, 124, 128, 130, 126, 127, 128, 126, 130, 130, 128, 127, 127, 130, 130, 127, 129, 128, 125, 129, 129, 125, 125, 126, 127, 128, 128, 127, 126, 128, 130, 128, 129, 129, 128, 130, 131, 129, 127, 128, 128, 127, 129, 127, 124, 128, 129, 126, 126, 126, 125, 127, 128, 127, 125, 126, 129, 127, 127, 129, 126, 127, 130, 129, 128, 126, 126, 129, 128, 128, 128, 126, 128, 129, 128, 129, 125, 125, 131, 129, 126, 126, 127, 128, 128, 129, 128, 124, 127, 133, 130, 126, };
// end of speaker

// heat sensor
float temp;
float tempC = 0;
// float tempF = 0;
int speaker = 11;
// end heat sensor

// base
 const int pingTrigPin = 12; //Trigger connected to PIN 7   
  const int pingEchoPin = 10; //Echo connected yo PIN 8   
  int buz=5; //Buzzer to PIN 4   
// end base

// bluetooth
#define buttonPin 7
int State = 0;
// end bluetooth

void setup()
{
// bluetooth
 Serial.begin(9600);         // Set the baud rate for Bluetooth communication
  pinMode(buttonPin, INPUT);     // Set the button pin as input
// end bluetooth

  // heat sensor
pinMode(A0, INPUT);
pinMode(speaker, OUTPUT);
// end heat sensor

// base 
  pinMode(buz, OUTPUT);   
// end base
}

void loop()
{
// bluetooth
 State = digitalRead(buttonPin);  // Read the state of the button
  Serial.println(State);
  if (State == HIGH) {
    Serial.println("Help Button Pressed! Help Button pressed! Help Button pressed! Help Button pressed!");  // Send a message when the button is pressed
    delay(500);                             // Add a small delay to avoid multiple messages on a single button press
  }
// end bluetooth

  // heat sensor
temp = analogRead(A0);
temp =((temp*5)/1024);
tempC = (temp-0.5)*100.0f;
// tempF = ((tempC9)/5 + 32);
Serial.print("Temperature = ");
Serial.print(tempC);
Serial.println(" C , ");
// Serial.println(tempF);
// Serial.println(" F ");
if (tempC <=22)
{
noTone(speaker);
delay(1000);
}
if (tempC >= 18 && tempC <= 22)
{
noTone(speaker);
delay(1000);
}
if (tempC >43)
{
// tone(7, 1000);
// delay(200);
 digitalWrite(speaker, HIGH);   
  delay(100);   
  digitalWrite(speaker, LOW);  
// end heat sensor

  // speaker
startPlayback(sample, sizeof(sample));
  delay(1000);
  // end speaker
}
// base - possible problem?
 long duration, cm;   
  pinMode(pingTrigPin, OUTPUT);   
  digitalWrite(pingTrigPin, LOW);   
  delayMicroseconds(2);   
  digitalWrite(pingTrigPin, HIGH);   
  delayMicroseconds(5);   
  digitalWrite(pingTrigPin, LOW);   
  pinMode(pingEchoPin, INPUT);   
  duration = pulseIn(pingEchoPin, HIGH);   
  cm = microsecondsToCentimeters(duration);   
  if(cm<=50 && cm>0)   
  {   
  int d= map(cm, 1, 100, 20, 2000);   
  digitalWrite(buz, HIGH);   
  delay(100);   
  digitalWrite(buz, LOW);   
  delay(d);  
  }   
  Serial.print(cm);    
  Serial.print("cm");   
  Serial.println();   
  delay(100); 
}
long microsecondsToCentimeters(long microseconds)   
  {   
  return microseconds / 29 / 2;   
  }   
  // end base
```

# Bill of Materials
<!---
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 
-->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Solid core wires |Used as jumper wires that can be soldered  | $6.90 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Adafruit-Solid-Core-Wire-Spool-ADA290/dp/B00KAE3NTQ/ref=sr_1_7?crid=33IWC40ETHR6A&keywords=solid+core+wire&qid=1689884878&sprefix=solid+core+wire%2Caps%2C339&sr=8-7)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Male-to-male jumper wires | Used to connect compenets without soldering| $5.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Solderless-Multicolored-Electronic-Breadboard-Protoboard/dp/B09FP517VM/ref=sr_1_6?crid=E0TUZAAY2ZVN&keywords=male+to+male+jumper+wire&qid=1689886329&sprefix=male+to+male+jumer+%2Caps%2C253&sr=8-6)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Male-to-female jumper wires | Used to connect compenets without soldering | $5.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Solderless-Multicolored-Electronic-Breadboard-Protoboard/dp/B09FPJM3L9/ref=sr_1_10?keywords=Male-to-female+jumper+wires&qid=1689886505&sr=8-10)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Female-to-female jumper wires | Used to connect compenets without soldering | $5.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Solderless-Multicolored-Electronic-Breadboard-Protoboard/dp/B09FPL5QV8/ref=sr_1_13?crid=2RHAYU3JQXC05&keywords=Female-to-female+jumper+wires&qid=1689886657&sprefix=female-to-female+jumper+wires%2Caps%2C261&sr=8-13)"> Link </a> |
|:--:|:--:|:--:|:--:|
| HC-05 Bluetooth module | Used to enable the button send a help message to the android phone | $7.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Bluetooth-Converter-Wireless-Transceiver-Communication/dp/B08Z3J9Y8T/ref=sr_1_18?crid=15O69JEM1KME8&keywords=HC-05+Bluetooth+module&qid=1689886759&sprefix=hc-05+bluetooth+module+%2Caps%2C199&sr=8-18)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Speaker | the audio component of the project and works with the temperature sensor to tell you when something is too hot | $15.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/MakerHawk-Full-Range-Advertising-Connector-Separating/dp/B07GJ4GH67/ref=sr_1_3?crid=2HCVM2WV4UHVQ&keywords=MakerHawk%2BSpeaker%2B3%2BWatt%2B8%2BOhm&qid=1689887110&s=electronics&sprefix=makerhawk%2Bspeaker%2B3%2Bwatt%2B8%2Bohm%2B%2Celectronics%2C200&sr=1-3&th=1)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Breadboard | the base of everything and allows me to make changes at any point | $8.75 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/BB830-Solderless-Plug-BreadBoard-tie-Points/dp/B0040Z4QN8/ref=sr_1_13?crid=1IQWCQ5K1Z63N&keywords=Breadboard&qid=1689887560&sprefix=breadboard%2Caps%2C648&sr=8-13)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Perf board | used to solder wires on permanently | $2.39 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.schmalztech.com/products/2-x-2-perfboard)"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

<!---

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
