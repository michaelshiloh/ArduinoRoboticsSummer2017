# ArduinoRoboticsSummer2017
## Arduino Robotics at the California College of the Arts, Summer 2017

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
The Hybrid Lab Summer Hours TBA, but hopefully:
 
Mon: 8am - 3pm (classes in session from 9am - 4:30pm) 
Tues: 8am - 5pm (classes in session from 9am - 1pm) 
Wed: 12pm - 7pm (classes in session from 9am - 4:30pm) 
Thurs: 8am - 5pm (classes in session from 9am - 1pm) 
Fri: 9am - 7pm (classes in session from 9am - 4:30pm) 
Sat: 10am - 4pm

### Syllabus

#### Course Objectives

* Learn about electronics, programming, mechatronics, and robotics
* Satisfy the Science and Math (SCIMA) learning outcomes for a 200 level course 
* Have fun

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
- Adam Savage

#### Rules

* Each of you will be given a kit of parts
* Each of you must bring a laptop (Windows, Linux, or Macintosh). If you
don't have a suitable laptop it is your responsibility to check one out of the
Media Center every day.
* Bring your laptop and the kit to every class
* No digital distractions in class. 
	* No phones on the tables. 
	* No instant messaging, email, or working on other projects. 
	* Please disable all notifications on your phone and laptop. 
	* You must be present, engaged, and participating.

#### Prerequisites

    High school math and algebra
    High school English writing skills (grammar, spelling, sentence
construction, etc.)
    Knowing the difference between an opinion and a fact


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
 ** The difference and relationship between voltage and current
** Digital Multimeter
** Schematics, and understanding the Arduino schematic
** Sensors
** Radios
* Arduino
** Introduction
** Arduino inputs: measure voltage. must convert anything to voltage.
resistance doesn't count. voltage dividers, pull ups, and pull downs
** Output: Transistors, H-bridge
** Other than Arduino
* Programming
** Conditionals
** Complex interactions
** Data types
** Arrays and for() loops
** Functions
* Construction techniques
** Prototyping shield
** PCB
* Robotics
** Autonomy
** Making decisions
** Noisy data and filters 
** Thresholds
** Self calibration

### Schedule

The schedule is subject to change

Monday May 22

- Introductions
- Interests and goals
- Hands-on activity
  - Basic Arduino
    (tutorial)[http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop)
  - Making sounds with Tone
- Resources: See the Arduino resources
  [here](https://github.com/michaelshiloh/resourcesForClasses)
- Homework
- Review the Basic Arduino
  (tutorial)[http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop]
  we did in class.
  - Read the entire document
  - Do the section titled _analogWrite(): Controlling speed or brightness_
    which we did not do in class.
    You may check out any equipment you need from the Hybrid Lab,
    either to take home or use in the lab.
- Order the required equipment to arrive no later than Friday January 27 so
  that you can complete the homework for week 3.
- Create your Github repository using
[this guide](https://github.com/zamfi/github-guide)
and email me the URL to your repository



Wednesday May 24
Pre-work stuff

* Answer questions about soldering
* Distribute kits
* Matrix
        Are you trained to use model shop?
        Are you trained to use the laser cutter?
        Do you know how to use Arduino?
        Did you bring your laptop to class?

Lecture/Lab

    Arduino, solderless breadboard, inputs, outputs
    http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop

Demo

    Motors, specifically brushed DC motors (also called DC motors)
    Solder wires to motors
    Hot glue strain relief
    Strip and tin ends

Homework due Friday May 27

    Solder wires (at least 12") to both of your motors, as demonstrated in
class
    Review
        Review what we did in class
http://teachmetomake.com/wordpress/arduino-hands-on-intro-workshop. If you
have not already done so, install the Arduino software.
        Review Arduino basics by reading from Intro through Lesson 4 of
Adafruit’s Arduino tutorial
        Review the AnalogReadSerial on the Arduino website. Remember that we
used a photoresistor instead of the potentiometer.
        Review the photoresistor on Instructables
        If you want some other Arduino resources, there are many. Here are
just two:
            Excellent introduction to Arduino: Arduino in a Nutshell
            Arduino overview with links to many other sources of information
    Learn about switches and digitalRead
        Perform the following steps, and take notes (digital file or paper)
and save programs as you go along. Pay attention to what didn’t work or what
you didn’t understand. I want you to describe the process, not just the final
results.
        Build the photoresistor circuit that we used in class, upload the
sketch, open the serial monitor, and verify that the numbers change as you
allow more or less light to fall on the photoresistor. Make note of the
smallest and biggest numbers you get, very roughly (say rounded to the nearest
50). Remember that the diagrams I showed in class are here
        Remove the photoresistor, and in it’s place put a pair of wires that
go off the breadboard and connect to nothing. In the picture and diagram below
the wires are the white and blue ones on the
left:20150128_182110arduinoWireSwitch_bbarduinoWireSwitch_schem
        Observe the numbers in the serial monitor. They should be close to
zero. Does this make sense? Remember what I said about the voltage divider:
the voltage in the middle of the divider (at the Analog Input pin A0) will be
somewhere between zero and five volts, depending on the ratio of the two
resistors. The fixed 10k ohm resistor is still there, but the photoresistor is
gone and in its place are a pair of wires that aren’t connected to anything,
in other words, an open circuit. The resistance of an open circuit is
infinite, and compared to infinity, the 10k ohm resistor is very small, so it
pulls the middle voltage down, close to zero.
        While watching the numbers in the serial monitor, touch the ends of
the white and blue wires to each other. The numbers should jump up to close to
1023. Again, remember that the voltage in the middle of the divider (at the
Analog Input pin A0) depends on the ratio of the two resistors. This time in
place of the photoresistor we have a pair of wires that are connected to each
other, in other words, a closed circuit, and specifically, a circuit with no
resistance. Compared to a circuit with no resistance, the 10k ohm resistor is
very big, so the closed circuit pulls the middle voltage up close to 5V.
        The blue and white wires are a switch. A switch simply makes a
connection, in which case you have a circuit with no resistance, or opens the
circuit, in which case you have an infinitely high resistance. Every switch is
a variation on this basic principle.A switch can be either open or closed,
resulting in a reading of close to zero or close to 1023. The Analog Input,
which is designed for measuring voltages with many possible values, is wasted
on this sort of input. Much more suited to a switch is a Digital Input, which
is designed to only measure one of two values: LOW and HIGH.
        In the program, replace the analogRead() command with digitalRead()
and upload the program. Close and open your switch, and see what you get in
the serial monitor. You should see zero with the switch opened, and one with
the switch closed. Zero represents LOW, and one represents HIGH.

Friday May 27
Questions about homework
Lecture

    Command line
    Git
    Github

In class exercise

    Install git
    Sign up with GitHub and send me your username if you haven't already
    Respond to invitation to join CCA-Robotics-Summer-2016 organization and
team on GitHub

In class exercise

    Using 9V battery make motor go. Try to change direction.
    Working in pairs, discuss and sketch out some ideas of how you might use
switches to control the direction

Lecture/Lab

    H-bridge concept
    Caution about external power!
    H-bridge tutorial

Homework due Wednesday June 1

    Multimeters, Arduino
        Read about digital multimeters, for example either SparkFun or
Adafruit
        Read the Arduino Fade tutorial. Note that the example is in File ->
Examples -> Basics -> Fade.
        For another perspective, the Arduino Fade Tutorial is also described
here.
    Git
        Watch these videos created by a CCA teacher (apologies these are a bit
rough)
        - Lecture 1 - watch on vimeo- Lecture 2 - watch on vimeo- Lecture 3 -
          watch on vimeo
        Read these extra resources:
        - Command line in windows
        - Review of basic command line prompts for Mac (for Mac users)
        - Review of command prompts for Windows(for Windows users)
        - Introduction to git/GitHub
        Create a repository of your (firstname-lastname, or use nickname if
you prefer) in our class "organization"
    Robotic devices
        Build cardboard contraption that can move forward, backwards, left,
and right using cardboard, hot glue, and the motors. H-bridge is not required.

Wednesday June 1
Disappointments

    Homework expectations: I am very disappointed with how few people took the
homework seriously. I am going to add homework to the grading
    Attendance expectations: You are expected to attend every meeting. It is
very difficult for me to judge whether an absence should be excused or not. I
am going to give everyone one excused absence, and every other absence will
count as an absence.

Lesson

    Model making studio orientation
    Discuss conditionals
    Discuss fade
    Discuss analog and digital inputs and outputs

In class work

    Create a git repository
        Create git account
        Email me your username
        Respond to my invitation
        Check "Initialize this repository with a README"
        Don't make it private
        Make a wiki page in your repository

Homework due Friday June 3

            This is hard homework. Expect to spend most of Thursday working on
this. Expect to require help from Dena or Andy. Don't wait until Friday
morning and expect to finish before class.
            Read all of the instructions very carefully
            Buy two 9V batteries of your own
            Create a wiki page titled "Homework due on June 3". On that page:
                Name two things you learned from the homework that was due
today
                Name two questions you have from the homework regarding
Arduino or multimeters
                Name two things you'd like to learn more about (from homework
or anywhere)
            You'll be connecting your motors to the H-bridge on the
breadboard. To make it easier to insert the stranded wires from your motors
into the breadboard, you can solder a short length of solid wire to the ends
of the stranded wires: 20150726_143543
            To be safe, slip a short piece of heat shrink tubing around the
solder joint, to prevent short circuits. Ask Dena or Andy to show you how:
20150726_143903Heat the tubing with a heat gun (ask Andy or Dena) and the
tubing will shrink tightly, holding it in place.
            Add your Arduino and H-bridge to your robot. You may need to
rebuild your vehicle to allow for this. Don't spend any time making your
vehicle look pretty - this is a very early prototype and will undergo more
revisions before it reaches the final stage. Decorations are the last thing to
add.
            Read the H-bridge tutorial again. I have added some new sections
and some explanations.
            Connect the H-bridge to one of the motors
            The battery pack that came with your kit will power your Arduino,
but now you will use a separate battery to power the motors. To connect this
battery to your breadboard, get a 9V battery clip from the lab monitor:
batteryclip
            Remember the positive (red) wire goes ONLY to +Vmotor on the
H-bridge which is pin 8. Don't get this wrong or you might destroy your
Arduino! The black wire goes to the ground which is common to everyone.
            Write an Arduino program to test that you can control the motor.
Your code might look like this:
            [codesyntax lang="c"]

            /*
             * Using Arduino to control half an H-bridge and one motor
             * 
             * This program corresponds to the schematic here:
             * http://teachmetomake.com/wordpress/arduino-tutorial-h-bridge#Controlling_the_H-bridge_from_an_Arduino
             */

             // Control pins for the left half of the H-bridge
             // The "const" keyword prevents these variables from changing
             const int enable1 = 6; // PWM pin for speed control
             const int in1 = 4;
             const int in2 = 2;
             
             void setup () {
               pinMode( enable1, OUTPUT);
               pinMode( in1, OUTPUT);
               pinMode( in2, OUTPUT);
               Serial.begin(9600);
             }
             
             void loop () {
               
               Serial.print("Motor full speed in one direction");
               digitalWrite (in1, HIGH);
               digitalWrite (in2, LOW);
               digitalWrite (enable1, HIGH);
               delay (2000); // wait for humans to enjoy the motor turning

               Serial.print("Turning motor off");
               digitalWrite (enable1, LOW);
               // let the motor coast to a stop
               // and for humans to notice it
               delay (2000);
               
               Serial.print("Motor half speed in the other direction");
               digitalWrite (in1, LOW);
               digitalWrite (in2, HIGH);
               // this might be too slow. 
               //If motor doesn't turn, use a bigger number
               analogWrite (enable1, 128); 
               delay (2000); // wait for humans to enjoy the motor turning
                
             }

            [/codesyntax]
            If you run into any problems (motors don't turn, H-bridge
overheats, program doesn't compile, etc.) fix these problems before
proceeding. Describe in your wiki page any problems you ran into and how you
fixed them.
            Connect the other motor to the other half of the H-bridge
following this part of the H-bridge tutorial
            Modify your Arduino program to test the second motor. Add
definitions for the new pin names:
            [codesyntax lang="c"]

             // Control pins for the right half of the H-bridge
             // The "const" keyword prevents these variables from changing
             const int enable2 = 9; // PWM pin for speed control
             const int in3 = 8;
             const int in4 = 7;

            [/codesyntax]
            You will also have to use these new pin names, e.g.
            [codesyntax lang="c"]

            Serial.print("Motor full speed in one direction");
               digitalWrite (in3, HIGH);
               digitalWrite (in4, LOW);
               digitalWrite (enable2, HIGH);
               delay (2000); // wait for humans to enjoy the motor turning

            [/codesyntax]
            Again, if you run into any problems fix these problems before
proceeding. Describe in your wiki page any problems you ran into and how you
fixed them.
            Now you are ready to control both motors at the same time, to make
your robot move around. First make sure the motors both turn in the same
direction by running a program like this:
            [codesyntax lang="c"]

            /*
               Using Arduino to control both halves of an H-bridge
               and two motors

               This program corresponds to the schematics here:
               http://teachmetomake.com/wordpress/arduino-tutorial-h-bridge#Controlling_the_H-bridge_from_an_Arduino
               and here:
               http://teachmetomake.com/wordpress/arduino-tutorial-h-bridge#Using_the_other_half_of_the_H-bridge
            */

            // The "const" keyword prevents these variables from changing
            // Control pins for the left half of the H-bridge
            // I would add the word "left" or "right to the variable
            // names but I want to use exactly the same names that are on
            // the schematics
            const int enable1 = 6; // PWM pin for speed control
            const int in1 = 4;
            const int in2 = 2;
            // Control pins for the right half of the H-bridge
            const int enable2 = 9; // PWM pin for speed control
            const int in3 = 8;
            const int in4 = 7;

            void setup () {
              pinMode( enable1, OUTPUT);
              pinMode( in1, OUTPUT);
              pinMode( in2, OUTPUT);

              pinMode( enable2, OUTPUT);
              pinMode( in3, OUTPUT);
              pinMode( in4, OUTPUT);
              Serial.begin(9600);
            }

            void loop () {

              Serial.print("Both motors forward at a medium high speed");
              // Left motor
              digitalWrite (in1, HIGH);
              digitalWrite (in2, LOW);
              analogWrite (enable1, 200);
              // Right motor
              digitalWrite (in3, HIGH);
              digitalWrite (in4, LOW);
              analogWrite (enable2, 200);
              delay(5000); // long enough to verify direction

              Serial.print("Turning motor off");
              digitalWrite (enable1, LOW);
              // let the motor coast to a stop
              // and for humans to notice it
              delay (2000);
            }

            [/codesyntax]
            If your motors don't turn in the same direction, swap the wires on
one of the motors. It's probably easiest to do this on the breadboard
            where your motors connect to the H-bridge output pins
            As before, make note of any problems and how you fixed them in
your wiki page
            If you have any energy left, try making your robot go:
                Forward for 2 seconds
                Left for half a second
                Reverse for two second
                Right for half
                Forward for one second
            You can do this at any speed you wish

Friday June 3

    Review homework results
        Batteries
        Robots
        Wiki
    Powering Arduino and motors
    Add light sensors to your contraption
    Program your robot to seek light

[codesyntax lang="c"]

/*
   Two light sensors added to the H-bridge to make a light seeking robot

   This program corresponds to the schematics here:
   http://teachmetomake.com/wordpress/arduino-tutorial-h-bridge#Controlling_the_H-bridge_from_an_Arduino
   and here:
   http://teachmetomake.com/wordpress/arduino-tutorial-h-bridge#Using_the_other_half_of_the_H-bridge
*/

// The "const" keyword prevents these variables from changing
// Control pins for the left half of the H-bridge
// I would add the word "left" or "right to the variable
// names but I want to use exactly the same names that are on
// the schematics
const int enable1 = 6; // PWM pin for speed control
const int in1 = 4;
const int in2 = 2;
// Control pins for the right half of the H-bridge
const int enable2 = 9; // PWM pin for speed control
const int in3 = 8;
const int in4 = 7;

// light sensors
const int leftLDR = A0;
const int rightLDR = A1;

void setup () {
  pinMode( enable1, OUTPUT);
  pinMode( in1, OUTPUT);
  pinMode( in2, OUTPUT);

  pinMode( enable2, OUTPUT);
  pinMode( in3, OUTPUT);
  pinMode( in4, OUTPUT);
  Serial.begin(9600);
  analogWrite (enable1, 200);
  analogWrite (enable2, 200);
}

void loop () {

  if (analogRead (leftLDR) > analogRead (rightLDR) ) {
    // Left motor reverse
    digitalWrite (in1, LOW);
    digitalWrite (in2, HIGH);

    // Right motor forward
    digitalWrite (in3, HIGH);
    digitalWrite (in4, LOW);
  } else {
    // Left motor forward
    digitalWrite (in1, HIGH);
    digitalWrite (in2, LOW);

    // Right motor reverse
    digitalWrite (in3, LOW);
    digitalWrite (in4, HIGH);
  }
}

[/codesyntax]
Homework due Monday June 6

    Create a new page on your wiki for homework that is due on June 6. Write
all your answers, questions, observations, etc. on that wiki page.
    Finish your light seeking robot and discuss any problems you run into and
how you solved them. Describe in detail what was wrong and how you figured out
what was wrong. Use this template:
        What did I want to happen
        What really happened
        What might be some reasons for the difference between the desired
behavior and the observed behavior
        How might you test each of those reasons to confirm whether it was in
fact the cause or not
    Upload a short video of your robot responding to light to
Youtube/Vimeo/tumblr/whatever and paste a link in your Github wiki
    Remember that your report is 50% of your grade
    Test your Ultrasonic Distance Measuring Sensor. There are numerous
tutorials for this, including my own here. If you prefer video or other
tutorial styles, search for "Arduino HC-SR04 distance sensor". You don't need
to do anything fancy, just verify that the sensor works by putting your hand
in front of it and getting a reading that seems about right.
        Put a link to the tutorial you found most helpful in your Github wiki
    Readings
        Read each of the these Adafruit sensor tutorials. Note that each link
will tell you the tutorial has moved; you'll have to click on the new location
to see the tutorial
        Pick two sensors that you would like to learn more about from this
list of sensors
        Read this function tutorial for Arduino
        Read the Adafruit stepper motor tutorial and the Adafruit servo motor
tutorial
        For each reading assignment, write in your Github wiki page:
            Two things you learned that interested you
            Two things that confused you OR two questions that you had after
reading

Monday June 6

    Tuesday Hacker Hours
    J.D. Zamfirescu-Pereira , Margaretha Haughwout and I are hosting open
    "hacker hours" on Tuesday 6/7 from 12-2pm in the Hybrid Lab. This means
you
    have access to the three of us in addition to the normally scheduled
Hybrid Lab
    manager and/or monitor.This will be an opportunity to work not only on
your homework, but also to ask
    questions about other projects you may have or would like to explore.
    Introduction to digital electronics
    Functions
        Most useful when you have a group of statements that you use
repeatedly e.g.[codesyntax lang="c"]

            // Left motor reverse
            digitalWrite (in1, LOW);
            digitalWrite (in2, HIGH);

            // Right motor forward
            digitalWrite (in3, HIGH);
            digitalWrite (in4, LOW);

        [/codesyntax]
        Also very useful to organize any group of statements that performs a
specific task
        By choosing meaningful function names, your code becomes much more
readable e.g.[codesyntax lang="c"]

          void turnRobotLeft() {
            // Left motor reverse
            digitalWrite (in1, LOW);
            digitalWrite (in2, HIGH);

            // Right motor forward
            digitalWrite (in3, HIGH);
            digitalWrite (in4, LOW);
          }

        [/codesyntax]
        Parameters or arguments e.g.[codesyntax lang="c"]

          // Make the robot turn left by driving the left wheel backwards
          // and the right wheel forwards. There is one parameter which 
          // sets the speed.
          void turnRobotLeft(int requestedSpeed) {

            analogWrite (enable1, requestedSpeed);
            analogWrite (enable2, requestedSpeed);
            // Left motor reverse
            digitalWrite (in1, LOW);
            digitalWrite (in2, HIGH);

            // Right motor forward
            digitalWrite (in3, HIGH);
            digitalWrite (in4, LOW);
          }

        [/codesyntax]
        Return values e.g.
        [codesyntax lang="c"]

          // Return the difference between reading the right light sensor
          // and reading the left light sensor. A positive number means
          // the right sensor has the greater reading.
          int getLightLevelDifference() {

            int difference;
            difference = analogRead(rightSensorPin) -
analogRead(leftSensorPin);
            return (difference);
          }

        [/codesyntax]
    Demo:
        How to make an extension cable for any device with header pins

Homework due Wednesday June 8

    Download and install Fritzing
    Read Fritzing's Getting Started
    Read Fritzing's Project View
    Read Fritzing's Designing PCB
    Attach an ultrasonic distance measuring sensor to your robot. You may
mount the sensor on the solderless breadboard, or you may mount it elsewhere
in which case you should build the extension I demonstrated in class

Wednesday June 8

    Poll: What other parts should we order? We have about $175 left
    Designing an Arduino shield with Fritzing

Homework due Friday June 10

    Email to me the names of or links to the top components you would like to
use
    Push your PCB layout further towards completion. Try adding a 4 pin header
for the distance measuring sensor.
    Program your robot to avoid obstacles:
        Drive forward until you see something close
        Turn to your left and right and measure the distance to whatever is in
front
        Turn in the direction that has the greater distance
        Remember to do excellent writeups in your github wiki, as I will be
using these for your mid semester evaluations

Friday June 10

    Questions
    Interfacing to other sensors (SPI, I2C, and Serial)
    Demonstrations of each of your robots avoiding obstacles
    3 PM: Laser cutter for those who needed
    Othermill
    Working through an example of taking existing code and modifying it:

/*
   I am Abrar
   this is the program for controlling my robot 
   with a distance measuring sensor
   if it gets too close to something, it looks 
   for a clear path away

   Modified by Michael in class on June 10

   Modified slightly more by Michael before 
   uploading to class blog on June 11
*/


// Control pins for the right half of the H-bridge
const int enable2 = 9; // PWM pin for speed control
const int in3 = 8;
const int in4 = 7;

//other half
const int enable1 = 6; // PWM pin for speed control
const int in1 = 4;
const int in2 = 2;

// ultrasonic distance measuring sensor
const int trigPin = 12;
const int echoPin = 11;

void setup() {

  Serial.begin (9600);

  // pins for the ultrasonic distance measuring sensor
  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);

  // motors
  pinMode( enable1, OUTPUT);
  pinMode( in1, OUTPUT);
  pinMode( in2, OUTPUT);

  pinMode( enable2, OUTPUT);
  pinMode( in3, OUTPUT);
  pinMode( in4, OUTPUT);

  // Set the speed to 100, which is pretty slow
  analogWrite (enable1, 100);
  analogWrite (enable2, 100);
}

void loop() {

  long distance;

  distance = measureDistance();

  // check validity of distance reading
  if (distance >= 200 || distance <= 0) {
    Serial.println("Invalid reading straight ahead");
    // go forward for just a little bit
    goForward(100);
  } else {

    if (distance < 15 ) { 
      // turn left a bit; take measurement 
      // turn right a bit; take measurement 
      // go whereever is more distance 

      // Might need to adjust the turn duration 
      turnLeft(50); // turn left for 50 milliseconds 

      int leftDistance = measureDistance(); 

      // Might need to adjust the turn duration 
      // In theory, 50 milliseconds to get forward, 
      // then another 50 to turn right the same amount 
      turnRight(100); 
      int rightDistance = measureDistance(); 
      turnLeft(50); // return to forward 

      // check validity of both readings 
      if (leftDistance >= 200
          || leftDistance <= 0 
          || rightDistance >= 200
          || rightDistance <= 0) 
       { 
         Serial.println("Either the left or right distance reading is bad"); 
         // better not do anything } 
         // otherwise, check to see if left or right 
         // is the better path 
       else if (leftDistance > rightDistance ) {
        turnLeft(50);
      } else {
        turnRight(50);
      }

    } // end of case where distance is less than 15

    // otherwise, distance is greater than 15, we
    // can proceed forward
    else {
      goForward (200);
    }
  } // end of what to do if we have a valid reading
} // end of loop

// go forward for a certain amount of time
void goForward(int timeToMove) {

  // left motor
  digitalWrite (in1, HIGH);
  digitalWrite (in2, LOW);
  // Right motor
  digitalWrite (in3, LOW);
  digitalWrite (in4, HIGH);

  delay (timeToMove);
}

// turn left for a certain amount of time
void turnLeft(int timeToMove) {

  // left motor
  digitalWrite (in1, LOW);
  digitalWrite (in2, HIGH);
  // Right motor
  digitalWrite (in3, LOW);
  digitalWrite (in4, HIGH);

  delay (timeToMove);
}

// turn right for a certain amount of time
void turnRight(int timeToMove) {

  // left motor
  digitalWrite (in1, HIGH);
  digitalWrite (in2, LOW);
  //Right motor
  digitalWrite (in3, HIGH);
  digitalWrite (in4, LOW);

  delay (timeToMove);
}

// Take a measurement using the ultrasonic discance
// measuring sensor and return the distance in cm
// no error checking takes place

long measureDistance() {
  long duration, distance;

  // measure how far anything is from us
  // send the pulse
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2); // low for 2 microseconds
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10); // high for 10 microseconds
  digitalWrite(trigPin, LOW);
  duration = pulseIn(echoPin, HIGH); // measure the time to the echo
  distance = (duration / 2) / 29.1; // calculate the distance in cm
  return distance;
}

Homework due Monday June 13

    Write a program for your robot that uses both the light sensors and the
distance measuring sensor:
        Measure distance
        If the distance measurement is invalid, do nothing
        If the distance is more than 50 cm, check the light sensors
            If there is more light to the left, go left for a short while
            If there is more light to the right, go right for a short while
        If the distance is less than 50 cm, go backwards (reverse) for a short
while
        Create a page for Monday June 13 in your github wiki, and discuss any
problems or question
    Read about the for() loop
    Read about arrays

Monday June 13

    Arrays and for() loops

[codesyntax lang="c"]

const int numberOfReadings = 600;
int measurements[numberOfReadings] ;
const int ldrPin = A0;

void setup() {
  Serial.begin(9600);
}


void loop() {

  for (int readings = 0; readings < numberOfReadings; readings++) {
    measurements[readings] = analogRead(ldrPin);
    delay(1);
  }


  // calculate the average
  int sum = 0;

  for (int readings = 0; readings < numberOfReadings; readings++) {
    sum = sum + measurements[readings];
  }

  int average = sum / numberOfReadings;

  // what's the difference between print() and println()?
  Serial.print("the highest reading is ");
  Serial.println(measurements[highestReading()]);
}

// return the index of the highest reading
// if there are multiple readings return one of them
int highestReading() {

  int latestHighestReading = 0;

  for (int readings = 0; readings < numberOfReadings; readings++) 
  { 
    if (measurements[readings] > measurements[latestHighestReading]) 
    {
      latestHighestReading = readings;
    }
  }
  return latestHighestReading;

}

[/codesyntax]
Homework due Wednesday June 15

    Read the Serial.print() reference
    Read the Serial.println() reference
    Add to the sketch we created in class to
        Print the average of the readings
        Print the maximum of the readings
        Write a function to print print only the even readings
        Don't bother testing the program for correct operation, but do make
sure it verifies with no errors
    Upload your program to Github using the "Upload files" button. If you
don't have an "Upload files" button you have to initialize your repository by
creating a "README.md" file:
        Enter you repository
        Go to the <>code tab. It's in the same line as the Wiki tab.
        In the "Quick setup" section click on the word "README"
        You'll see a file that has one line in it. Move the curser to the end
of that line and press <Enter>
        Click on "Commit new file" at the bottom of the screen

Wednesday June 15

    Check that everyone uploaded their program to github
    Ultrasonic distance measuring sensor on a servo motor
    Develop program for using the ultrasonic distance measuring sensor on a
servo motor. The program we started developing in class is here.

Homework due Friday June 17

    Build a device to hold your servo motor and to mount the distance
measuring sensor on top of that. You can do it on your robot or as a separate
device. If you want to look at the one I made ask the lab monitor to open the
teacher cabinet.
    Finish the homework that was due on Wednesday
        Upload the file
        After you select the file for uploading, you will be asked to provide
a description or comment. Add a brief description.
        Press the "Commit changes" button
    Read the millis() tutorial
    Read the break() tutorial

Friday June 17

    Finish the program we started on Wednesday
        Finish scanning in 10 degree chunks
        Add print() statements to see what it's doing
        Test what we have so far
        Fix problems
    Sensors from your readings
        Distance, PIR, proximity sensors, and bump
        TV remote IR demodulators
        9 DOF sensors
        TMP36
        Sound
        FSR
        Tilt

Arduino program

The changes that we made in class to the program we were working on are in the
same location on Github:  here.

Note that this is not a new file, but is recorded in Github as changes to the
previous file. You can click on the "History" button to see the history of
what I've uploaded, and if you click on the individual file (the one dated
yesterday) you can see a line-by-line comparison of the changes from
Wednesday.

Using Othermill for double sided PCBs

I received a reply from Other Machine Company and it turns out I was aligning
things improperly. The correct procedure is to align to the lower left hand
corner of the bracket when cutting the Top side and to align to the lower
right hand corner of the bracket when cutting the Bottom side. I have modified
the instructions to reflect this here

You are not required to create a PCB but you will receive extra credit if you
do.
Homework due Monday June 20

The goal for next week will be to make your robot navigate a space reliably
using the light sensor and the distance measuring sensor. Since we were having
trouble with the servo motor, that will be optional.

    Rebuild your robot in a nicer fashion. If necessary, start from scratch.
Keep in mind everything you've learned so far, such as:
        Leave plenty of room for batteries, Arduino, breadboard, other devices
        Make sure it is strong enough that you can plug and unplug things
without breaking anything
        Make sure the robot can move freely. Some of you had wheels that
rubbed against the sides, or casters that couldn't swivel. Fix all of this. I
will bring in a few casters on Monday if you can't find any, but I'd prefer
you buy some over the weekend. You should be able to find inexpensive ones at
dollar stores or other stores.
    For  June 10 you wrote a program that tried to seek light and avoid
obstacles.
        Add print() or println() statements to this program so that you can
see whether it's working properly or not
        Add good comments so that I can understand what you are trying to do
        Make sure it compiles cleanly
        Add it to your github repository
    Download and install Processing from
https://processing.org/download/?processing

Monday June 20

    Github
        Look at my Github repository and see how it tracks history
        Show how to edit a file and then commit those changes
    Introduction to Processing
        Mouse and line drawing example
        Array of objects example
        Arduino + Processing example
        Resources include:
            http://hello.processing.org/
            All of the tutorials at  https://processing.org/tutorials/  but
especially:
                https://processing.org/tutorials/overview/
                https://processing.org/tutorials/gettingstarted/
                https://processing.org/tutorials/drawing/
            http://learningprocessing.com/
    Prototyping shield
    More of your questions
    Work on your robots

Wednesday June 22

Announcements

Open house at Other Machine Company!
Wednesday June 29 at 4:30
1001 Camelia St., Berkeley

Be sure to say hi to Emily Shore and tell her you are a student of mine at CCA

OMChousewarmingReminders

Description of problems and how you solved them is 50% of your grade!

Lecture

    Wireless
        Infrared
            "TV remote" style
        Visible light
            E.g. flashing portion of computer screen to download program into
Arduino
        Radio Frequency (RF)
             WiFi
                Potentially connect to many computers and internet.
                Tends to require more processing power, hence shields with
secondary processor
                Built in to most laptops and phones
                Built in to Arduino Yun and MKR1000
            Bluetooth or BLE
                Usually one-to-one
                Requires app for phone
                Shields or modules
                Built in to most laptops and phones
                Built in to Arduino 101
                Short range
            Zigbee
                Shield
                One-to-one or mesh network
                Not present in most laptops and phones so usually requires two
modules (not cheap)
                Potentially long range
            No protocol e.g. nRF24L01
                Cheap! ($3)
                Low speed
                Low power
                Not super reliable
                Potentially long range with fancier antenna

Future topics

    Multimeter
    Construction techniques
        Wire choices and color coding
     Other motors
        Stepper
    Noisy sensor data
    Other types of Arduinos
    Work through an example using millis()
    LCD

Student pages

    Alaa
    Jake
    Gina
    Nate L.
    Lesa
    Abrar
    Troy
    Jasper
    Freddy
    Scott
    Nate S
    Heather
    Ni
    Kaiyan

Resources

            http://www.kr4.us/
            https://www.servocity.com/
            https://www.inventables.com/
            https://www.adafruit.com/category/227

