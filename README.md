This procedures allows me to have multiple Arduino IDE 1.8.8 running on my Mac OSX High Sierra and configured as "portable".
Create a new folder (such as "Arduino_ESP32") where you want to have your Arduino
- download Arduino IDE 1.8.8
- show Arduino.app content
- copy "Content" into the Arduino folder
- create an empty "portable" folder under Contents/Java
- do "show information" on Contents/MacOS/Arduino and drag an icns file on the icon to change it
- rename Contents/MacOS/Arduino to a dedicated name (such as Arduino_ESP32")
- make an alias and copy it into "Application" folder
