

# Task 2: API

API stands for Application Programming Interface and it allows communication between frontend and backend. In this task, I built a Weather Application using data from openweathermap.org. I added the generated API key into the JavaScript file using VS Code and integrated it with the given reference code. I used a jQuery plugin to display the fetched weather data on the webpage. I initially faced issues while fetching the data and adjusted the style.css file to correct the output layout.

***Final outcome:*** Weather data was successfully fetched from the API and displayed correctly on the website.
For this website I used HTML, CSS and JavaScript

![website](https://i.postimg.cc/RhMG5hnk/Whats-App-Image-2026-02-13-at-11-27-25-PM.jpg)

[ Code ](https://github.com/prathamesh-6326/Weather-API.git)

# Task 3: Working with GitHub

In this task, I explored the given GitHub repository to understand its structure, commits, issues, pull requests, and GitHub Actions workflow. I forked the main branch to work on fixing an error in the code. Initially, I faced difficulty in understanding how forking and branch management works. After correcting the issue in my forked repository, I committed the changes. I then created and submitted a pull request to the main repository for review.

***Final outcome:*** The code error was fixed and a pull request was successfully submitted.

![website](https://i.postimg.cc/pTnyWJK1/Screenshot-from-2026-02-03-18-16-39.png)

[ Link ](https://github.com/UVCE-Marvel/git-task/pull/242#issue-3891104419)

# Task 4: Get familiar with the command line on ubuntu

Ubuntu was already installed as the default operating system on my laptop, so I started using it for regular tasks. I explored the interface and focused on working through the terminal. Since I was new to Linux, the commands were different from what I had used before. I practiced basic commands such as mkdir, cd, touch, cat, and chmod to understand file handling and permissions. With regular use, I became comfortable navigating and executing commands in the terminal.


## The subtasks were:
- Create a folder named test.
- cd into that folder.
- Create a blank file without using any text editor.
- create 2600 folders in this folder where each folder is named like . For example, M90 or B56.
- concatenate two text files containing any random text and display them on the terminal.

| Task | Command |
|:------:|:---------:|
| Create folder | `mkdir test`|
| Change directory | `cd test` |
| Create Blank File | `touch empty` |
| Create n folders | `for i in {1....2600}; do mkdir M$i; done`|
| Concatenate files | `cat file1.txt file2.txt` |
| Print Working Directory | `pwd` |
| Lists the contents in Directory | `ls` |
| Prints the given argument again | `echo` |

***Final outcome:*** I was able to use Ubuntu confidently and execute common Linux commands without difficulty.

![website](https://i.postimg.cc/HkZLbh22/Whats-App-Image-2026-02-04-at-10-42-53-AM.jpg)


# TASK 9: Tinkercad

Tinkercad is an online simulation platform used to design and test electronic circuits virtually. In this task, I explored the Tinkercad environment to understand how basic electronic components work together. I created a circuit using an ultrasonic sensor and a servo motor to build a simple radar-like object detection system. The components were connected virtually and the simulation was run to verify the output. I tested the sensor readings and servo movement to ensure proper working in the simulation.

**Components used:**

- Arduino UNO
- LED display
- Ultrasonic sensor
- Connecting wires

**Ultrasonic sensor:**

An ultrasonic sensor is an electronic device that measures distance using high-frequency sound waves. It emits ultrasonic pulses and calculates the distance by measuring the time taken for the echo to return, based on the speed of sound. It is widely used in obstacle detection, robotics, and parking assistance systems.

***Final outcome:*** A radar-like object detection system was successfully simulated in Tinkercad.

![website](https://i.postimg.cc/VvWfvGvW/Whats-App-Image-2026-02-04-at-4-39-06-PM.jpg)


# Task 10: Speed Control of DC Motor
In this task, I used **Arduino UNO, L298N motor driver, and a DC motor**. The Arduino UNO generated a PWM signal where the duty cycle was controlled through the code. The L298N received a constant 12V supply from the power source. The PWM output from Arduino was connected to the ENA pin of the L298N. Based on the duty cycle, the L298N switched the motor supply ON and OFF rapidly, which changed the effective voltage applied to the motor. I assembled the circuit on a breadboard and corrected minor wiring mistakes during testing.
Final outcome: The motor speed was successfully controlled by varying the PWM duty cycle through Arduino.

***Final outcome:*** The DC motor speed was successfully controlled and varied as required.

![Speed changing](https://i.postimg.cc/kg4JMymY/Whats-App-Image-2026-02-04-at-10-46-07-AM.jpg)

[YouTube Link](https://youtu.be/TO1YyProWOQ)

# TASK 11: LED Toggle Using ESP32
In this task, I used **ESP32, Arduino IDE, LED, 220Ω resistor**, and connecting wires to toggle an LED using a webserver. The ESP32 was programmed to host a simple web server over WiFi. I connected the LED to a GPIO pin of the ESP32 through a 220Ω resistor. Using Arduino IDE, I wrote and uploaded the code to control the LED state through a browser. I corrected minor pin configuration errors during debugging and verified the LED response.

Connections are made as shown in the circuit diagram

![ESP32](https://microdigisoft.com/wp-content/uploads/2021/08/ESP32-1_bb-768x1506.jpg.webp)

A wired connection between ESP32 and the Arduino IDE in the PC is established using a USB-A to micro USB cable. the required code is written in the IDE and is compiled and then uploaded into the ESP32 which is firmly connected to the other components through the GIPO pins. When the uploading of the code is completed an IP address will be generated in the IDE and in any browser you can enter that IP address and get access to the web server which toggles the LEDs.

***Final outcome:*** The LED was successfully toggled through a web interface using ESP32.

![Website](https://i.postimg.cc/6675FYpL/Whats-App-Image-2026-02-16-at-9-13-06-AM.jpg)

[Youtube Link](https://youtube.com/shorts/Svtfvyx2KhQ?feature=share)

# TASK 12: Soldering Prerequisites

I learned the basic prerequisites required before starting soldering work. I identified tools such as soldering iron, solder wire, flux, and safety equipment. I understood proper handling techniques and safety precautions. I practiced holding components and maintaining correct temperature control. I also observed common mistakes like cold joints and overheating.
Final outcome: I understood the required tools and safety steps needed before performing soldering.

### **Difference between Leaded and Lead-Free Solder**

| Parameter | Leaded Solder | Lead-Free Solder |
|:------:|:------:|:-----:|
| Composition | Tin (Sn) + Lead (Pb) | Tin (Sn) + Silver (Ag) + Copper (Cu) |
| Common Ratio | Sn63/Pb37 | Sn99/Ag0.3/Cu0.7 (varies) |
| Melting Point | 183°C | 217–220°C |
| Ideal Tip Temperature | 320–350°C|350–380°C |

***Final outcome:*** Basic soldering was performed successfully with proper joints and safety measures.

![website](https://i.postimg.cc/xCbcpKRw/Whats-App-Image-2026-02-09-at-7-39-59-PM.jpg)


# TASK 13: 555 Astable Multivibrator 

In this task, a 555 timer IC was configured in astable mode to generate a continuous square wave output with a duty cycle of approximately 60%. I studied the working of the 555 timer in astable operation, where it switches continuously between HIGH and LOW states without external triggering. Resistors and a capacitor were connected according to the standard astable configuration. I calculated the time period and frequency using the required formulas before assembling the circuit. Minor wiring mistakes were corrected while verifying the output waveform.


| Components | Quantity |
|:------------:|:----------:|
| 555 timer IC | 1 |
| Resistors Ra = 10 KΩ | 1 |
| Resistors Rb = 20 KΩ | 1 |
| Capacitor C = 10 µF | 2 |
| Bread board | 1 |
| DC Power supply | 1 |
| Connecting wires | as per requirement |


The duty cycle of the astable multivibrator depends on the values of resistors **Ra** and **Rb** and capacitor **C1, C2**.

$$
\text{Duty Cycle} = \frac{R_A + R_B}{R_A + 2R_B} \times 100
$$

$$
\text{Duty Cycle} = \frac{30}{50} \times 100 = 60\%
$$

![website](https://i.postimg.cc/tC6Bd3rz/tim47.webp)

The circuit connections were made as shown in the above circuit diagram. The DC power supply was connected to the IC and then using the probes the output waveform was observed on the digital CRO screen by connecting the probes across the output and ground.
The waveform was an expected square wave.

***Final outcome:*** The 555 timer successfully generated a continuous square wave in astable mode.

![website](https://i.postimg.cc/ZYpWrx0D/Whats-App-Image-2026-02-15-at-4-13-12-PM.jpg)


# TASK 16: Datasheets Report Writing 

## L293D Motor Driver IC

I referred to the L293D motor driver datasheet and studied its pin configuration and working. I analyzed important specifications like voltage range, current rating, and internal H-bridge structure. I noted down functional diagrams and key electrical characteristics. I organized the collected information into a structured report format. The report focused only on technical specifications and usage details.

***Final outcome:*** A complete datasheet-based technical report on the L293D motor driver was prepared.

Hyperlink : [L239D motor driver](https://drive.google.com/file/d/1pK1RQ5Knf2lFC4oHziovkqZ_j5Pvo6ns/view?usp=drivesdk)
