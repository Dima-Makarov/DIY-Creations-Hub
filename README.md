# DIY-Creations-Hub
Place where I store all my project (done and undone)
## BigRedButton
Main repo - here: [BigRedButton](https://github.com/Dima-Makarov/BigRedButton)
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/816129f3-1e2c-461a-a4e3-5abe3377385a.png" width="50%" height="50%">
</p>

## DefinitelyNotAFlipperZero
Smart device that incorporates GPS, IMU, OLED display, joystick and is run by arduino nano. Has a beautiful UI with main menu, GPS functionality (current location, time, date, speed, distance to hardcoded places, and can be used as a gps-ruler); IMU fuctionality (shows current pitch and roll angles); timer to set some time interval, and stopwatch to count seconds; Also has a game called "Baloon Pop" that uses IMU to control the point, which you need to get onto a baloon ("O") while avoiding danger ("X").

All of that runs on a single arduino, with flash usage being 99% :)

The device has almost the same dimensions as flipper zero. But still beats it since flipper does not have a gps :)
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/8ea2c3d8-c678-4633-8885-34d9300c01ef" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/25afa410-50fd-4728-a724-c299c0d370c2" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/bc3b776c-8cc4-4595-b2ac-88856c2e9cc8" width="50%" height="50%">
</p>

## DeviceThatTheoreticallyCouldNavigateTheEntireRoom
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/a6fae5fd-d590-40fc-8202-5443f4284fd8" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/4bb5494a-5d32-48b2-897d-e68981cce888" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/43b76ff8-ceb2-41d9-9a41-c938cfd9ab18" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/d883dadb-e65c-488f-b986-0c81a73e0d0c" width="50%" height="50%">
</p>

Soo yep. The idea was to have three strings attached to the ceiling, and three servos that control the lengths of the strings. So the device could potentially be extremely useful to navigate the room. For instance, we could attach a gripping mechanism to it and the task of getting the TV remote to the sofa without standing up could have been solved :).

### Details of implementation.
Servos are ofc *fixed* so they have no limits on how long they can rotate in one direction. Device consists of servos, arduino, battery, radio control receiver, and the plastic body (designed in Fusion360).

### Results
In the end, there were a few ritical flaws with the desing. First, It only could navigate inside a triangle formed by the ceiling string attachment points. Second, near the ceiling, the tension in string was becoming high, and servos could not lift it anymore (due to the fact that angle between vertical line and the string was getting bigger). And third, that the device itself was unstable, due to literally hanging on strings from the ceiling.
There is, howewer, still an option to fix the last flaw. We can lower the center of mass of the device, or just add a gyro stabilizer (like on drones) to disconnect the part with strings from the part with "payload".

This concept of strings hanging from the ceiling was used in one of the StuffMadeHere youtube videos ([Link](https://www.youtube.com/watch?v=xHWXZyfhQas&t=1329s)). But his setup costs like 50k$, mine is slightly (roughly 1000 times) cheaper :)

## TheEggDropper
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/21c94498-47fc-4800-8d18-29e92ae53cee" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/96d61c64-55be-4ead-babb-504737d1a826" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/e58f4eda-f65b-4786-b733-f6363e341f72" width="50%" height="50%">
</p>

This is part of the project made for the russian cansat competition, where a drone had to fly along a specified route, find an open fire, drop the kinder surprise egg onto it, and return home, all autonomously(!).

### Device
Device went through many iterations, 3 main designs were tester, and we stopped on the third one. It is fairly simple: a metal wire is attached to the egg with a ring on the other end, and a pull rod goes through every ring, and with the signal from the drone, the arduino rotated the servo just enough to release one ring at a time.

### Results
The whole project was 80% completed when the disaster stroke -- because of covid-19, organizers desided to cancel the competition, and the whole system was untested in real environment. But needless to say, this device was the most reliable part of the whole system :).

## StarFinder
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/0760e118-eca7-41c5-a6f9-4273a3517c17" width="50%" height="50%">
</p>

Main article - here: [Link](https://habr.com/ru/articles/506532/)

## DroneBlackBox
Like actually black box with antenna
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/8ad731be-9bfd-4e17-89b4-3ea1006d6d5c" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/855faa4d-9ada-4511-bfc6-66a065e99439" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/4d448c95-05fd-47f5-a303-b666fc8e2873" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/f9646c06-27f6-4f64-a16f-ddd6e9d69260" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/019d6c7e-e45e-4934-a471-ebfd744831f2" width="50%" height="50%">
</p>

### Description
I don't remember the exact reason to make this device -- maybe also for cansat project... But still. 

The device consisted of: GPS, Arduino, Radio transmitter (nrf24 long range), battery, battery charging unit, voltage dc-dc converter. The idea was that this device is strapped to a big drone, it constantly sends position data to the ground station, and in case of Rapid Unscheduled Dissassembly of a drone it becomes much easier to find a drone knowing there is a radiobeacon constantly screaming the device location.

I could ofc add a flash drive position recording module, but at the time, did not have an arduino module for that :(

### Results
The project was successfull, I tested it on a real DJI Phantom 3 SE, and it worked with no issues farther than one kilometer in distance.

## RubiksCubeClock
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/bcbe2bbf-bb0d-41ba-8fd2-001e43b930dc" width="50%" height="50%">
</p>

This device slightly differs from other in the fact that it does not use 3d printing at all. The entire model is made out of wood. Also contains AA battery pack, oled, and arduino with a program to process the buttons which are located below left and right hand. The project is successfull and the device is in use today.

## TheTragicRadioAirplaneStory

So I am also into model and radiocontrolled planes. Here's a bunch of photos of them.

It all started from one rubber motor plane, which was modified by me by adding two brushed electric motors, battery and receiver:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/775812bf-6ac4-440e-8aa0-1947266f6733" width="50%" height="50%">
</p>

But, two small quadcopter motors weren't enough to even keep a stable altitude, not even attempting to takeoff. Soo, if you have not enough motors, just add more!
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/ade809a1-f925-4c4d-b02b-73bc67b06723" width="50%" height="50%">
</p>

(Apologies for the image quality, lost a better photo). And it flew!
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/69ba6783-77c7-4150-b064-ded2f73c6884" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/d9c4ce85-bf40-4d78-b963-dda88a2d3751" width="50%" height="50%">
</p>

But still wasn't good enough. The big drag combined with overall small motor power did not allow to do anything cooler than just flying around in circles with it (trying not to stall and hit ground).
So in the end I converted it to a glider and successfuly glided onto a neighbours roof, snapping wings in half:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/43e9758e-2265-4c3f-a50a-a03bfb79bb5a" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/e54acf11-7430-48e1-b898-7618e876d22c" width="50%" height="50%">
</p>

Next I decided to move towards so-called Foxy, which is foam mass-produced airplane. To start things up, I installed old hardware on it: same motors, same battery. It flew better than the old 4-engine version!
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/93ac0644-1779-4b10-9378-6ecce37f3dac" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/609ccff7-82d7-45fb-a32a-bb9261a49691" width="50%" height="50%">
</p>

But, still was underpowered, and although had 2 engines, was not cool enough. It was time for a big change. I bought a new tiny brushless 6 Amp motor, borrowed an overpowered 30 Amp electronic speed controller, a good 3s battery, 2 servos and installed all of that on a plane:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/b4700021-f7c0-40e5-9d37-a036da0a295a" width="50%" height="50%">
</p>

<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/f18eb91a-5a5e-46a2-ad68-f81f1e2cae15" width="50%" height="50%">
</p>

Went outside on a frosen lake. It was cold. I started the engine. It flew. It flew high, perhaps 20 meters above the ground. Aaand merely seconds after that, I lost any understanding of what as going on with a plane, specifically, it's orientation, and it rapidly descended and crashed onto a bush:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/a303fcf2-f1cc-438f-87f5-293be87ff4ff" width="50%" height="50%">
</p>

This event did not upset me. I knew I was going to the right direction. Next step was to buy an armful of foam planes:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/3329383e-2e15-4897-98a1-a213c808bfa6" width="50%" height="50%">
</p>

And I started moving all the hardware to a new frame:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/b082865d-a3e4-4253-a0f9-a940bacb0127" width="50%" height="50%">
</p>

I flew once, and it was great! But I had a feeling that it was too heavy, and wing area wasn't big enough. So, if you have not enough wings, just add more!
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/5a0fca0a-13f7-4842-9232-ad3d71cb1356" width="50%" height="50%">
</p>

It flew brilliantly. Good control, perfect stability, slow speed. It was a really good plane to practice flying:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/821a0509-c652-4efb-a0f2-64f0f04a638c" width="50%" height="50%">
</p>

But later, I decided to remove second wing, just so it could fly faster and do different aerobatic maneuvers. Also tried to install an fpv camera:
<p align="center">
  <img src="https://github.com/Dima-Makarov/DIY-Creations-Hub/assets/79033065/9cb44391-c818-4aa7-ac11-f7efe58e3a45" width="50%" height="50%">
</p>

But didn't quite like it, and now I am flying without it.
