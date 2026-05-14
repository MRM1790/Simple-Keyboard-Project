# Simple-Keyboard-Project
DIY keyboard from scratch for school projects.
This block diagram displays what parts are considered using in this project. As the following goes, Key switches (Kailh or cherry MX) it is possible to use Choc switches (boxed switches) but for now we are sticking to kailh or cherry mx switches. We are using 3 pin switches for this project. For proof of concept, we have thought about doing a cardboard box with a "WSAD" arrow keys for now. Eventually we will do a full 74 keyboard switches. Microcontroller we plan on using is an Arduino pro micro controller that has a USB C connection for the wire to be connected to the computer or laptop. The goal is to have a keyboard matrix which are key switches that have diodes and wires soldered on each other to create columns and rows to utilize more of the pins that are on the Arduino Pro Microcontroller.  Once that is set up then the user should be able to press a input on the proof of concept model and should display either numbers or letters to the output display monitor.

ATTENTION:
  For the BOM files, designators, and CPL we recommended ordering through JLC PCB since it is configured in their version of excel and ordering process.
  QMK Toolbox will be needed to upload the code in the circuit board which a link will be provided here
  https://qmk.fm/toolbox

ATTENTION: THE SOFTWARE FOR THE KEYBOARD IS LABELED AS BOTH "KEYBOARD.JSON" AND "KEYMAP C" AND THE MAIN THING THAT YOU WILL NEED IS THE FILE THAT SAYS "jam61_default.HEX" then you will plug that into the QMK Toolbox application, and press the reset button on the circuit board in order to flash it. Once you hit the reset button in Toolbox hit flash prompt and the Hex file will go into the circuit.
