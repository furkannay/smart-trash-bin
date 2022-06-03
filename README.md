### SMART TRASH BIN

# MATERIALS
*  arduino uno
*  servo motor
*  Ultrasonic Sensor
* power source
* jumpers




The ultrasonic sensor has four pins, the first one is the GND pin, the second is the echo pin, we will read the reflection signal from it. Then we have the trig pin which we’ll use to transmit the ultrasonic wave and the last pin is Vcc which is used to provide 5V to power the sensor.Plug the sensor into your breadboard and then use the jumpers to connect the GND pin to 0V/GND and the Vcc pin to 5V. Make sure that you plug in leads from the Arduino to your 0V and 5V tracks as well.
Next connect the Trig pin to the Arduino digital pin 9 and the Echo pin to the Arduino digital pin 8.

<img src="https://user-images.githubusercontent.com/74255322/171907443-ae14a6bd-d142-46f3-b444-bb5f102c9820.png">

The servo motor has a female connector with three pins. The darkest or even black one is usually the ground. Connect this to the Arduino GND.
Connect the power cable that in all standards should be red to 5V on the Arduino.
Connect the remaining line on the servo connector to a digital pin on the Arduino.


<img src="https://user-images.githubusercontent.com/74255322/171907199-27274c29-f77d-424e-b703-7e6a33014b5e.jpg">

let's upload our code to arduino.We can add a support rod or wire to the motor to open the lid of the bin by taking advantage of the movement of our motor.
Our system is ready. Let's mount the system in our bin and connect it to the power source and it's ready.


result video=== https://youtube.com/shorts/YsTRrHtIU_E?feature=share
