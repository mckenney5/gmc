G & M Code Checker
==================

![screen shot](https://github.com/mckenney5/gmc/blob/main/sc.png?raw=true)

## Description
This program checks gcode for these specific parameters:
- The Z axis cannot go below -0.25" or above 1"
- The X & Y axis (along with I & J) cannot go below 0" or above 4"
- The feedrate should be set to 10ipm
- The program should be in G90 mode
- There should be no spaces between cords and the number (e.x. no: X 1.00)
- The program should do M03 before cutting, and end with M05
- The 1st and 2nd line should have a comment

All of that are requirements for a high school CNC project.
This program helps students check for those requirements by pasting their program.
All of the source code is in one file to make it easier to embed it into a Google Site.

## License
This code is licensed under the MIT license. See 'LICENSE' for details.

