# heavylib
Library of [Heavy](https://enzienaudio.com) compatible abstractions.

See the -help.pd patches for more information on each object.

Synthesis
---
`[hv.blepsaw]` - Band-limited PolyBlep sawtooth signal generator. [_more info_](https://github.com/cfloisand/pd-polyblep/blob/master/Source/polyblep~.c)

`[hv.pinknoise]` - Cheapish pinknoise generator. [_more info_](http://www.firstpr.com.au/dsp/pink-noise/)

`[hv.vline]` - Envelope generator, replacement for Pd's [vline~] object.

Processing
---

### Dynamics

`[hv.compressor]` - Compressor unit with Threshold and Ratio parameters. (Attack/Release is fixed at 40ms)

`[hv.compressor2]` - Stereo version of `[hv.compressor]`.

`[hv.envfollow]` - Cheap envelope follower.

### Effects

`[hv.comb]` - Comb filter effect unit.

`[hv.flanger]` - Flange effect unit.

`[hv.flanger2]` - Stereo version of `[hv.flanger]`.

`[hv.freqshift]` - Frequency shifter effect unit.

`[hv.reverb]` - Simple reverb unit.

### Filtering

`[hv.filter allpass]` - Allpass filter with Q control (Biquad).

`[hv.filter lowpass]` - Lowpass filter with Q control (Biquad).

`[hv.filter highpass]` - Highpass filter with Q control (Biquad).

`[hv.filter bandpass1]` - Bandpass filter with Q control, peak gain = Q (Biquad).

`[hv.filter bandpass2]` - Bandpass filter with Q control, constant 0dB peak gain (Biquad).

`[hv.filter notch]` - Notch filter with Q control (Biquad)

`[hv.filter.gain peak]` - Peaking filter with Frequency, Q and Gain parameters (Biquad).

`[hv.filter.gain lowshelf]` - Low shelving filter with Frequency, Q and Gain parameters (Biquad).

`[hv.filter.gain highshelf]` - High shelving filter with Frequency, Q and Gain parameters (Biquad).

Math Operations
---
`[hv.tanh]` - Static non-linear waveshaper.

`[hv.gt]` - Signal-rate greater than ( > ).

`[hv.gte]` - Signal-rate greater than or equal to ( >= ).

`[hv.lt]` - Signal-rate less than ( < ).

`[hv.lte]` - Signal-rate less than or equal to ( <= ).

Logic
---

`[hv.dispatch]` - Utility for organising parameter interfaces to other abstractions.

`[hv.drunk]` - Randomised walk number generator.
