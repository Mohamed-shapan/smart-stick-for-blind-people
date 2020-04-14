# smart-stick-for-blind-people
smart stick for blind people
smart stick for blind people:
   Description
•	Main aim of project was to create a stick for blind so that it is affordable and at the same time reliable


•	A smart stick basically detects the obstacles around it in 3 directions (right, left and front) and users are notfied using the android App.


•	The smart stick uses 3 ultrasonic sensors and arduino to detect obstacles around it.


•	The Android app takes the data from the stick and provides feedback to the user in the form of voice output.
•	Since, blind people find difficult to operate the app, the app launches automatically as soon as it is connected to the smart stick
•	There is a Navigation feature wherein the user has to say the destination by voice and GPS will start automatically (The current location will be detected automatically).
•	In order to consider the emergency, and for proper navigation amongst the app, gestures are used. The user draws some gestures lik (^) or (v) or / on the screen and appropriate person will be notified about the situation
•	The gestures are editable and people phone numbers can be set

•	component
•	An Arduino Uno.
•	An Ultrasonic sensor( HCSR04 ).
•	A Mini breadboard.
•	A 9-volt battery.
•	A 9-volt battery connector.
•	DC male power jack.
•	A Buzzer.
•	Some Jumper wire.
•	A Broken cell phone from scratch.
•	A Toggle switch.
Other tools and parts used in this project:
•	PVC pipe (used for making the stick).
•	PVC elbow.
•	Insulation tape.
•	Some small screws for mounting Arduino.
•	Screwdriver.
•	Utility knife.
•	Instant adhesive Glue.
•	A Box to Put your Arduino and other electronics, or think about it later.
                            steps                                                                   First, we need the vibrator motor. Find a broken cell phone.
Do this step with care and patients.
I used a micro vibrator motor from an old broken cellphone that lying around my home. The reason for i used this, it is very small in size and almost works with low voltage.
Unscrew the cell phone and disassemble all the parts like shown in the above images. you can see the vibrator motor placed a side of the phone's case . Take out the motor carefully from the cell phone.
Please note: different cellphones have different vibrator motor (in size and shape).
Now solder the motor on a small piece of general purpose PCB, Then solder two wire to the terminals of the motor like shown in the above images.
now we got the vibrator motor.
Now it is time for wiring the Arduino!
See the above schematics and carefully connect all parts to the Arduino.
I used a mini breadboard to connect the ultrasonic sensor to the Arduino using jumper wires.
The other parts like buzzer and motor is directly connected to the Arduino.
It is pretty easy does not have complicated wiring.
You can see the wiring diagram from the above image. here i will explain by parts:
•	Ultrasonic VCC to Arduino 5v.
•	Ultrasonic GND to Arduino GND.
•	Ultrasonic TRIG to Arduino D12.
•	Ultrasonic ECHO to Arduino D11.
•	Buzzer RED to Arduino D8.
•	Buzzer BLACK to Arduino GND.
•	Vibrator motor pin 1 to Arduino D7.
•	Vibrator motor pin 2 to Arduino GND
•	9-volt battery RED to Toggle switch pin 1.
•	9-volt battery BLACK to DC male power jack(-).
•	Toggle switch pin 2 to DC male power jack (+).
Take a look the above images to make the stick.
I used a 3/4 inch diameter PVC pipe and an 'L' shaped elbow for making the stick.
I will describe you in the word to make one:
•	First take a PVC pipe( 3/4 inch diameter), then cut a piece of one and a half meter.
•	Take an 'L' shaped elbow and attach it one of the ends of the pipe.
•	Take another small piece of PVC pipe (10 cm long), then attach it the other end of the elbow.
•	simply glue it.
I'm wrapped the stick with a black insulation tape. No specific reason for that i like black color :)
Now its time for fixing everything on the stick.
This is the hardest step in this project. It took me hours to design and fix the parts onto the stick.
Find a box yourself that we can use to put all our electronics together. I used foam board to make a box myself.
You can also simply do that(i think you don't need an explanation for that).
Fix your Arduino in the box, use screws for a strong fixing . Give two holes for fixing Ultrasonic sensor on the closing lid of the box as shown in the above image. I fixed the buzzer outside of the box for a clear sound also fixed the toggle switch a side of the box and a small hole for connecting vibrating motor to Arduino. Fix the battery inside of the box and connect the power jack to the Arduino.
Mount the Ultrasonic sensor on the closing lid of the box. Fix the buzzer on the top of the box.
take out the vibrator motor to the outside of the box (we need to fix it on the stick's hand)
Now Attach the box to the stick. you can either use screw or glue. Here i used an instant adhesive glue because it is very strong.
After attaching the box to the stick take out the vibrator motor and fix it below the elbow. i used insulation tapes to fix the motor
