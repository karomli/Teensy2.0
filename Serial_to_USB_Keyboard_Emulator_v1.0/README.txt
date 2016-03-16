LICENSE
=======
Serial-USB Keyboard Emulator is free software: you can redistribute 
it and/or modify it under the terms of the GNU General Public License 
as published by the Free Software Foundation, either version 3 of 
the License, or(at your option) any later version.

Serial-USB Keyboard Emulator is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Foobar.  If not, see <http://www.gnu.org/licenses/>.

Author: Khairul Anuar Romli
Email: maverequi@gmail.com

Serial-USB Keyboard Emulator
============================
Change Log: 
v1.0
- Publish the binary for public usage
v0.9
- Add readme with full list of supported characters
- Add support capital letter characters and small letter characters
v0.8
- Clean up the character checking 
- Break down the character checking code to speed up the hex to code encryption
v0.7
- Added more character into the project

Setup and Configuration
=======================
1. Connect the Host to Host System's USB Port
2. Install FTDI Driver on the Host System.
3. Connect the Client hardware to Remote System's USB Port
4. Open the terminal program and enter the correspending Serial Port.
5. Set Baud Rate to 9600

HOW-TO
======
Modifier: User must type the modifier to differentiate between normal key
and combination of SHIFT with KEYBOARD's KEY.

'~' - Normal Key
'^' - SHIFT + Key

Example Usage:
1.
Type in ~0x04 on Host Terminal
Press Enter
Remote System will send keyboard key press 'a'

2.
Type in ^0x13 on Host Terminal
Press Enter
Remote System will send keyboard key press 'P'

KEY LIST
========
Key List is based on 
HID Usage Tables 
10/28/2004 
Version 1.12 

KEY_A 0x04
KEY_B 0x05
KEY_C 0x06
KEY_D 0x07
KEY_E 0x08
KEY_F 0x09
KEY_G 0x0A
KEY_H 0x0B
KEY_I 0x0C
KEY_J 0x0D
KEY_K 0x0E
KEY_L 0x0F
KEY_M 0x10
KEY_N 0x11
KEY_O 0x12
KEY_P 0x13
KEY_Q 0x14
KEY_R 0x15
KEY_S 0x16
KEY_T 0x17
KEY_U 0x18
KEY_V 0x19
KEY_W 0x1A
KEY_X 0x1B
KEY_Y 0x1C
KEY_Z 0x1D
KEY_1 0x1E
KEY_2 0x1F
KEY_3 0x20
KEY_4 0x21
KEY_5 0x22
KEY_6 0x23
KEY_7 0x24
KEY_8 0x25
KEY_9 0x26
KEY_0 0x27
KEY_ENTER 0x28
KEY_ESC 0x29
KEY_BACKSPACE 0x2A)
KEY_TAB 0x2B	
KEY_SPACE 0x2C		
KEY_MINUS= 0x2D	
KEY_EQUAL 0x2E
KEY_LEFT_BRACE 0x2F	
KEY_RIGHT_BRACE 0x30	
KEY_BACKSLASH 0x31
KEY_NUMBER 0x32
KEY_SEMICOLON 0x33
KEY_QUOTE 0x34
KEY_TILDE 0x35
KEY_COMMA 0x36
KEY_PERIOD 0x37
KEY_SLASH 0x38
KEY_CAPS_LOCK 0x39
KEY_F1 0x3A
KEY_F2 0x3B
KEY_F3 0x3C
KEY_F4 0x3D
KEY_F5 0x3E
KEY_F6 0x3F
KEY_F7 0x40
KEY_F8 0x41
KEY_F9 0x42
KEY_F10 0x43
KEY_F11 0x44
KEY_F12 0x45
KEY_PRINTSCREEN 0x46		
KEY_SCROLL_LOCK 0x47		
KEY_PAUSE 0x48
KEY_INSERT 0x49	
KEY_HOME 0x4A
KEY_PAGE_UP 0x4B
KEY_DELETE 0x4C
KEY_END 0x4D
KEY_PAGE_DOWN 0x4E	
KEY_RIGHT 0x4F
KEY_LEFT 0x50
KEY_DOWN 0x51
KEY_UP 0x52
KEY_NUM_LOCK 0x53
KEYPAD_SLASH 0x54	
KEYPAD_ASTERIX 0x55	
KEYPAD_MINUS 0x56	
KEYPAD_PLUS 0x57	
KEYPAD_ENTER 0x58	
KEYPAD_1 0x59
KEYPAD_2 0x5A
KEYPAD_3 0x5B
KEYPAD_4 0x5C		
KEYPAD_5 0x5D		
KEYPAD_6 0x5E		
KEYPAD_7 0x5F		
KEYPAD_8 0x60		
KEYPAD_9 0x61		
KEYPAD_0 0x62			
KEYPAD_PERIOD 0x63
