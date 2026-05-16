# typer-robot
A robo with a hardware similar to 3d printer except that has pen and not filament and same plotter mechanism to help me write low-value tasks like onpaper applications and other documents and save my precious time

(P.s I am using arduino as i have that aldready)

The problem:
I have to spend a lot of time doing low value task like writing handmade applications for school, making a card or maybe writing notes 

The Solution:
I really wanna make a cool plotter that will write for me (very close to a human style)!!


**Working of the Robot**

* The robot will be powered by my ardiuno (I have that) additionaly!
  It will have the parts 3d-printed like base, penholders.etc (In CAD)
  
- Draws on paper through the CNC Motion

#Softwares 
* Inkscape – Vector design creation
* Inkscape G-code Extension – G-code generation
* Universal G-code Sender (UGS) – Command transmission  
  *Allows control like start, pause, resume, and stop
  
- NOTE: UGS does not generate motion logic
UGS does not control motors directly, 
UGS does not require custom firmware


* GRBL Firmware – Motion control execution
* Arduino IDE – Firmware upload and testing

**How it works:**  
Drawing → G-code → Controller → Motors → Pen movement

**Text Handling**
The plotter does not make text directly.
all text is converted into vector outlines before plotting.

**Using Inkscape** – Converts Text to Vector
Converts  text into vector that the robot will follow and move the pen around and make the text on paper 
Removes dependency on fonts during plotting

**Arduino IDE**
Used for:
- Uploading firmware
- Testing calibration and motion routines


## Why I'm requesting the EasyDraw V2 Kit
 
My original BOM uses 28BYJ-48 steppers which I already have, but honestly they have bad torque and a lot of backlash not great for writing cleanly. The EasyDraw V2 kit has NEMA 17 motors with a proper CNC shield, ABS printed parts (not brittle PLA), and a tested 24×30cm draw area which is enough to cover A4 size paper. Building around a solid mechanical base means I can focus on the software side getting the handwriting style right instead of fighting hardware issues. T

IMPORTANT NOTE: I have ideas to customize it even more with custom 3d printing the parts to make it look more of robots and the sole purpose to buy this as a kit is because this is my first big projects it will give me more confidence as the parts are more compataible 


**BOM**

## BOM – EasyDraw V2 Kit (Requesting via Macondo)

| Category | Item | Qty | Cost (INR) |
|---|---|---:|---:|
| Full Kit | EasyDraw V2 Writing & Drawing Machine Kit (Not Assembled) | 1 | 7990 |
| **Total** | **Project Cost (INR)** | | **7990** |
| **Total** | **Approx. Cost (USD)** | | **~96** |

**Kit includes:**
- ABS 3D printed structural parts (CoreXY frame)
- 2× Stepper motors + drivers
- 1× Servo motor (pen up/down)
- Arduino + custom CNC shield (pre-assembled & tested)
- GT2 belts + pulleys
- Steel rods + bearings
- All fasteners
- USB cable

*Source: [shopmakerq.com](https://shopmakerq.com/product/2d-plotter-kit-not-assembled/) | Maximum draw area: 24×30 cm*



### Wiring Diagram

| |
|---|
| ![](https://github.com/studyhridhaan-coder/typer-robot/blob/main/Wiring%20Diagram.png?raw=true) |




**For the reviewer:**
Hello there!! 
You have visited the right place and welcome to my project repo find the README (Which you are reading rn), CAD, Pcb and other concept images.
along with the bill of material,

Edit: I have explain the concept better in readme and made the 



please take your time to review!!
you can also reach out to me
email: Study.hridhaan@gmail.com
slack: @Hridhaan
