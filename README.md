# Amalgamated Harmonics

## Scale Quantiser

Scared by the anarchy of unconstrained tone? Want to come back to that familiar octave of your youth? Here at Amalgamated Harmonics, our engineers and scientists provide the best possible set of semitones, fresh from the laboratory. 

* V/OCT: Input signal
* KEY: Root note of the scale
* SCALE: In order of appearance:
	* Chromatic,
	* Ionian a.k.a. Major
	* Dorian
	* Phrygian
	* Lydian
	* Mixolydian
	* Aeolian a.k.a. (Natural) Minor
	* Locrian 
	* Major Pentonic 
	* Minor Pentatonic
	* Harmonic Minor
	* Blues
* OUT: Quantised note
* Top row of outputs: Gates triggered from the scale degree of the note quantised

### Notes

These modules are primarily intended as a vehicle for me to learn how to create modules for VCV Rack.   

After watching a cool video from KlirrFaktor, I set out to build a scale based quantiser as there did not seem to be one around and this was a great opportuntity to learn how to build mmodules. I did not spot Jeremy Wentworth's module in development, but wasn't going to let redundancy get in the way of good idea. I thought I'd at least add something (scale degree-based gates), that may or may not be usedful for someone.  

### Credits and Thanks

* Jeremy Wentworth for the core quantisation code. I broke the code down a bit to understand was was going on and fixed a few things which seemed to be broken (at least as far as I could work out). 
* The KlirrFaktor for his great video on building a sequencer: https://www.youtube.com/watch?v=RFyC4II1kRw which used a quantiser with a fixed scale  