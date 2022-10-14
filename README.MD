# DeforumKeyframer

## What this is
This is a macro for Davinci Resolve/Fusion to assist with creating keyframes for Deforum Stable Diffusion. You can view your keyframes on the timeline, making it easier to visualize your animation or synchronize to music and video.

## What this is NOT
This does not bring Stable Diffusion into Davinci Resolve. It simply generates a list of keyframe data that can be copied into Deforum Stable Diffusion.

## This is currently alpha software
It may not work well or even at all. Future releases may break your existing projects. Please do not use for serious work at this point in time.

## First release coming soon

## Prerequisites
* https://www.blackmagicdesign.com/products/davinciresolve/
* https://deforum.github.io/

## Installation

## How to use
First, make sure the FPS in your project settings and timeline settings are set to match the FPS that you will be using in Deforum. 
On the Resolve Edit page, create a solid, precompose it, then drop the DeforumKeyframer macro on it. You can also drop it directly on a video clip if you want.
You can now work with the plugin from either the Edit page or the Fusion page, whichever you prefer. 
You can use the controls on the effect's "controls" page to set keyframes. Please note that curves/easing will not transfer over to Deforum!
If you go to the "output" page and click the execute button, your keyframe data will populate into the various fields. You can copy and paste from these fields into the Deforum notebook.
