## !!Hafsa's sketch sketch
This is a sketch of a LED that controls the   on/ off and blinking mode of 3 LEDs. It runs a function that will blinks lights, and will blink LED1, 2 & 3 every few seconds from the range of 10 to 30 to simulate different levels within a blender.  the least amount of seconds simulates high speed

# Controlling Arduino from browser

Simple code that works on Arduino Micro, using the Cylon.js library and websockets to control your Arduino board from the browser.


# How it works and what it can do
This program is a way for your browser to communicate with your Arduino board, using buttons on an html page. It's main contribution is to show how LEDs on a board can be triggered, but also how it represents real-life electronic hardware and how you could trigger soe finctons they do or  and control them using nothing but the browser.

## Wiring Arduino board
To use: First, you want to wire your arduino board accordingly, in this example, pin 3, 4 and 5 are used on the Arduino board, which has a led plugged in on each output. 

## Installation

$ npm install

run gord.exe file

run arduino editor, and upload "Standard Firmata" to your arduino board  (sketch under Examples>Firmata>StandardFirmata)

$ gort scan serial ( shows your port the arduino is connected to)

$ gort arduino upload firmata  (/dev/cu.usbmodem1421 is the port I'm using, copy the result from gort scan serial ,  for PC 
what port you got from scan serial to put in here should being with(COM)).

## Using gort on Mac
(For Mac users, please visit http://gort.io/documentation/getting_started/downloads/ to download gort for Mac, and replace the current gort.exe file that currently exists in this folder, or use the one that I included in the /gort for mac/gort.exe)

## Starting it up
$ npm start (starts a live-server at localhost:5000 and starts the 'robot' on the arduino
Go to localhost:5000 and start using. Wire Arduino board accordingly to the pins in the app.js file,

You can now control the arduino board from localhost:5000

