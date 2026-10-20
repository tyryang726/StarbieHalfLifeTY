Starbie(SQUAREBIE)

Starbie(SQUAREBIE) is a tiny motion-controlled digital pet with 3 gameplay buttons. Instead of pressing controls, you interact with it by physically moving the board. And there is also 2 buttons in the form of keyboard switches

What it is:
Starbie is my first beginner/starter project for Half Life from hackclub. The creature on a small display will react to how you handle it. 
Tilting, moving, and otherwise checking in on your pet are meant to be part of the experience.

The board includes a microcontroller, display, motion sensor, and environmental sensor in a compact PCB design. It is USB powered and built around beginner-friendly through-hole soldering for the add-on components.

Why?
This project was made by me from the tutorial of halflife week 1 pcb design

Project status
The PCB design and an Arduino firmware are included in the files. The default program is a 2 eye pet with a tilt-controlled menu, hidden stats, and a shake reaction.

Software
Firmware/ contains one self-contained Arduino IDE sketch for the XIAO ESP32-C3. I did some customize pins, menu actions, starting values, and motion settings at the top of the sketch.

================================================================================
BILL OF MATERIALS (BOM)

================================================================================

Item             Amount       Cost (ea.)      Source / Link
--------------------------------------------------------------------------------
XIAO ESP32 C3  |  1.0   |    $7.98   |     AliExpress (aliexpress.com/item/1005007084388623.html)

0.96 OLED      |  1.0   |    $1.73   |      AliExpress (aliexpress.com/item/1005006262908701.html)

MPU6050        |  1.0   |    $1.73   |      AliExpress (aliexpress.com/item/1005006262908701.html)

DHT11          |  1.0   |    $1.73   |      AliExpress (aliexpress.com/item/1005008818897051.html)

MX Switches    |  20.0  |    $1.73   |      AliExpress (aliexpress.com/item/1005012898928151.html)

10k Resistor   |  100.0  |   $1.73   |      AliExpress (aliexpress.com/item/1005002388905118.html)

PCB            |  1.0    |   ~$10.00   |    JLCPCB (jlcpcb.com)

--------------------------------------------------------------------------------
Total (each kit) 1.0       ~$26.63       -

================================================================================
pictures:
<img width="1902" height="1068" alt="Screenshot 2026-10-07 172340" src="https://github.com/user-attachments/assets/83ef8d1c-98ec-4b11-b237-9fd0413c5416" />

<img width="740" height="557" alt="image" src="https://github.com/user-attachments/assets/9ee78a8a-2c44-4f4d-b457-b207224b34c1" />

<img width="1902" height="1068" alt="starbie6" src="https://github.com/user-attachments/assets/d07829fb-61c1-4567-9c8a-56ee58bddf5d" />

<img width="454" height="720" alt="image" src="https://github.com/user-attachments/assets/8010a37d-01f3-4247-aeff-51b012db00ee" />
