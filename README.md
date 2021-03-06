#Cyber-Camera
<i>by Amir Fefer </i><br> <br>
An open source for home surveillance: <br>
Cyber-Cam turns any webcam into a smart security home surveillance system. <br>
Allow you to watch and record video streaming anywhere from a secured (TLS/SSL & HTTP Basic Auth) web interface. <br>
Cyber Cam includes smart protection, which plays alarm, sends email and smartphone notifications when a suspicious ,<br> activity captured. Based on real time movement, face, full/upper-body detection. <br>

#Features 
* Watch your webcam stream from anywhere
* Active protection with email and smartphone notifications based on movement/face/full/upper body detection
* Recrod a video, or take a snapshot
* Auto sync recorded video to your Dropbox account
* TLS/SSL plus http basic authentication secured
* Responsive Web UI 
* Audio Stream - record yourself.

#Screenshots

Watch simply on the go: <br><br>
![Stream](https://github.com/amirfefer/Cyber-Camera/blob/master/static/stream.png) 
![Stream](https://github.com/amirfefer/Cyber-Camera/blob/master/static/online.png)
![Stream](https://github.com/amirfefer/Cyber-Camera/blob/master/static/cloud.png)

Or from your browser: <br><br>
![Stream](https://github.com/amirfefer/Cyber-Camera/blob/master/static/screenshotDesktop.png?raw=true) <br>
#Installations and Requirements
<b> Windows installer (RC1) is ready for testing! check in release tab </b><br>
Tested on fedora and Windows (7 and 8)  <br>
Download and install python 2.7.9 (32 bit only)
You can use lower 2.7.x  without SSL/TLS support, not recommended!

For a quick installation you can use  [pip](https://pip.pypa.io/en/latest/installing.html) <br>
Install  [Flask](http://flask.pocoo.org/docs/0.10/installation/#installation), there are some dependencies  <br>
Install [flask_httpauth](https://flask-httpauth.readthedocs.org/en/latest/)<br>
Install [numpy 1.9.2](http://sourceforge.net/projects/numpy/files/)<br>
Install [opencv 2.4](https://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.4.11/opencv-2.4.11.exe) (Not tested with opencv3)<br>
Install [pycrypt](https://pypi.python.org/pypi/pycrypto) <br>

It's importent to fill out the conf file, pay attention to the comments.
For TLS/SSL support, make server's certificate and a key (optional),  you can follow up the manual in the conf file. <br>
The user's password must be in sha224, you can use a generator like [this](http://www.miniwebtool.com/sha224-hash-generator/) <br>
To run the server under windows, run cmd and type 'python server.py' <br>

Congratulation! your webcam transformed into a smart security cam. <br>
Don't forget to  port forward, plus you can use ddns service like [noip](http://www.noip.com/free) <br>
If you encounter a bug, or have some suggestions, please  let me know by email or open an issue. <br>

amirfefer@gmail.com

