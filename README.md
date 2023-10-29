# Roll A Ball

<html>
<img src="GitAssets/Art.jpg">
</html>

The creation of this game is based on understanding the basics of Unity; how to navigate the editor, create Scripts in C#, set up input using the Input System, and create a basic user interface. [Roll-a-Ball](https://learn.unity.com/project/roll-a-ball)

<html>
<img src="GitAssets/Unity.jpg">
</html>

> _Powered by Unity_

## Technologies Used

* _Github_
* _VSCode_
* _C#_
* _Unity_
* _.NET_
* _JSON_

<html>
<img src="GitAssets/RollABall.jpg">
</html>

<html>
<img src="GitAssets/Gameplay.jpg">
</html>

<html>
<img src="GitAssets/Score.jpg">
</html>

> Current game state as of _10/29/2023_

### Gameplay

**Player Controls**: The Player GameObject responds to player input by applying force. Physics interactions work as expected.

**Speed**: The Player's speed is currently optimal.

**Responsive Walls**: All walls in the game world are responsive to collisions, allowing for dynamic interactions as the Player navigates the play area.

**Risk of Falling**: Player can fall off the play area if they roll the ball towards a wall at full speed.

**PickUp Rotation**: PickUp GameObjects rotate smoothly.

**Interactive UI**: Player Score is displayed and incremented each time a PickUp is collected. If the Player wins, a custom 'You Win' rotation appears.  

### Work in Progress

* Customize play area further - (make more maze-like)

* Obstacle challenges - (add enemies / blockages in play area)

* Physics experimentation - (add jump feature / build play area vertically)

### ⚖️ License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Copyright (C) 2023 Jeremy Josol. All Rights Reserved.

```
MIT License

Copyright (c) 2023 Jeremy Josol.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
