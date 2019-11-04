# Arduino-PS2X
Want to interface a PlayStation 2 Controller with an Arduino Microcontroller? You have come to the right place. 

Arduino-PS2X is an easy to use library that will take care of all the low-level interfacing for you, so you can start using the controller right away in your project.

Please refer to the example sketches to learn how to use this library.

## Debugging
If you have problems, open the PS2X_lib.h file and change (i.e.: remove the comment markers):
```
// $$$$$$$$$$$$ DEBUG ENABLE SECTION $$$$$$$$$$$$$$$$
// to debug ps2 controller, uncomment these two lines to print out debug to uart

//#define PS2X_DEBUG
//#define PS2X_COM_DEBUG
```
to:
```
// $$$$$$$$$$$$ DEBUG ENABLE SECTION $$$$$$$$$$$$$$$$
// to debug ps2 controller, uncomment these two lines to print out debug to uart

#define PS2X_DEBUG
#define PS2X_COM_DEBUG
```
to enable debug messages. Save the file and recompile the example sketch. Open the serial terminal and see what it says.

## Authors
- Original code by Shutter on Arduino Forums
- Revamped, made into lib by and continued development by [Bill Porter](www.billporter.info)
- Contributors:
  - Eric Wetzel (thewetzel@gmail.com)
  - Kurt Eckhardt
- Now maintained by SukkoPera

## License
Arduino-PS2X is released under the GNU General Public License (GPL) v3. If you make any modifications to the board, **you must** contribute them back.

Arduino-PS2X is provided to you ‘as is’ and without any express or implied warranties whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties of merchantability, fitness for a particular purpose or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

## Project Showcase

Here are some projects using this library:

-  [FireHero (Guitar Hero Axe Controlled Flamethrowers)](https://www.coolthings.com/firehero/) by *Chris Marion*
-  [Scanalogic Review](http://store.curiousinventor.com/blog/scanalogic_2_logic_analyzer_review/) by *CuriousInventor*
-  [SAGAR](http://www.billporter.info/category/projects/autonomous-rover/) by *Bill Porter*
-  [Remote Controlled Robot](http://www.youtube.com/watch?v=WP2yqu1Rs_M#t=22s) by *teachengineering*
-  [‘America Dream’ Electric Hammock](http://hackaday.com/2011/04/27/be-lazy-and-get-somewhere-at-the-same-time/) *by Stephen Shaffer*
-  [Life size R2D2 robot](http://youtu.be/H9BcXc7ixT0) by *Dan*
