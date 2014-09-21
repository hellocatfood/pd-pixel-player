# Pixel Player

Inspired by the work of [Neil Harbisson](http://eyeborg.wix.com/neil-harbisson) and the [Cyborg Foundation](http://eyeborg.wix.com/cyborg).

Tested on Ubuntu 14.04

## Dependencies
- Pure Data Extended

## Usage
- Create the GEM window	
- Click on the red button to load an image. Supported file types depend on your operating system, but generally jpg, gif and png file formats are supported
- Click on the green start button and the pixels will start to be read
- Drag the orange horizontal slider up to increase the master volume
- Drag the orange vertical slider up on each pixel player to control its volume
- Turn the knob to scale the pitch of the audio

## Extra
Increase the canvas size of the loadiamge.pd patch to expose its inlets and outlets. These inlets can be used with midi or other controllers. inlets_diagrram.png describes what each inlet is.

Uses code by guido for switching wave forms http://puredata.hurleur.com/sujet-8079-switching-between-oscillators