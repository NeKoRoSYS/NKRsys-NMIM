# NKRsys-MIH
NeKoRoSYS's Mobile Input Handling. An open-source project dedicated to providing mobile game developers a quick headstart on setting up mobile/touch control for their Unity game. This asset currently only supports Unity's New Input System package, but it can be easily back-ported so that it supports the old input system.

<br>

## Features
This project extends from the [on-screen controls](https://docs.unity3d.com/Packages/com.unity.inputsystem@0.9/manual/OnScreen.html) that Unity's Input System package have provided by default.
### Button
`ControlButton` is an extension of the [`On-Screen Button`](https://docs.unity3d.com/Packages/com.unity.inputsystem@0.9/manual/OnScreen.html#on-screen-buttons) component provided by the Input System package. It can have animated sprites and color fading!
### Joystick
`ControlStick` is a heavily-improved extension of the [`On-Screen Stick`](https://docs.unity3d.com/Packages/com.unity.inputsystem@0.9/manual/OnScreen.html#on-screen-sticks) component provided by the Input System package. It has a variety of configurable settings, and it can be used for several features that your game may already have, like player movement.
### Touchpad
`ControlPad` is a component that registers input if the touch made contact inside its rect bounds. It's not found in the Input System package by default as it is a custom implementation. It supports multitouch and can be configured and used for a variety of features you may plan on implementing to your project!
