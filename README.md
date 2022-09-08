# Control-Arduino-ESP32-by-WebSerial
Control Arduino ESP32 by WebSerial using speech to text

To be able to control and communicate with the Arduino, should use the serial port, and to use the serial port in a website, should use the Web [Serial API](https://web.dev/serial/) 

**Note**: recommend to use **Google Chrome** browser to be able to use **Web Serial API**

1. Connect a servo to pin 9 in Arduino, similar to the circuit below

![Ciucit](https://user-images.githubusercontent.com/90250848/189132104-a8715993-9123-48fe-90b8-a3856d7e8b26.png)

2. Connect the Arduino to your computer and use the file "SpeechCommand.ino", then upload the code

3.  Use the html and css files, the page should look like this

![Capture0](https://user-images.githubusercontent.com/90250848/189132805-12177f28-4910-4b48-a954-b4ff66ab7b4f.PNG)

4. Click **Connect to Serial** button to connect to Arduino, then change the language by pressing the button language

![Capture](https://user-images.githubusercontent.com/90250848/189133980-72aed8aa-ed4b-492a-a256-22f98285da3e.PNG)

**Note**: Port number is different from computer to computer, in my computer it is COM3, it may be different in your computer

5. Allow the browser to use your microphone, then try to say "Right" or "Left", or in Arabic you can say "يمين" or "يسار" 
if you say "Right" or "يمين" the servo should turn right, same thing if you say "Left" or "يسار" the servo should turn left 
