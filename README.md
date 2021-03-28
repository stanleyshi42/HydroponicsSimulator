# HydroponicsSimulator
TuffyHacks 2021 Project

https://tuffyhacks.com/
https://www.notion.so/TuffyHacks-Hacker-Camper-Guide-b6d48f4c0ccb40d0b3a32aef02cc51eb

## Inspiration
I took an introduction to environmental science course several years ago and was quite interested in the variety of material it covered. One particular topic that stuck with me was hydroponics, which is a modern form of agriculture. 

Hydroponics produces crops in an indoor, climate-controlled building and does not use any dirt. There are many variants of hydroponics, but generally speaking crops are suspended over a tank of nutrient-rich water that is usually monitored by a computer system. The system tracks the amount of nutrients in the water and adds nutrients when needed. 

Hydroponics brings many benefits over traditional farming. It allows crops to grow in climates that are not suitable for crops. This will likely be a huge thing in the future due to the threat of climate change. It is also space efficient since hydroponic systems can be stacked vertically, while traditional farmland has to be horizontal. Lastly, hydroponics produce higher crop yields due to optimal nutrients, light, and temperature

A friend and I briefly talked about creating a small-scale hydroponics system, but we got around to starting it. When faced with thinking of a project for this hackathon, the hydroponics idea came to mind and I ended up making this project.

While I initially had the idea of making a hydroponics simulation, as production went on it slowly became more like a game kinda similar to Cookie Clicker, if anyone remembers what that is. There is a lot of clicking involved and you can buy a couple upgrades.

## What it does
The Hydroponics Simulator is an application that performs a very simple simulation of a hydroponics system. Honestly, its less of a simulation and more of a visualization of the concept. In any case, I hope this program can bring awareness and interest to hydroponics.

The user is able to plant crops and add nutrients to the water. The plants will consume nutrients to grow and can be harvested for money when they have fully matured. Money can be used to plant more crops and to buy some upgrades.

## How we built it
This program was built using Java and the NetBeans IDE GUI Builder. 

## Challenges we ran into
This was my first time making a project with the GUI Builder in Netbeans, which resulted in spending time on learning how to use it. The Builder is rather straightforward, however, and no major challenges were met with it. 

One significant challenge I ran into was making a way to call a function once every second in order to make the crop grow. The first thing I tried was importing the Timer object and Googling how to implement it, but kept on running into errors. I eventually gave up and tried using an infinite loop that waited 1 second at the end of every iteration, but it seems this caused the program to stay stuck in this loop. I would probably need to use multiple threads to have this method work. After that, I tried the Timer object again and found that there are two Timer packages, java.util.Timer and javax.swing.Timer. It seems that Googling "java timer" returned help for both packages and interfered with my implementation. I imported the other Timer object and finally got it to work.

## Accomplishments that we're proud of
I don't think there were any major accomplishments this project made, but I am proud of a couple things. I'm proud of learning how to use the GUI Builder and happy that I could apply something that I've learned. I'm also proud of managing to push through all the big and small challenges I encountered and sticking through a long day of programming. Lastly, I'm proud of deciding to attend my first hackathon! I haven't done anything extracurricular yet and am glad I got to experience TuffyHacks.

## What we learned
I learned quite a bit on using Netbean's GUI Builder! I've only used it briefly when my professor introduced it to us in class so I'm glad that I got a chance to make a project with it. 

I also learned that there's two Timer packages apparently. I'll definitely look more closely at the packages I'm importing in the future!

## What's next for Hydroponics Simulator
The backend for this program makes scaling up the project pretty difficult so I don't think I'll be adding much more to this project, but I'll definitely  use the knowledge I gained in the future. And not just the programming knowledge, trying to create a hydroponics simulation helped me learn a bit more about hydroponics and the things I need to consider when making a simulation of one. Maybe I'll try making a more authentic hydroponics simulation next time?
