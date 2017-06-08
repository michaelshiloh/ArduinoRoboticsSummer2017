# ArduinoRoboticsSummer2017
## Arduino Robotics at the California College of the Arts, Summer 2017

[Current homework assignment](#current-homework-assignment)


### Important Information

Title: Arduino Robotics (Science and Math)

This page is
https://github.com/michaelshiloh/ArduinoRoboticsSummer2017

Lecture: Monday Wednesday Friday 1:30 PM - 4:30 PM
* Last class is Wednesday June 28
* No class on Memorial Day Monday May 29
Main building, San Francisco, room 107 (Hybrid Lab)

Instructor: Michael Shiloh
mshiloh@cca.edu
Office hours: By appointment
The Hybrid Lab Summer Hours (TBA)
 
Mon: 
Tues: 
Wed: 
Thurs: 
Fri: 
Sat:

### Syllabus

#### Course Objectives

* Learn about electronics, programming, mechatronics, and robotics
* Satisfy the Science and Math (SCIMA) learning outcomes for a 200 level course 
* Have fun

#### Github and Class Repository
We will be using a cloud service called Github. Our repository is at
https://github.com/michaelshiloh/ArduinoRoboticsSummer2017

The class repository will be used to assign homework and reading
assignments, and will contain useful code, libraries, and links to other
resources. Github allows you to receive email updates when a repository
changes — take advantage of this feature!

You will be required to create your own repository for handing in homework and
for project documentation.

#### Required Textbook
No textbook is required, but there are many good online references and a
few good books out there I can recommend. We also have a good assortment of
books in the library.


#### SCIMA 200 level Learning Outcomes

To be added

#### Grading Rubric

    15% attendance
    15% participation
    20% the things you build for this class
    50% reports

Why so much for the reports? Because that's how you solidify your learning and
show me what you're learning.

The difference between science and fooling around is writing stuff down
(Adam Savage)

#### Rules

* Each of you will be given a kit of parts
* Each of you must bring a laptop (Windows, Linux, or Macintosh). If you
don't have a suitable laptop it is your responsibility to check one out of the
Media Center every day.
* Bring your laptop and the kit to every class
* Participate in class! Ask questions, guess answers, propose topics,
share interesting projects you’ve found, push the envelope, explore your
interests, and teach us all! There are no stupid questions; admitting when
you don’t know something should be a point of pride. Chances are you’re
not the only one with a question, just the bravest one.
* As outlined in the CCA Student Handbook, attendance in class is mandatory
* and three or
more unexcused absences will result in a failing grade.
* Plan to spend 3-12 hours a week on homework. If you don’t have a
solid foundation in math you may need more time. Plan ahead!
* Submit your homework on time.  Write clearly and legibly. Attend class, and
don’t be late. These are not requests, these are requirements.
* You are responsible for checking your email and the class repository
for updates.
* No digital distractions in class. 
	* No phones on the tables. 
	* No instant messaging, email, or working on other projects. 
	* Please disable all notifications on your phone and laptop. 
	* You must be present, engaged, and participating.

#### Access & Wellness Services
CCA says:
> Students with disabilities, including disabilities that are not clearly
> evident like chronic diseases or learning disabilities are encouraged
> to notify their instructor after class or during office hours. CCA will
> make reasonable accommodations for persons with documented
> disabilities. Students should contact Suzanne Raffeld, Director of
> Access and Wellness Services (email: sraffeld@cca.edu; phone:
> 510.594.3775), to answer any questions or for assistance. For more
> information, consult CCA's webpage at: http://www.cca.edu/
> students/resources/disability.

I want you to succeed in this class. Please make use of the Hybrid Lab
coaches, the Learning Resource Center, and talk to me if you feel you are
struggling with the material — I can help you do better in this class, but
only if you let me know you need help.

#### Class Format
Sessions will be a mix of lectures, guided labs, and independent work time.
Homework will require research, analysis, and experimentation.
Engineering always takes more time than you think — please make sure to
give yourself enough time!


#### Prerequisites

- High school math and algebra
- High school English writing skills (grammar, spelling, sentence
construction, etc.)
- Critical Thinking (knowing the difference between an opinion and a fact)

####  Optional equipment

As you develop your projects and interests, you might need to purchase
additional components and devices. This is impossible to predict as the range
of projects you might approach are indeed infinite. At the low end, you can
build amazing projects from discarded electronic devices such as printers at
absolutely no cost; at the high end there is no limit; a complicated project
could easily start at hundreds of dollars. Some lessons I've learned:

* Projects will cost more than you think
* Projects will take MUCH MUCH longer than you think
* Things that you think should be easy will be hard
* You will order parts that are wrong or that you simply decide not to use.
Be ready to accept this. Consider these items you might trade with other
students (or the larger maker community) for parts that you do need,
especially when you need that part urgently.
 * You will spend less time and money if you are flexible about your concept.
Allow prototype iterations to modify your concept, not just your execution.
The reverse is also true: If you strongly want to stick to your concept, be
prepared to spend more time and money. The common way of looking at this is to
consider that there is a relationship between time, money, and features. You
can choose any two of them, and the third will grow (or shrink) to
accommodate.


#### Topics, not in chronological order

* Git and github
* Electronics
  * The difference and relationship between voltage and current
  * Digital Multimeter
  * Schematics, and understanding the Arduino schematic
  * Sensors
  * Radios
* Arduino
  * Introduction
  * Arduino inputs: measure voltage. must convert anything to voltage.
resistance doesn't count. voltage dividers, pull ups, and pull downs
  * Output: Transistors, H-bridge
  * Other than Arduino
* Programming
  * Conditionals
  * Complex interactions
  * Data types
  * Arrays and for() loops
  * Functions
* Construction techniques
  * Prototyping shield
  * PCB
* Robotics
  * Autonomy
  * Making decisions
  * Noisy data and filters 
  * Thresholds
  * Self calibration

### Schedule

The schedule is subject to change

### Monday May 22

- Introductions
- Interests and goals
- Hands-on activity
  - Basic Arduino
    [tutorial](http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop)
- Resources: See the Arduino resources
  [here](https://github.com/michaelshiloh/resourcesForClasses)

**Homework due Wednesday May 24**
- Memorial Day: We **do** have class this Friday, May 26. 
	We do **not** have class on Monday May 29.
- Review the Basic Arduino
  [tutorial](http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop)
  we did in class. Read the entire document. Don't worry about understanding
	it all.
  - Do the section titled [how to use a sensor](http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop#How_to_use_a_sensor)
  - do the section titled [analog write(): Controlling speed or brightness](http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop#analogWrite_Controlling_speed_or_brightness)
  - Optional: Can you figure out how to connect two LEDs to your Arduino and how
	to make them blink? Copy your code into your *README.md* file.
- Create your Github account and a class repository following
[this guide](https://github.com/zamfi/github-guide). **Important!** Make sure
to check the box that says "Initialize this repository with a README".
Your account name should be your name (unless for privacy reasons you'd prefer 
something else) and your repository name should be the class name. When you
are done, email me the URL to your repository.

### Wednesday May 24

* Homework review
	* Github
	[Resources](https://github.com/michaelshiloh/resourcesForClasses#github-resources)
	* [AnalogReadSerial](http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop#How_to_use_a_sensor)
	* [Fade](http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop#analogWrite_Controlling_speed_or_brightness)

* Lecture
	* Motors, specifically brushed DC motors (also called DC motors)

* Soldering Demonstration: Soldering wires to motors
	* Use _stranded_ wires at least 12", any colors except red or black
	* Hot glue strain relief
	* Test with a 9V battery
	* Attach a short piece of solid core wire
	* Insulate with heat shrink tubing
	* Test again

* Homework due Friday May 26

  * Read the soldering tutorial
		[here](https://github.com/michaelshiloh/resourcesForClasses#soldering)
  * Read _all_ the motor tutorials
		[here](https://github.com/michaelshiloh/resourcesForClasses#motors)
  * Read and do the Arduino [AnalogInput tutorial](https://www.arduino.cc/en/Tutorial/AnalogInput). Use your LDR
		and not a potentiometer. Make notes in your "journal" (your README.md
		file) of any interesting things you discover or any problems that you run
		into. 
  * Modify the program so that it also prints the values of
	  _sensorValue_. I showed you this in class. You might also refer to the
		_println_ [tutorial](https://www.arduino.cc/en/Serial/Println).
		Make note of the approximate range of values you get,
		between covering up the light sensor (dark) and uncovering the light
		sensor (light). 
		Make notes in your README.md file and upload your program.
		Remember to use the .ino file extension.
  * Modify the program so that instead of blinking, the LED turns on when the
	  light level is above some threshold (say 500), and turns off when the
	  light level is below that threshold. Chose a threshold that is appropriate
		to the range of light levels that you get.
		You might want to refer to the [if() statement
		tutorial](https://www.arduino.cc/en/Tutorial/ifStatementConditional).
		Make notes in your README.md file and upload your program. 
		Remember to use the .ino file extension.
  * Modify the program so that the LED turns on when the
	  light level is above some threshold (say 700), turns off when the
	  light level is below a different threshold (say 300), and blinks if the
		light level is between those two thresholds. Again, choose appropriate
		thresholds.
		Make notes in your README.md file and upload your program.
		Remember to use the .ino file extension.

### Friday May 26

* H-bridge concept
  * Caution about external power!
  * H-bridge [tutorial](http://teachmetomake.com/wordpress/arduino-tutorial-h-bridge)

**Announcements**
* No class on Monday, and Hybrid Lab is closed
* After Monday, Hybrid Lab is open weekdays 9am - 5pm. 
* There are no weekend hours yet
* Although there is a class from 9-1,
  you may work in the lab if you don't disturb.
* If you reply to any of my emails, please change the subject line if you are
  changing the subject.

**Homework due Wednesday**
1. Contrary to what I said in class, I *do* want you to solder wires to 
   your new motor(s), as demonstrated in class. You have time on Tuesday or
   Wednesday. 
1. Build some sort of robot or vehicle or other mechanized device that uses these two motors
1. **Examples:**
  * [Jeffrey Stone](https://www.youtube.com/watch?v=xQlpFIsD2WA)
  * [Shiyu Zhang](https://raw.githubusercontent.com/Raineshiyuzhang/Raine-Shiyu-Zhang-/master/finalProject/video.mp4)
  * [Siyu Zhang](https://raw.githubusercontent.com/sirryzhang/Siyu-Zhang/master/TapTap%20robot/taptap%20robot%20video.mp4)
  * [Benner Boswell](https://github.com/bennerboswell/week3-homework-/blob/master/vehicle/IMG_7490.MOV)
1. **Details:**
  * Leave room for your Arduino, solderless breadboard, and battery packs
  * The project doesn't have to be beautiful or creative. The goal is to
	have a platform to explore next week.
  * Don't worry about programming. We will do that in class.
4. Do the last exercise from the homework assigned last Wednesday

### Wednesday May 31
Homework review
* Soldered wires on motor
* Vehicles
* Last exercise from last Wednesday

Lecture
* Programming
	* Conditionals
		* if() - else - else if()
	* Loops
		* While()
		* For()
	* Reminder: Variables can be programmatic (counts, etc.) or sensor influenced
* Electronics
	* How to power Arduino and motors

**Announcements**
* Please clean up after yourselves! All sorts of trash was left behind after
  class.
* I have to leave every Wednesday at 4:30pm sharp. I am available 
	before or after class on other days or by appointment
* Please note that in
  [this](http://teachmetomake.com/wordpress/wp-content/uploads/2015/01/l293d_schem.png) 
  diagram I use Arduino pins 2, 4, and 6 to control the H-bridge, but in
  [this](http://teachmetomake.com/wordpress/wp-content/uploads/2015/02/l293d_5V_twoMotors_schem.png)
  diagram I use Arduino pins 2, 3, 4, 6, 7, and 12. Both are correct, but you 
  will have to change your program to use the proper pins.
	
**Homework due Friday**
1. Program your contraption to perform a simple sequence of activity
2. Add a pushbutton, so that your contraption only performs its activity if
	the button is pressed. Once the button is pressed, your contraption must
	complete its activity, and then it goes back to waiting for the next button
	press.
	* Document your assignment on Github with the following:
		* Picture(s)
		* Short video
		* Program, with comments describing what's going on
3. Modify your program from step 2 above so that once the button is pressed,
  your contraption performs its activity forever (until you unplug it).
	* Document your assignment on Github with the following:
		* Program, with comments describing what's going on, especially what
   makes it continue forever

### Friday June 3

Homework review

Testing
* Testing motor without H-bridge
* Testing H-bridge without Arduino
* Testing program without H-bridge
	* Multimeter
* Serial.print() and Serial.println()

Distance Measuring Sensor

```
/*
HC-SR04 
 
Circuit:
  VCC to arduino 5v 
  GND to arduino GND
  Echo to Arduino pin 11 
  Trig to Arduino pin 12
 
Based on code from
http://www.instructables.com/id/Simple-Arduino-and-HC-SR04-Example/step3/Upload-the-sketch/
*/

const int trigPin = 12;
const int echoPin = 11;

void setup() {
  Serial.begin (9600);
  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);
}

void loop() {
  long duration, distance;
 
  // Drive trigger pin LOW, HIGH, LOW to send the pulse
  digitalWrite(trigPin, LOW); 
  delayMicroseconds(2); // low for 2 microseconds
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10); // high for 10 microseconds
  digitalWrite(trigPin, LOW);

  // the pulseIn command waits for a given pin to go HIGH, and then 
  // reports how long it waited until that happened
  duration = pulseIn(echoPin, HIGH); // measure the time to the echo

  // Convert to centimeters
  distance = (duration/2) / 29.1;  // calculate the distance in cm

  // Discard readings that are too large or too small to be reasonable
  // It's pretty common for some sensors to give occasional bad readings
  // and a good program must take that into account
  if (distance >= 200 || distance <= 0){
    Serial.println("Out of range; reading invalid");
  } else {
    // anything left should be a valid distance
    Serial.print(distance);
    Serial.println(" cm");
  }

  delay(500);    // wait before doing it again
}
```

Programming
* int and long variables, and the const modifier
* Serial.print() and Serial.println()
	* Useful for debugging as well
* Functions
	* Arguments (none, one, or more) 
	* Return value (none or one)

Electronics
* Servo motor

Homework 
* Read the three resources about functions
	[here](https://github.com/michaelshiloh/resourcesForClasses#functions)
* Add the distance measuring sensor to your robot, and write a
  program to help your robot avoid obstacles. 
	Document as before (picture, video, code with excellent comments). 
	Also describe (in README.md or another .md file) any
	difficulties you encountered and how you overcame them, and anything 
	interesting you discovered.
* Advanced challenge: 
	* Mount the distance measuring sensor on the servo motor. Use some sort of
    extension to the pins, do not solder wires to the pins
	* Write a program to make your robot go in the direction where there
		 is the most space.
  * Document as before (picture, video, code with excellent comments,
		and discussion (in README.md or other .md file)). 
* As a treat, here is an example of what you can do with two [servo
  motors](https://youtu.be/pi7GvRE-ivU) (and a Theremin)

### Monday June 6

Demo
* An extension for your distance measuring sensor
* Adding a light sensor to your robot
* Prototyping shield

Lecture
* Functions
* Arrays 
* Advanced conditionals: how to make use of multiple sensors
* Fritzing schematics

Homework

1. Organize your robot code to use functions, as I started to do in class.
Your functions should perform the basic capabilities of your robot (or
whichever ones you use: `goForward()`, `goBackwards()`, `turnRight()`,
`stopMoving()`, etc. 
Place your file(s) in Github.

2. This exercise is to develop your skill using servo motors. Use two light
sensors pointing in different directions. Write a program so that your servo
motor points in the direction that has more light. When the light level is
equal, the servo motor should point in the middle. 
Place your file(s) in Github.

Advanced challenge: The
servo motor points to the middle when the difference between the two light
levels is less than 15.

3. Start thinking about the final machine you would like to build for this
class. You will present your ideas informally on Friday. Make a folder in
your Github account called "FinalProject" and put any description, sketches,
research, etc. in there.

### Wednesday June 8
Homework questions

Software Lecture
* Functions that take arguments

Hardware Lecture
* Volts, Ohms, and Amps
* Ideal wires

Demo
* Fritzing schematics
* Fritzing PCB layout

###current-homework-assignment
Homework 
1. Write a function that takes three integer arguments and returns their
average. Write a program that uses this function. Review the function
resources if necessary.

2. Read all of the resources on
  [arrays](https://github.com/michaelshiloh/resourcesForClasses#arrays)

3. Use fritzing to create a schematic showing two light sensors and a servo
	motor. I am only interested in the schematic view, you do not need to do the
	breadboard or the PCB views. Upload an image to Github.

4. Write a short description of your final project proposal. If you have no
ideas don't do this exercise and instead make an appointment to talk to me.


### Friday June 10
Hardware Lecture
* Ideal wires
* Series and Parallel

Software Lecture
* Functions that take arguments
* Arrays 
* For() loops
*	Filtering noisy sensor data in software

Demo
* Soldering wires and components to PCB
* Othermill for double sided PCBs
* Blink without Delay
* Ultrasonic distance measuring sensor on a servo motor
* Using array for scanned data
* Classes and objects

Homework 
* Soldering wires and components to PCB practice
### Monday June 13

* Using functions and classes to better organize programs

### Wednesday June 15

Announcements
* I have to leave every Wednesday at 4:30pm sharp. 

*	Wireless (Bluetooth, Xbee, WiFi, other)

### Friday June 17
*	Processing

### Monday June 20
* Advanced debugging

### Wednesday June 22
*	Multitasking


### Friday June 24
* Advanced Robotic Concepts
* Work time
	
### Monday June 27
* Work time

### Wednesday June 29
* Final project critiques

Student accounts:

* [Abdullah Balkhyour](https://github.com/Abalkhyour/ArdiunoRobotics)
* [Sabine Belofsky](https://github.com/sbelofsky/arduinoroboticssummer2017)
* [Nino Panes](https://github.com/senaponin/ArduinoRobotics)
* [Aaron Mckenzie](https://github.com/aaronmckenzie/Mechatronics-Summer-2017)
* [Audreen](https://github.com/audreen/Arduino_Robotics_S2017)
* [Omar Ansari](https://github.com/ansariomar/HW-1)
* [Emily Cunningham](https://github.com/ecunningham4/Arduino-Robotics)
* [Sergio Burgos](https://github.com/sergio-burgos/ArduinoRoboticsSummer2017)
* [Yanru Yin(
  Melissa)](https://github.com/melissa1126/ArduinoRoboticsSummer2017)
* [Michelle Herrera](https://github.com/emilypostpunk)
* [Andrew Kim](https://github.com/Kimhangi)
* [Mamdouh Khogeer](https://github.com/MamdouhKhogeer/ArduinoRobotics)
