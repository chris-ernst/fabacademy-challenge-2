# FabAcademy Micro Challenge II

Woah!! Tatiana, Busi, Joaquin and Chris are building an interactive feedback recorder for Design Dialogues.  


Here you'll find the [3D files for fabrication](/fab_files). All files CC. 

Find our Miro board here: https://miro.com/app/live-embed/uXjVOErRQPQ=/?moveToViewport=-555,-3315,3861,3052

# Emergent Interrogations

## 1. Academic level



### Explain how it is linked to your research areas

We decided to collaborate on a joint project that  incorporates human bodies with technology in a provocative, speculative way. Our individual design research areas vary as follows:  Joaquin is interested in body cognition, data interpretation and human-tech relationships. Tatiana explores activism, art, technology, science, and the environment. Chris explores intelligence in technological artifacts and co-design with algorithms, while Busisiwe looks into the junctions between the digital and physical navigating decentralization infrastructures and self organization.


### Initial idea / Concept of the Project ( What questions need to be answered?)

In combining and navigating our interests, we saw intersections in our interests, mainly themes of immersive and interactiveness, explorative education, engaging experiences and provocative products. 

After understanding our collective themes, we asked ourselves, how can we create an artifact that collects and presents data, using movement to answer provocative questions centered around MDEF journey and our collective consciousness.

### Propose (What is supposed to do or not to do)

What should the Artifact do:

* Connect to Kinect, Grasshopper, Firefly to recognise body movement and gestures via skeleton tracker
* Through Grasshopper and Firefly, determine lines and points as nodes on the body that the Kinect has sensed to connect to a servo Motor
* Control a servo Motor and its parameters on Grasshopper/ Firefly, using Arduino sketches and Uno Write component, use arm gestures to control the motors movement
* Servo Motor should successfully move a pen and  move according to the gestures sensed through the kinect.
* Control a DC and its parameters on Grasshopper/ Firefly, using Arduino sketches and Uno Write components. This motor should rotate a disk while the servo inscribes the drawing according to the gestures. 
*A series of questions should be listed, where the observer answers YES or NO through arm gestures 



What should the Artifact not do:

* The motors should move at the correct speed, not to fast or too slow
* The questions/ prompts, the movement of the DC Motor should not be out of sinc. We calibrated each component to be in a 40 second window where each question should be answered in a 5 second window.



### Shown how your team planned and executed the project

![photo](/photos/plan.png)

We subdivided the tasks between areas of interest/skill. Initially, whoever was interested in working on a particular side of the project would do so, but towards the end we started to subdivide the tasks based on our familiarity with the program/topic. 

For example, Tatiana and Busi were interested in working with Grasshopper, Arduino and Kinect so they were in charge of most of the electronics. On Friday, when we were working to finish everything on time, Juaco was delegated to do the 3D models because he had lots of experience with them.

![photo](/photos/roles.png)

### System diagram (illustration explaining function, parts, and relations)

Initial Sketches

<p float="left">
  <img src="/photos/sketch1.jpg" width="500" />
  <img src="/photos/sketch2.jpg" width="500" /> 
</p>

<p float="left">
  <img src="/photos/sketch3.jpg" width="330" />
  <img src="/photos/sketch4.jpg" width="330" />
  <img src="/photos/sketch5.jpg" width="330" />
</p>

![photo](/photos/system_diagram.jpeg)


### Integrated Design (How you designed it - relation between elements)

Relation between elements



* XBox Kinect to Firelfy: We connected the Kinect to Firefly creating parameters and co-ordinated to sense gestures and 



* Honest Design (use of technology in a meaningful way, in relation to the topics)*

#### CNC
We used the CNC milling machine to create the structure for our design. Since we didn’t want to waste material by making avoidable mistakes, we initially prototyped the base using cardboard.

#### 3D SCANNING
We used the Kinect to be able to detect the motion of the participants because we wanted the project to be interactive. Grasshopper was the program we used to make the movements control the servo. Later, we also combined more electronic components in Grasshopper, such as the button, spinning DC motor and potentiometer.

#### ELECTRONICS DESIGN
We used Arduino UNO and bread boards with servos, motors, buttons and potentiometer to be able to control the rotation of the panel and movements of the pen in relation to the Kinect. We used various 

##### EMBEDDED PROGRAMMING
We used Arduino to design the electronics: turning on the motor with a button and regulating the speed. Then, we ended up finalizing everything in Grasshopper so that we could have a unique file with both Kinect and electronic components.

#### 3D MODELING
The joint between the motor and the cardboard “wheel” was modeled in Fusion, imported to Cura and printed using the fab lab ender-3 printer. 

#### LASER CUTTING
The handle meant to hold the servo and pen was designed in Fusion, then laser cut using an acrylic scrap sheet.


### Be creative (find solutions with materials and technology you have)

All of us were unfamiliar with Grasshopper, so we were excited to dive deeper into that software. It encouraged us to approach the program with an unfamiliar, new mindset because the logic behind the nodes was not something we were used to.
The rotation of the wheel: we came up with an unconventional solution to spinning the wheel with the motor, since we wanted to spin it slower than what the motor allowed us. We used a rubber band to create friction around the wheel. 

###Explore design boundaries (based on your expertise)

In the exploratory phase, we encouraged each other to work with unfamiliar topics so that we could expand our knowledge. Tatiana and Busi worked on Arduino, which is something they didn’t have much knowledge on, while Juaco experimented with the Kinect and we all worked on the grasshopper file, contributing what we could and asking Edu for help.

When it was time to work fast, however, we did give priority to those who had expertise in the fields we needed.

### Listed future development opportunity for this project

We wanted to explore how digital data can make physical products. It would be interesting to introduce more mediums to play with the Kinect.
It would be nice to paint the board black so that we wouldn’t make any marks with the sharpie, and also find a good dimension white paper for the spinning wheel.


## Replicability

How did you fabricate it (fabrication processes and materials)

We started out by sketching various iterations of the structure. We first created a cardboard prototype to understand the dimensions and functionality of the box.

<p float="left">
  <img src="/photos/Prototype1.JPG" width="200" />
  <img src="/photos/Prototype2.JPG" width="200" />
  <img src="/photos/Prototype3.JPG" width="200" />
  <img src="/photos/Prototype4.JPG" width="200" />
</p>

![photo](/photos/prototype.gif)

![photo](/photos/Sensing1.png)


After the prototype, we began to create the file to CNC. We settled for a MDF wooden panel which could hold in place the spinning wheel and the arm on which the motor was placed. Juaco designed some panels to hold the structure in Fusion, then worked on the gcode to be able to CNC them.
We also modeled some attachments to keep all the electronic components in place. Juaco created an adapter from the motor to the disk (motor axle mount), another joint from the lever to the servo and a final one from the lever to the pen.

Here are screenshots of the process done in grasshoppper.

<p float="left">
  <img src="/photos/GHArduino.png" width="500" />
  <img src="/photos/GHFirstprogram.png" width="500" />
</p>


<p float="left">
 <img src="/photos/GHKinect.png" width="500" />
  <img src="/photos/GHservo.png" width="500" />
</p>


<p float="left">
  <img src="/photos/GHdcmotor1.png" width="350" />
  <img src="/photos/GHdcmotor2.png" width="350" />
  <img src="/photos/GHphrases.png" width="350" />
</p>

### Design & Fabrication files (open source or open format)

You can find all the files here: [3D files for fabrication](/fab_files). 

Screenshots of the process:

![photo](/photos/Fusion1.png)
![photo](/photos/Fusion2.png)



<p float="left">
  <img src="/photos/CNC1.JPG" width="200" />
  <img src="/photos/CNC2.JPG" width="200" />
  <img src="/photos/CNC3.JPG" width="200" />
  <img src="/photos/CNC4.JPG" width="200" />
</p>

<p float="left">
  <img src="/photos/juaco_cnc_result.jpg" width="200" />
  <img src="/photos/juaco_chris.jpeg" width="200" />
  <img src="/photos/juaco_chris2.jpeg" width="200" />
  <img src="/photos/3d2.png" width="200" />
  <img src="/photos/tatiana.jpeg" width="200" />
</p>


![photo](/photos/juaco_cnc_result.jpg)

![photo](/photos/juaco_chris.jpeg)
![photo](/photos/juaco_chris2.jpeg)

![photo](/photos/3d2.png)

![photo](/photos/tatiana.jpeg)



### BOM (Build of Materials)

<ul>
<li> Computer ;)
<li> Kinect
<li> Arduino 13
<li> Button
<li> Motor
<li> Servo
<li> 10 cables
<li> 1 MDF panel 1 220 x 2440 x 10.3 mm 
<li> Carboard panel cut in a 50x50cm circle
<li> Screw to fit between MDF panel and cardboard circle.
<li> Acrylic scraps (Ours was 40x15cm)
<li> 3D printed material
 
 </ul>

### Iteration Process (spiral development)

Working with the Kinect: Juaco, Busi and Tatiana worked on Grasshopper, connecting the Kinect to a servo. The servo would move up or down based on the distance between the participant’s hands. The wider the distance, the more the servo would move in a certain direction.
On Wednesday, we created our first iteration of the project. We made a prototype out of cardboard which contained the spinning wheel and the lever that moved the pen up and down according to the movements detected by the Kinect.

![photo](/photos/prototype.gif)
![photo](/photos/prototype.jpeg)

The only thing that needed to be added was the motor that would spin the wheel for a certain amount of seconds and be resetted by a button.


### Describe the problems and how the team solved them

There was a problem when trying to control the amount of time for which the motor was spinning. When controlled by the button, there was a strange ratio appearing on Grasshopper. The time was about 3x faster than the values that we inserted, and the problem only persisted with the button. The only way we could solve this was by modifying the step count from 1 second to 3 seconds.

The motor’s spinning was hard to control: the threshold it had was very specific and below a certain number, it would just shut down. This meant that the full rotation was too fast for what we required. We solved this problem by creating a sort of gear with the spinning wheel.

We encountered multiple incompatibilities when trying to combine separate Grasshopper files (the Kinect project + the electronics project) and we still do not know what the problem is. We had to rebuild and reset many of the nodes for the file to work again.


### Photographies of the end artifacts

Final photos:

![photo](/photos/final_mount.gif)



