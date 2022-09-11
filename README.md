# HRSH-AutoSkillCheck
A bot written in Python to automaically pass all skill checks in Dead By Daylight.

The code uses image recognision to find the skill checks. The screenshot of the screen is sent for processing and when a skill checks appears, 
the main code is triggered.

There are 4 things to keep in memory:
> High point for the color red and white
> Low point for the color red and white

The code will look for skill check within the color range of low and high.

When the red reaches white region the check is triggered and a virtual input of the selected key is sent to automate the process.
