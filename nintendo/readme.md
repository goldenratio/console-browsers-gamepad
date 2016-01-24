# New 3DS

Browser supports HTML5 canvas.

#### Key Events
The following buttons trigger the onkeydown and onkeyup events:

| Keycode        | Button|
| ------------- |:-------------:|
| 13 | A |
| 37 | Left Arrow key |
| 38 | Up Arrow key |
| 39 | Right Arrow key |
| 40 | Down Arrow key |

Other buttons do not trigger key events.
Touch events are supported on the secondary screen.

###### Related links:
1. https://3dbrew.org/wiki/Internet_Browser

---

# Wii U

Browser supports HTML5 canvas.

#### Key Events
The following buttons trigger the onkeydown and onkeyup events:

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
