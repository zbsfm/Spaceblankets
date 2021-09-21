# Spaceblankets<img width="1177" alt="Screen Shot 2021-09-21 at 12 53 47" src="https://user-images.githubusercontent.com/56085339/134214239-6ce8da99-0685-436b-84c1-198b4497f3d7.png">
A jammable sample-based drum machine designed for mixer controllers, heavily inspired by Mylar Melodies.

Everything except the HOST-FX module is free - you can substitute that for any effect you like, or simply remove it.

**Prerequisites:**
- VCVRack v1.1.6
- Bogaudio library
- Bidoo library
- Orange Line library
- Valley library
- Lomas library

**Use:**
There are 5 drum channels, with 2 more easily added. Each channel has 4 controls: level, decay, pitch, and density. I'm using a Novation Launch Control XL - in my case, these controls are mapped to a channel fader and the corrosponding 3 potentiometers. In the case of the kick channel, these CCs are 41, 21, 29 and 13 respectively.

The kick, snare and hi-hat are 3 channels of Mutable Grids (here, Valley Topograph.) The open-hat channel is a manually programmed sequence (this channel's density control doesn't do anything.) The ride cymbal is a euclidean rhythm with length 32 - the density controls the "fill" parameter.

**TODO:**
