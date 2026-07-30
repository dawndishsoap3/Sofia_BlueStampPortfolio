# Layered clothing separation system

This project is based off of a consistant problem present in closets, specified towards those who stack their clothes up in large sections of closet. Though its workability remains debatable, the project itself is meant to be a mechanism stacked beside the original set-up to take up little room but lift up layers of clothes to avoid the chaos from pulling out one piece of clothing.

```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Sofia H | Lynbrook | CS/Robotics | Incoming Sophomore 

![Headstone Image](logo.svg)
  
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/pXLjiaRDFJA?si=oMpKDkiPru_itYRW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

- Challenges
  
  - Rail:
Create a fitting support to attach to the pinion that won't stick or get stuck on the rail. Both the rail itself and the structure took multiple cadded attempts to get right, with it frequently getting stuck along the rail and being hard to remove/slide again.

  - Platform Supports:
Due to a lack of time, the 3D printed support was incredibly weak, and it frequently snapped with extra pressure from the turnbuckle. The solution was to add copius amounts of hot clue to secure it, which ended up working out decently well.

  - Rack + Pinion:
1. Other side of structure
Initially the gear would keep on jumping on one end of the structure so that the pinion wouldn't run straight. My solution was to cad a separate system that can attach into the gear but still allow it to turn but preventing it from jumping upwards.

2. Servo Motor
The servo motor itself wasn't attached very well to the structure, so it would still jump when the gear was running, so I got help from dad to cut up some wood to nail the servo into to prevent excess movement. There were also lots of issues later on with the wood being too high and the gear still jumping steps, and so I just removed more hot glue on the bottom and sanded the bottom of the wood pieces.



- What I hope to learn in the future
  
    - I need to be more innovative with my ideas and think ahead. For this project I didn't end up with enough time to fix the major issue of the project not entirely working for its intended purpose of folded clothes. For one thing the structure is too small and limited  to work with full sized clothes, and for another thing the wedge often gets stuck at even the smallest inconsistencies with the clothing, which causes the whole thing to somewhat malfunction. Instructors did tell me that it would be an issue, but the project itself took more time than I presumed, and at the start I believed precision from the user would simply be enough so time management and thinking ahead of time. I also want to solve issues with larger scopes instead of smaller projects that are niche in use.


- Integration:

  - New:
    - Added lead screw to create extra support for other end of the platform.
    - 3D printed and cadded a support for turnbuckle to latch onto.
    - Printed a Rail + supports to stick onto the pinion for the pinion to latch onto.
    - Controller + wiring to control both stepper motor and servo motor.
    - Extra platform to hold breadboard + Arduino.
    - Replace previous DC motor with servo motor for better torque
    - Printed alternate side to rack to hold in in place and ensure the gear goes over both pinions without jumping.
    - Attached wooden backing to servo motor to secure it without extra movement.
    - Rubber bands removed and replaced with turnbuckle. Turnbuckle latches onto 3D printed connector and the platform on the other side to secure somewhat equal placing on both ends.


  - Old:
    - Rubber Bands hold the entire right end of the structure down to balance out the sides.
    - The entire other side of the main structure provides the platform for the clothes to lie on top of, considering the mechanism cannot reach below the base of the motor/structure.
    - Linear bearing used for smoother motion along the metal bar.
    - The rack part of the system is glued onto the spinning portion of the DC motor.
    - The stepper motor is attached to the makeshift rail(metal bar) using flat pieces of acrylic + 3D platforms to drag the platform up when the stepper motor moves up/down.
    - The motor along with a rack & pinion mechanism will be attached on top of the platform to pull/push the wedge.
    - The motor will driver the gear forwards or backwards to push or pull the pinion part of the mechanism.
    - The motor itself is powered by an external battery of around 6v along with an H-bridge.
    - The motor driver along with the external power source will drive the rotation process of the stepper motor so the platform + nut moves up & down along the bar.



# Second Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/UdAOEMXKUa8?si=n13M24BPBgDxM0hO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


For your second milestone, explain what you've worked on since your previous milestone. You can highlight:

- What needs to be completed:
    - Need to find a way to connect the pinion part of the mechanism onto the actual structure in a way that doesn't topple the entire wedge.
    - Create the wedge.
    - Attach the DC motor.
    - Add the modification for the controller to control the stepper motor + DC.

- Integration:

  - New:
    - Rubber Bands hold the entire right end of the structure down to balance out the sides.
    - The entire other side of the main structure provides the platform for the clothes to lie on top of, considering the mechanism cannot reach below the base of the motor/structure.
    - Linear bearing used for smoother motion along the metal bar.
    - The rack part of the system is glued onto the spinning portion of the DC motor.

  - Old:
    - The stepper motor is attached to the makeshift rail(metal bar) using flat pieces of acrylic + 3D platforms to drag the platform up when the stepper motor moves up/down.
    - The motor along with a rack & pinion mechanism will be attached on top of the platform to pull/push the wedge.
    - The motor will driver the gear forwards or backwards to push or pull the pinion part of the mechanism.
    - The motor itself is powered by an external battery of around 6v along with an H-bridge.
    - The motor driver along with the external power source will drive the rotation process of the stepper motor so the platform + nut moves up & down along the bar.

- Challenges:

  - Balance:
    - Since one side of the main structure is a metal bar, the rest of the structure can slide along it freely. Even when connected to the other part of the structure on the stepper motor it consistantly slides down. When the stepper motor itself moves down, the other side follows relatively smoothly, but when the stepper motor moves upwards instead the acrylic plate would just bend and the other side of the plate would get stuck. My solution was to use tension to (somewhat) fix the problem by adding an extra upwards turning 'hook' on the platform with the stepper motor and connecte it to the bottom of the structure. The result partially worked by pulling the weight of the structure towards the stepper motor side, but more weight added towards both sides in the future would offset that balance, but thats a future problem.

  - Limit Switches:
    - The actual connection between the wire and the limit switch itself was incredebly fragile, so the biggest problem I had with the switches would be the wire completely breaking off, so the version currently on the project is the 5-6th version. Actually wrapping the wire itself around the connection was another challenge considering the wires wouldn't always pass the hole through the connection, which would sometimes result in weak connections especially when I first started working with the switches.



# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/ISGqGEbCcpE?si=TqQMsiPEvNbvCroy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:

- Integration:
    - The stepper motor is attached to the makeshift rail(metal bar) using flat pieces of acrylic + 3D platforms to drag the platform up when the stepper motor moves up/down.
    - The motor along with a rack & pinion mechanism will be attached on top of the platform to pull/push the wedge.
    - The motor will driver the gear forwards or backwards to push or pull the pinion part of the mechanism.
    - The motor itself is powered by an external battery of around 6v along with an H-bridge.
    - The motor driver along with the external power source will drive the rotation process of the stepper motor so the platform + nut moves up & down along the bar.



- Technical progress:
    - The entire idea including the design and the first prototype following design finished. Also recieved most of the needed materials for the building process and tested the TT DC gear motor with the L298N motor driver; Nema 17 stepper motor + TMC2209 motor driver successfully. Multiple portions of the overall design were also cadded, printed and altered to fit into the rest of the materials. I used a combination of pieces of acrylic & 3D prints to create the main backing of the mechanism.

- Challenges:
  - Cadding on Onshape:
Started working with cadding & Onshape for the first time & could not figure out how to maneuver around & create specific shapes with the system.

  - Drilling through acrylic:
    - Acrylic is incredibly easy to fracture through drilling, so drill bits had to slowly increase in size being one of the most time-consuming parts of the project so far. My first try at drilling through broke part of the acrylic clean off about half way through a 30 min process.

  - Working with Nema 17 Stepper Motor:
    - Since a 12V battery was unavailable, a giant power generating box was used in its place untill the power adapter arrived. When wiring I made a mistake connecting the motor driver GND to the power source and the power source to GND & may or may not have shorted the motor driver and cooked the wire. On the second try the wiring had go be repetitively fixed but the major issue lied in the potentiometer being autoset to the highest setting and drawing way too much current. The entire process took around a whole session's worth of time to fix with instructor help.

- What your plan is to complete your project
    - My plan is to continue finishing the rest of the main structure as well as the backing in the next week along with integration with the limit switch x motor. Hopefully the second milestone will completely finished by the end of next week and the third milestone almost done. 

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
#include <Servo.h>


// --- FUNCTION PROTOTYPES ---
void moveDistanceMM(float distanceMM, bool direction);
void stepMotor(bool direction, unsigned long delayMicros);


// --- MOTOR PINS (NEMA 17 Stepper) ---
const int stepPin = 3;
const int dirPin  = 4;
const int enPin   = 5;


// --- SERVO PIN ---
const int SERVO_PIN = 9;


// --- BUTTON PINS ---
const int btnServoToggle = 10; // Button to start/toggle Servo sequence
const int btnUp          = 11;
const int btnDown        = 12;
const int btnQuit        = 13;


// --- LIMIT SWITCH PINS (For Servo) ---
const int SWITCH_1 = 6;
const int SWITCH_2 = 2; // Pressing this stops servo completely


// --- STEPPER MOTOR SETTINGS (From Code 1) ---
const float STEPS_PER_MM = 25.0;       
const float TARGET_SPEED_MM_PER_SEC = 8.0; // Fast speed (8.0 mm/s)


const unsigned long stepDelayMicros = (1000000.0 / (STEPS_PER_MM * TARGET_SPEED_MM_PER_SEC)) / 2.0;


// Track stepper position in millimeters
float currentPositionMM = 0.0;


// --- STEPPER CONTINUOUS STATE TRACKING (From Code 1) ---
bool isContinuousUP   = false;
bool isContinuousDOWN = false;


unsigned long lastUpPressTime   = 0;
unsigned long lastDownPressTime = 0;
const unsigned long DOUBLE_PRESS_WINDOW = 500;


// Edge detection variables for buttons
int lastBtnUpState   = HIGH;
int lastBtnDownState = HIGH;


// --- SERVO OBJECT & STATE TRACKING (From Code 2) ---
Servo myServo;
bool servoActive = false;
bool movingTo180 = true;


// Edge detection variables for Servo controls
int lastSwitch1State  = HIGH;
int lastSwitch2State  = HIGH;
int lastServoBtnState = HIGH;


void setup() {
 Serial.begin(9600);


 // Stepper pin setup
 pinMode(stepPin, OUTPUT);
 pinMode(dirPin, OUTPUT);
 pinMode(enPin, OUTPUT);
 digitalWrite(enPin, LOW); // Enable driver


 // Button & Switch setup with internal pull-ups
 pinMode(btnUp, INPUT_PULLUP);
 pinMode(btnDown, INPUT_PULLUP);
 pinMode(btnQuit, INPUT_PULLUP);
 pinMode(btnServoToggle, INPUT_PULLUP);
 pinMode(SWITCH_1, INPUT_PULLUP);
 pinMode(SWITCH_2, INPUT_PULLUP);


 Serial.println("--- System Ready (Servo Idle until Pin 10 pressed) ---");
}


void loop() {
 // Read current states
 int btnUpState    = digitalRead(btnUp);
 int btnDownState  = digitalRead(btnDown);
 bool quitPressed  = (digitalRead(btnQuit) == LOW);


 int switch1State  = digitalRead(SWITCH_1);
 int switch2State  = digitalRead(SWITCH_2);
 int servoBtnState = digitalRead(btnServoToggle);


 // ==========================================
 // 1. SERVO CONTROL LOGIC (Exclusively from Code 2)
 // ==========================================
 if (servoBtnState == LOW && lastServoBtnState == HIGH) {
   if (!servoActive) {
     servoActive = true;
     myServo.attach(SERVO_PIN);
     Serial.println("Pin 10 Pressed! Starting Servo sequence...");
   } else {
     movingTo180 = !movingTo180;
     Serial.println("Pin 10 Pressed! Toggling Servo direction...");
   }
   delay(50); // Debounce
 }


 if (switch1State == LOW && lastSwitch1State == HIGH) {
   if (!servoActive) {
     servoActive = true;
     myServo.attach(SERVO_PIN);
   }
   movingTo180 = !movingTo180;
   Serial.println("Switch 1 Pressed! Toggling Servo direction...");
   delay(50);
 }


 if (switch2State == LOW && lastSwitch2State == HIGH) {
   movingTo180 = !movingTo180;
   servoActive = false;
   myServo.detach();
   Serial.println("Switch 2 Pressed! Toggled direction and STOPPED Servo.");
   delay(50);
 }


 lastSwitch1State  = switch1State;
 lastSwitch2State  = switch2State;
 lastServoBtnState = servoBtnState;


 if (servoActive) {
   if (movingTo180) {
     myServo.write(180);
   } else {
     myServo.write(0);
   }
 }


 // ==========================================
 // 2. STEPPER MOTOR BUTTON PRESS LOGIC (Exclusively from Code 1)
 // ==========================================


 // --- UP BUTTON DETECT ---
 if (btnUpState == LOW && lastBtnUpState == HIGH) {
   unsigned long currentTime = millis();


   if (isContinuousUP || isContinuousDOWN) {
     isContinuousUP   = false;
     isContinuousDOWN = false;
     lastUpPressTime  = 0;
     Serial.println("Continuous Movement STOPPED via UP Press.");
   } else {
     if (currentTime - lastUpPressTime <= DOUBLE_PRESS_WINDOW) {
       isContinuousUP  = true;
       lastUpPressTime = 0;
       Serial.println("Double Press UP! Starting Continuous UP Movement...");
     } else {
       lastUpPressTime = currentTime;
       Serial.println("UP Pressed (Pin 11) - Moving 1mm");
       moveDistanceMM(1.0, HIGH);
     }
   }
   delay(50); // Debounce
 }


 // --- DOWN BUTTON DETECT ---
 if (btnDownState == LOW && lastBtnDownState == HIGH) {
   unsigned long currentTime = millis();


   if (isContinuousUP || isContinuousDOWN) {
     isContinuousUP   = false;
     isContinuousDOWN = false;
     lastDownPressTime = 0;
     Serial.println("Continuous Movement STOPPED via DOWN Press.");
   } else {
     if (currentTime - lastDownPressTime <= DOUBLE_PRESS_WINDOW) {
       isContinuousDOWN  = true;
       lastDownPressTime = 0;
       Serial.println("Double Press DOWN! Starting Continuous DOWN Movement...");
     } else {
       lastDownPressTime = currentTime;
       Serial.println("DOWN Pressed (Pin 12) - Moving 1mm");
       moveDistanceMM(1.0, LOW);
     }
   }
   delay(50); // Debounce
 }


 lastBtnUpState   = btnUpState;
 lastBtnDownState = btnDownState;


 // --- QUIT BUTTON ---
 if (quitPressed) {
   isContinuousUP   = false;
   isContinuousDOWN = false;


   Serial.println("QUIT Pressed (Pin 13) - Returning to 0.0 mm");


   if (currentPositionMM > 0.0) {
     Serial.print("Retracting ");
     Serial.print(currentPositionMM);
     Serial.println(" mm...");
     moveDistanceMM(currentPositionMM, LOW);
   } else {
     Serial.println("Already at position zero.");
   }


   Serial.println("Arrived at 0.0 mm.");
   delay(200);
 }


 // ==========================================
 // 3. STEPPER CONTINUOUS EXECUTION LOOP
 // ==========================================
 if (isContinuousUP) {
   stepMotor(HIGH, stepDelayMicros);
   currentPositionMM += (1.0 / STEPS_PER_MM);
 } else if (isContinuousDOWN) {
   stepMotor(LOW, stepDelayMicros);
   currentPositionMM -= (1.0 / STEPS_PER_MM);
 }
}


// Low-level helper to pulse stepper once
void stepMotor(bool direction, unsigned long delayMicros) {
 digitalWrite(enPin, LOW);
 digitalWrite(dirPin, direction);
 digitalWrite(stepPin, HIGH);
 delayMicroseconds(10);
 digitalWrite(stepPin, LOW);
 delayMicroseconds(delayMicros);
}


// Function to drive the Stepper Motor fixed distance (With acceleration ramp)
void moveDistanceMM(float distanceMM, bool direction) {
 digitalWrite(enPin, LOW);
 delayMicroseconds(10);
 digitalWrite(dirPin, direction);
 int totalSteps = distanceMM * STEPS_PER_MM;
 unsigned long currentDelay = stepDelayMicros * 2;


 for (int i = 0; i < totalSteps; i++) {
   digitalWrite(stepPin, HIGH);
   delayMicroseconds(10);
   digitalWrite(stepPin, LOW);
   delayMicroseconds(currentDelay);


   // Acceleration ramp over first 20 steps
   if (i < 20 && currentDelay > stepDelayMicros) {
     currentDelay -= (stepDelayMicros / 20);
     if (currentDelay < stepDelayMicros) {
       currentDelay = stepDelayMicros;
     }
   }
 }


 // Update track position
 if (direction == HIGH) {
   currentPositionMM += distanceMM;
 } else {
   currentPositionMM -= distanceMM;
 }


 Serial.print("Current Stepper Position: ");
 Serial.print(currentPositionMM);
 Serial.println(" mm");
}```


# Start Project: Retro Arcade Console

<iframe width="560" height="315" src="https://www.youtube.com/embed/GA7f74dMpFM?si=IPN6mD2wxSBYlFqZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Process:
    - The starter project was very soldering heavy with bits of screwing around attaching the acrylic plates around the mechanism. Every single piece came in a bag or attached to foam pieces to protect the backing & the instruction maneul was to attach at the front then solder at the back. The project was relatively simple in terms of instructions.

Challenges:
    - Despite the project itself being quite a simple concept, I made a mistake on the first step which led to a small problem that took much longer than it should have. The piece connecting the board and the outer port had one of the major prongs out of the hole it was supposed to be in, and as a result the solder had to be removed from the back. I only noticed the issue when the starter project was nearly done, so part of the challenge was removing the casing of the project & part of the connecting battery holder to get to the section.The one issue was that the solder was effectively stuck in the board and the solder remover didn't work, along with steel wool or ever removing the solder from the front of the board. I recieved a lot of help from instructers during the struggle and the final resort was pulling the entire thing out of the socket and replacing it with a new one.

How it works:
  - The final mechanism can either be connected to a computer through the port or recieve power through 3AA batteries on the back. The entire casing is clear so you can see the entire structure clearly. The button with the red cap on it is the on/off switch for the game & it starts with sound coming from the piezo buzzer direcly below the on/off switch. There are a total of 5 games, of which the 2 I'm familiar with are Tetris and a shooter game. You can scroll through all the games by press the left/right keys. The LED screed on the top right will display your highest score for each game as you scroll through them all. The yellow button with the square symbol at the top represents the start key for any of the games, and for the shooter game it also shoots the beam at the oncoming enemies. The button right below it with the X symbol represents the pause/unpause button for the games. 

# Bill of Materials


| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Stepper Motor | Main backing structure & controls along the y-axis | $21.59 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B0D22G2RG6/ref=ewc_pr_img_1?smid=A18QU8XMRRHZ9O&th=1)"> Link </a> |
| Limit Switch | Limit when the arduino tells the DC motor to stop spinning | $5.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B07X142VGC/ref=ewc_pr_img_4?smid=A30QSGOJR8LMXA&psc=1)"> Link </a> |
| TMC2209 Stepper Motor Driver | Drives the Nema 17 | $13.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B08SMDY3SQ/ref=ewc_pr_img_3?smid=A2K1WYI5NZ8QSW&th=1)"> Link </a> |
| Metal Rod | Other part of the side structure | $19.99 | <a href="[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B08HYK1TLG/ref=ewc_pr_img_9?smid=A2COIW4JKWLTTA&th=1)"> Link </a> |
|Lead Screws | Attachment to secure other platform | $4.99 | <a href="[[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B08HYK1TLG/ref=ewc_pr_img_9?smid=A2COIW4JKWLTTA&th=1)](https://www.amazon.com/gp/product/B079HQ386R/ref=ox_sc_act_image_3?smid=A31QZVWR40HWH8&th=1)"> Link </a> |
| 4AA Battery holder | Provide power to Servo | $5.88 | <a href="[[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B08HYK1TLG/ref=ewc_pr_img_9?smid=A2COIW4JKWLTTA&th=1)](https://www.amazon.com/gp/product/B0DZX39MHK/ref=ox_sc_act_title_6?smid=AQ37Z5F5L6GWK&psc=1)"> Link </a> |
| Polythylene Sheets | Wedge Material | $12.99 | <a href="[[[https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/gp/product/B08HYK1TLG/ref=ewc_pr_img_9?smid=A2COIW4JKWLTTA&th=1)](https://www.amazon.com/gp/product/B0DZX39MHK/ref=ox_sc_act_title_6?smid=AQ37Z5F5L6GWK&psc=1)](https://www.amazon.com/gp/product/B0F6BKVBMR/ref=ox_sc_act_image_15?smid=A2PM3NVHLMC8ZC&th=1)"> Link </a> |
|4-pronged buttons | Controller | NA | NA |
| Breadboard | extra wiring | NA | NA |
| Hot Glue | Attachment | NA | NA |
| Jumper Wires| Wiring | NA | NA |
| Acrylic Plates | Structure | NA | NA |
| Header Pins | Structure | NA | NA |

| Acrylic Plates | Structure | NA | NA |
| Wood | Stabilize rail + Servo | NA | NA |

# Other Resources/Examples

