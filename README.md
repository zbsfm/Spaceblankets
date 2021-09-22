# Spaceblankets <img width="1042" alt="Screen Shot 2021-09-21 at 21 14 21" src="https://user-images.githubusercontent.com/56085339/134268231-0dbe1eef-dc0b-4a32-833c-e75827d7601e.png">

A jammable sample-based drum machine designed for mixer controllers, heavily inspired by Mylar Melodies.

Everything except the HOST-FX module is free - you can substitute that for any effect you like, or simply remove it.

**Prerequisites:**
- VCVRack v1.1.6
- Bogaudio library
- Vult free library
- Valley library
- Lomas library

**Use:**
6 drum channels, with 4 parameters each, plus a master channel, also with 4 parameters.
- CHANNEL 1: Plaits' analog kick model. Parameters: level, decay, pitch, Grids channel 1 density.
- CHANNEL 2: Plaits' analog snare model, processed by Vult Wolv. Parameters: level, decay, pitch, Grids channel 2 density.
- CHANNEL 3: Plaits' analog hi-hat model. Parameters: level, decay, pitch, Grids channel 3 density.
- Channel 4: 909 open hat sample. Parameters: level, decay, pitch, Euclidean density (length 8)
- CHANNEL 5: 909 crash sample. Parameters: level, decay, pitch, Euclidean density (length 32)
- CHANNEL 6: Vult Trummor 2 tom. Parameters: level, decay, pitch, Euclidean density (length 32)
