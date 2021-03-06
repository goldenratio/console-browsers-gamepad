# Nintendo Switch

Web browser not supported at the moment.

---

# New 3DS

##### HTML5 Gamepad API : Not Supported

#### Key Events
The following buttons trigger the onkeydown, onkeypress  and onkeyup events:

| Keycode        | Button|
| ------------- |:-------------:|
| 13 | A |
| 37 | Left Arrow key |
| 38 | Up Arrow key |
| 39 | Right Arrow key |
| 40 | Down Arrow key |


1. Other buttons do not trigger key events.
2. Analog stick does not triggger any event. It scrolls page.
3. Button 'B' - back button. Cannot be blocked
4. Button 'Y' and 'X' - Zoom in/out. Cannot be blocked
5. R - Browser history forward
6. L - Browser history backward
7. ZR / LR - Opens tabs list
8. Touch events are supported on the bottom screen.

###### Related links:
1. https://3dbrew.org/wiki/Internet_Browser

---

# Wii U

##### HTML5 Gamepad API : Not Supported

#### Key Events
The following buttons trigger the onkeydown, onkeypress  and onkeyup events:

| Keycode        | Button|
| ------------- |:-------------:|
| 13 | A |
| 37 | Left Arrow key |
| 38 | Up Arrow key |
| 39 | Right Arrow key |
| 40 | Down Arrow key |

Also you can pool `window.wiiu.gamepad` to read the current state of the primary GamePad.
With `window.wiiu.gamepad` we can read Accelerometer, Gyroscope, Angle and Orientation values.
 
###### Related links:

1. https://www.nintendo.com/wiiu/built-in-software/browser-specs/extended-functionality/ 
2. `window.wiiu.gamepad` http://wiiubrew.org/wiki/Internet_Browser#wiiu.gamepad
3. Sample page to obtain values from the Wii U GamePad - http://www.nintendo.com/wiiu/built-in-software/browser-specs/sample/
4. http://www.lostdecadegames.com/wii-u-browser/
