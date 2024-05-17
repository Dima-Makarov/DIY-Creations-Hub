# DIY-Creations-Hub
Place where I store all my project (done and undone)
## BigRedButton
Main repo - here: https://github.com/Dima-Makarov/BigRedButton
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/816129f3-1e2c-461a-a4e3-5abe3377385a)
## DefinitelyNotAFlipperZero
Smart device that incorporates GPS, IMU, OLED display, joystick and is run by arduino nano. Has a beautiful UI with main menu, GPS functionality (current location, time, date, speed, distance to hardcoded places, and can be used as a gps-ruler); IMU fuctionality (shows current pitch and roll angles); timer to set some time interval, and stopwatch to count seconds; Also has a game called "Baloon Pop" that uses IMU to control the point, which you need to get onto a baloon ("O") while avoiding danger ("X").

All of that runs on a single arduino, with flash usage being 99% :)

The device has almost the same dimensions as flipper zero. But still beats it since flipper does not have a gps :)
![General look](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/8ea2c3d8-c678-4633-8885-34d9300c01ef)
![IMU menu. You can see the UI layout: battery percentage, satellite count, time, and specific stuff for IMU](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/25afa410-50fd-4728-a724-c299c0d370c2)
![The development process](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/bc3b776c-8cc4-4595-b2ac-88856c2e9cc8)

## DeviceThatTheoreticallyCouldNavigateTheEntireRoom
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/a6fae5fd-d590-40fc-8202-5443f4284fd8)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/4bb5494a-5d32-48b2-897d-e68981cce888)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/43b76ff8-ceb2-41d9-9a41-c938cfd9ab18)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/d883dadb-e65c-488f-b986-0c81a73e0d0c)
Soo yep. The idea was to have three strings attached to the ceiling, and three servos that control the lengths of the strings. So the device could potentially be extremely useful to navigate the room. For instance, we could attach a gripping mechanism to it and the task of getting the TV remote to the sofa without standing up could have been solved :).

### Details of implementation.
Servos are ofc *fixed* so they have no limits on how long they can rotate in one direction. Device consists of servos, arduino, battery, radio control receiver, and the plastic body (designed in Fusion360).

### Results
In the end, there were a few ritical flaws with the desing. First, It only could navigate inside a triangle formed by the ceiling string attachment points. Second, near the ceiling, the tension in string was becoming high, and servos could not lift it anymore (due to the fact that angle between vertical line and the string was getting bigger). And third, that the device itself was unstable, due to literally hanging on strings from the ceiling.
There is, howewer, still an option to fix the last flaw. We can lower the center of mass of the device, or just add a gyro stabilizer (like on drones) to disconnect the part with strings from the part with "payload".

This concept of strings hanging from the ceiling was used in one of the StuffMadeHere youtube videos (https://www.youtube.com/watch?v=xHWXZyfhQas&t=1329s). But his setup costs like 50k$, mine is slightly (roughly 1000 times) cheaper :)

## TheEggDropper
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/21c94498-47fc-4800-8d18-29e92ae53cee)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/96d61c64-55be-4ead-babb-504737d1a826)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/e58f4eda-f65b-4786-b733-f6363e341f72)
This is part of the project made for the russian cansat competition, where a drone had to fly along a specified route, find an open fire, drop the kinder surprise egg onto it, and return home, all autonomously(!).

### Device
Device went through many iterations, 3 main designs were tester, and we stopped on the third one. It is fairly simple: a metal wire is attached to the egg with a ring on the other end, and a pull rod goes through every ring, and with the signal from the drone, the arduino rotated the servo just enough to release one ring at a time.

### Results
The whole project was 80% completed when the disaster stroke -- because of covid-19, organizers desided to cancel the competition, and the whole system was untested in real environment. But needless to say, this device was the most reliable part of the whole system :).

## StarFinder
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/0760e118-eca7-41c5-a6f9-4273a3517c17)

Main article - here: https://habr.com/ru/articles/506532/

## DroneBlackBox
Like actually black box with antenna
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/8ad731be-9bfd-4e17-89b4-3ea1006d6d5c)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/855faa4d-9ada-4511-bfc6-66a065e99439)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/4d448c95-05fd-47f5-a303-b666fc8e2873)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/f9646c06-27f6-4f64-a16f-ddd6e9d69260)
![image](https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/019d6c7e-e45e-4934-a471-ebfd744831f2)

### Description
I don't remember the exact reason to make this device -- maybe also for cansat project... But still. 

The device consisted of: GPS, Arduino, Radio transmitter (nrf24 long range), battery, battery charging unit, voltage dc-dc converter. The idea was that this device is strapped to a big drone, it constantly sends position data to the ground station, and in case of Rapid Unscheduled Dissassembly of a drone it becomes much easier to find a drone knowing there is a radiobeacon constantly screaming the device location.

I could ofc add a flash drive position recording module, but at the time, did not have an arduino module for that :(

### Results
The project was successfull, I tested it on a real DJI Phantom 3 SE, and it worked with no issues farther than one kilometer in distance.

## TheTragicRadioAirplaneStory

So I am also into model and radiocontrolled planes. Here's a bunch of photos of them.
