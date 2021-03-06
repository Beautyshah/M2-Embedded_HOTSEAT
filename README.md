# M2-Embedded_HOTSEAT
## HOTSEAT
The buttons have to be switched on before the app starts working.
 Potentiometer acts as temperature sensor. It gives signal which is converted by ADC and used to make a PWM signal pf corresponding duty cycle, as seen in the oscilloscope. 
 As potentiometer is varied, message containing detected temperature is shown in serial monitor.
 
 ## Folder Structure
Folder               | Description|
-------------------  | -----------------------------------------|
|1_Requirements     | Documents Detailing requirements and research|
|2_Design   | Documents Specifying design details|
|3_Implementation   | All Code and Documentation|
|4_Testplan and output| Output |
|5_Report   | All details|
|6_ImagesAndVideos| All final images and video of simulation|

## Functions 
| Feature Id | Feature |
| -----------|---------|
|F_01|  sensing if the person is seated  |
|F_02| Blinking the LED  |


## CI Status Badge
[![C/C++ CI](https://github.com/Beautyshah/M2-Embedded_HOTSEAT/actions/workflows/c-build.yml/badge.svg)](https://github.com/Beautyshah/M2-Embedded_HOTSEAT/actions/workflows/c-build.yml)

## valgrind Badge
[![Valgrind](https://github.com/Beautyshah/M2-Embedded_HOTSEAT/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/Beautyshah/M2-Embedded_HOTSEAT/actions/workflows/Valgrind.yml)

## Code Quality Badge
![code quality score](https://api.codiga.io/project/30169/score/svg)

## Code Grade
![code grade](https://api.codiga.io/project/30169/status/svg)

## Codacy Badge
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/4ffe3fdba59c42d7b630d2175bd65b59)](https://www.codacy.com/gh/Beautyshah/M2-Embedded_HOTSEAT/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Beautyshah/M2-Embedded_HOTSEAT&amp;utm_campaign=Badge_Grade)

## Challenges Faced and How Was It Overcome
| No. | Challenge | Solution
|-----|-----------|--------
|1. | On the simulide latest version some sources are not available| By the help of connect class solved |
|2. | issues in implementation | fixed them by making template in order
|3. | Issues in workflows | fixed them by updating the path to all files correctly|
