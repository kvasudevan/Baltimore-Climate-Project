# Baltimore-Climate-Project

Open the files in the Arduino IDE desktop app (https://www.arduino.cc/) 
Hit the check mark on the top left of the window to make sure the software compiles properly (if it doesn't load up, you most likely will have to install the libraries which are listed within the code)
Once you've loaded up the proper libraries, the only change we need to make is in the top section //Variables 
You will change the line String unit_id = "BCXX" to match the sensor number you are working on. So if your sensor number (listed on the bag and also on the back of the DHT22 temperature sensor is 9, change the code to read String unit_id = "BC09"
