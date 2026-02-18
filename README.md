# MP3 Player and Speaker!
<img width="950" height="837" alt="Screenshot 2026-02-18 120725" src="https://github.com/user-attachments/assets/21b34bea-2e24-4e5d-b23c-bbbb16c7c215" />
<img width="1088" height="815" alt="Screenshot 2026-02-18 120706" src="https://github.com/user-attachments/assets/5f93963d-ac95-43cf-83a5-65619167d424" />

## Description
I got really fed up with paying for my Spoitfy subscription so I decided to make my own MP3 Player!! I originally started this off as only the MP3 player but I ended up making another board to connect to a speaker too! It uses a XIAO Seeed Studio ESP32 C2 as the main brains!

## PCB
The PCB of this was made in KiCad! It mostly uses through hole components so finding the footprints wasn't required since it's mostly connectors. <img width="809" height="769" alt="Screenshot 2026-02-17 220505" src="https://github.com/user-attachments/assets/82b40ef7-56db-4242-baa4-3dadaa8290f2" />
<img width="1615" height="482" alt="Screenshot 2026-02-18 095952" src="https://github.com/user-attachments/assets/87d07813-d638-47e4-ae5f-a166269a8aa1" />
I used a lot of new things like mousebites and a copper fill while making this PCB!
<img width="1024" height="498" alt="Screenshot 2026-02-18 155720" src="https://github.com/user-attachments/assets/5cf6d137-8e28-4ea8-880e-ad99e360b092" />
<img width="1024" height="427" alt="Screenshot 2026-02-18 155734" src="https://github.com/user-attachments/assets/37e7d248-49a2-40ed-9580-d753175529d9" />
## CAD
I made a case for both the boards in Fusion 360! I was already a bit proficient in Fusion 360 so it wasn't that hard to make. I measured the different components and the board in Kicad and then used those to figure out the case. I also imported the board in to see if it would fit.<img width="1423" height="731" alt="Screenshot 2026-02-18 160507" src="https://github.com/user-attachments/assets/3fbcc704-e0da-4ea6-839e-7456f222b34e" />
## Features
It has 3 buttons for Skip Song, Prev Song and Pause/Play. They also function as volume control for when you long press them! Both the boards have an SD Card Reader for you to put the MP3 files in and outputs to listen to the music. It's a really simple design so there's no screen to know which song's playing.

## Challenges
I faced a lot of challenges during this project, mainly with the firmware. I also had trouble choosing my components and I ended up choosing the wrong DAC for my project originally why actually led to it being two boards with kinda the same purpose. But overall I think I learnt a lot through this project!

## PCB User Guide
The PCB features two seperate boards connected with a tab which has mousebites in it. It must be snapped into two parts and the components must be soldered on separately to each. They are two different boards in one PCB!

## Components
The detailed version is in the BOM so please read through that if you have any questions!
XIAO Seeed Studio ESP32 C2 
MAX98367A
PMC5102A
SD Card Reader Module
Switches/Capacitors etc



Thank You for reading! :3
