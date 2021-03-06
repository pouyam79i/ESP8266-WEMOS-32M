# NodeMCU:
### ESP8266 WEMOS 32M

<p>
<h3>Introduction</h3>  
Well, lets say this model is one of NodeMCUs and it is pretty good for IoT things and project.<br>
This model can be kind of hard to figure out how to set it up and updload your code on it.<br>
For me, as I am a lover of these kind MCUs board and IoT things, it took me to find clibs in russian 
to figure how to deal with it :))))<br>
well lets get down and see how to do the job.<br>
</p>
<br>

## Things you need
<p>
1 - ESP8266 WEMOS 32M <br>
2 - micro usb cable <br>
4 - Arduino IDE installed on your PC <br>
3 - a smart phone with blynk app installed on it <br>
</p>

## 1 - Setup things on Arduino IDE
<p>
Well first of all we need to install NodeMCU libs on Arduino IDE. <br>
To do that, you must open Arduino IDE then go to:<br>
File | Prefrences <br>
Then copy the link below in side a bar with the title of "Additional Board Manager URLs:"<br>
copy this link in it: "http://arduino.esp8266.com/stable/package_esp8266com_index.json" <br>
In this case you can download the NodeMCU boards libs for Arduino IDE :) <br>
To do this go to:  <br>
  Tools | Boards | Boards Manager <br>
And easily search NodeMCU or ESP8266 and Install it.
</p>

## 2 - Uploading Code on boards
<p>
Well you better go and search how to use blynk with you self :)))))<br>
But still the most <span style="color:rgb(125, 82, 150)">improtant</span> part remains. :) <br>
What configs does this board have? <br>
Before compiling and uploading your code you must do a few things here: <br>
1 - you must set the board type at this:<br>
  Tools | Boards | ESP8622 Boards | NodeMCU 1.0 (ESP 12E Module) <br>
2 - your main configs:<br>
  builtin led: 2<br>
  Upload speed: 115200 <br>
  CPU Frequency: 80MHz<br>
  Flash size: 4MB (FS:2MB OTA:~1019KB) <br>
3 - make sure you have installed the Board driver<br>
  it is ch340g driver <br>
  easily download it from internet <br>
  after the set the port to that and then upload your code <br>
 4 - DONE!
</p>
<br>
<br>

Well I don't think this was hard but can be hard if you don't what is what :)<br>
I also uploaded a few picture to make sure that you will do it :)<br>
Plus there is my code as well<br>

### Good lock
### Written by Pouya Mohammai
