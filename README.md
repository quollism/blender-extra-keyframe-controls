# blender-useful-animation-tools-from-279

## Notice

*This plugin is unsupported as of 14 June 2018 because there's not really any need for it anymore. Also the toolbar UI gets in its way so it's barely usable. Use the Keying dropdown and record button on the Timeline toolbar instead.*

## Features 

A little add-on which reinstated Blender 2.79's animation-specific tools to Blender 2.8's Timeline and 3D View toolbar, plus a bit extra.

This add-on is not intended as a criticism of the 2.8 UI clean-up! The clean-up is a Very Good Thing to make Blender 2.8 less visually noisy and to prioritise which tools get screen space. However I found these tools useful to have where they were in 2.79, so I'm reinstating them as an add-on.

The useful tools also include the Keyframe Interpolation setting which is usually tucked away in User Preferences. This is helpful for switching interpolation modes when adding new animation channels. New keyframes on an _existing_ channel have the same interpolation mode as the previous keyframe on that channel, so the Keyframe Interpolation setting has no effect there.

## Usage

* Download the .py file
* Start Blender 2.8
* Change one of your windows to the User Preferences editor
* Click Install Add-On From File
* Browse to where you downloaded the .py file
* Select it
* Ensure the add-on is showing and tick its little box
* Click Save User Settings

If you already have a Timeline window open, the next time you mouse over that window the controls should magically reappear. Yay!

## Limitations

Blender 2.8 was in the middle of heavy development when this script was written. The toolbar layout changed enough to make this script both unnecessary and unusable enough to call it a day.