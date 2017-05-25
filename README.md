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

#### current homework assignment
* Homework due Friday May 26

  * Read the soldering tutorial
		[here](https://github.com/michaelshiloh/resourcesForClasses#soldering)
  * Read _all_ the motor tutorials
		[here](https://github.com/michaelshiloh/resourcesForClasses#motors)
  * Read and do the Arduino [AnalogInput
	  tutorial](https://www.arduino.cc/en/Tutorial/AnalogInput). Use your LDR
		and not a potentiometer. Make notes in your "journal" (your README.md
		file) of any interesting things you discover or any problems that you run
		into. 
  * Modify the program so that it also prints the values of
	  _sensorValue_. I showed you this in class. You might also refer to the
		_println_ [tutorial](https://www.arduino.cc/en/Serial/Println).
		Make note of the approximate range of values you get,
		between covering up the the light sensor (dark) and uncovering the light
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
  * H-bridge tutorial

* Homework due Wednesday
  * Solder wires to motors to both of your motors, as demonstrated in class

### Wednesday May 31

* Conditionals
* Review analog and digital inputs and outputs
* Test equipment

### Friday June 3

* How to power Arduino and motors
* Electrical noise and how to reduce it
*	Filtering noisy sensor data in software
* Functions

### Monday June 6

* Fritzing schematics
* Adding sensors: Light, distance
* Advanced conditionals: how to make use of multiple sensors
* Function arguments and return values

### Wednesday June 8

* Arrays 
* For() loops
* Classes and objects

### Friday June 10

* Ultrasonic distance measuring sensor on a servo motor
* Using array for scanned data
* Fritzing PCB

### Monday June 13

* Othermill for double sided PCBs
* Using functions and classes to better organize programs

### Wednesday June 15

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
