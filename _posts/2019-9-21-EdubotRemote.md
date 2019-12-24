---
layout: post
title: Basic Robotics with Xamarin.Forms
published: true
---
In this tutorial, I will discuss about integrating Xamarin.Forms to Edubot. 

If you're interested in IoT (Internet of Things), this is the article for you.

## What is Edubot?
It's a Mobile Robot created for Kto12 Learners

Basic programmable mobile robot for young (and not so young) learners. Graphical programming style is used to program the robot - programming is done by assembling together a set of blocks, very much like playing on a jigsaw puzzle.

![an image alt text]({{ site.baseurl }}/images/01/edubot.jpg "Edubot")

[E-Gizmo Edubot Link](https://www.e-gizmo.net/oc/index.php?route=product/product&product_id=1404).

## How to Start?
### 1. Download the Arduino IDE and the ArduBlock tool
[Download Arduino IDE](https://www.e-gizmo.net/oc/kits%20documents/ARDUINO%20IDE%20SOFTWARES/arduino-1.8.10%20-windows%20.exe).

[Download ArduBlock Tool](https://www.e-gizmo.net/oc/kits%20documents/Kto12BOT/ardublock%20-%20031319.zip).

### 2. Install Arduino IDE
* After downloading the Arduino IDE, install it on your desired location
![an image alt text]({{ site.baseurl }}/images/01/installarduino.png "Arduino IDE")

* Go to Arduino IDE Installation Path

* Extract the ArduBlock jar file and place it in tools folder
![an image alt text]({{ site.baseurl }}/images/01/ardublockpath.png "ArduBlock")

### 3. Open Arduio IDE and Set the Board and COM Port
* Connect the Edubot to your PC

![an image alt text]({{ site.baseurl }}/images/01/connecttopc.png "Board")

* Set Board to Gizduino (mini) w/ ATmega168

![an image alt text]({{ site.baseurl }}/images/01/board.png "Board")

* Set COM Port

![an image alt text]({{ site.baseurl }}/images/01/comport.png "Port")


### Open ArduBlock
* Tools > ArduBlock

![an image alt text]({{ site.baseurl }}/images/01/ardublock.png "ArduBlock Tool")

* Create your first Edubot Program

![an image alt text]({{ site.baseurl }}/images/01/sampleblocks.png "Sample")

* Drag and drop the components and follow the program below

![an image alt text]({{ site.baseurl }}/images/01/firstprogram.png "First Program")

* Click Upload to Arduino

![an image alt text]({{ site.baseurl }}/images/01/clickupload.png "Upload")

## You have created your first Edubot Program!


## Now let's work on the most exciting part.

## Connect your Edubot with Xamarin.Forms Application (to be updated)
* Download the Xamarin.Forms Application below
[EdubotRemote Github Repository](https://github.com/xambuddy/EdubotRemote)

* Open EdubotRemote.sln

![an image alt text]({{ site.baseurl }}/images/01/opensolution.png)

* Connect your Android Device and run the application

* Make sure bluetooth is turned on when you run the application

![an image alt text]({{ site.baseurl }}/images/01/connect.jpg)

* Open ArduBlock Tool and Open EdubotDuino.abp

![an image alt text]({{ site.baseurl }}/images/01/edubotduino.png)

![an image alt text]({{ site.baseurl }}/images/01/edubotduinoss.png)

* Upload it to your Edubot

## And now you have it! Play now with your Edubot using your Android/iOS device

<iframe width="420" height="315" src="https://youtu.be/RDYw5fX_Zmo" frameborder="0" allowfullscreen></iframe>