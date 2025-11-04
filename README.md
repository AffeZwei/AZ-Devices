# AZ-Devices

# AZ Crosscounter Audio Synth
Fully expanded view:
![CrossPMMidiFull](https://github.com/user-attachments/assets/920045c9-0be8-4060-b7ee-d8784488d2c8)
Read full manual here: https://docs.google.com/document/d/1zV0esc2ami-lVniTjiRCF9nk2YPZQcAY78aBvlTqNmM/edit?usp=drive_link

Crosscounter Audiosynth Quickstart -  Crosscounter Audiosynth is a monophonic, audio-following synthesizer, but can also receive simple, monophonic midi input. It is an audio device and can live on its own on an audio track or be used on a midi track along with other audio devices. 

Choose your input source: audio or midi (choosing midi will give you a drop-down menu for midi sources and channels)
experiment with the mods, indexes, filters, mod modes and (sub)harmonics until you get a sound that suits
turn on the envelope if you want to shape the sound. The parameters will vary depending on the source input (audio or midi)

Troubleshooting:
no sound? Try turning off the envelope, or adjusting the Onset Detection parameters (if your input source is audio). Is your audio source signal loud enough? This device might not respond to weak signals, or signals below 20hz. Check the Hi-Pass filter, is the threshold low enough? Check the Dry/Wet ratio as well.
pitch too unstable? If that’s not what you want, make sure “non-continuous” is selected and “Counterpoint” is turned off. Try the “Large” mode for Pitch Recognition. Turn the Mod Modes to “Fixed”. Bear in mind, a bit of wackiness is characteristic for this device.

This device will follow and pitch match whatever you are playing, singing, or sampling. However, it has the capability to switch to midi mode, where it will receive midi input from within Ableton or external hardware. This is useful if, for example, you want to have the synthesizer receive midi pitches from a sequencer for 8 bars, then switch to receiving pitch from live input for the next 8 bars. The dual sine-wave oscillators are cross phase modulated. In addition to the usual synthesis modulation parameters, this audiosynth offers additional harmonics and subharmonics, which can lend an organ-like character to the sound. An experimental feature is Counterpoint, which adds melodic variation to your incoming sound. Crosscounter Audiosynth was inspired by the patching found in "Generating Sound and Organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. 

# AZ Doppler-to-Midi
![Doppler2Midi](https://github.com/user-attachments/assets/0602b75d-f527-4667-86b8-f67dd25fe568)

Read the full manual: https://docs.google.com/document/d/1OVZs2Bpg1QWmK29EugjebsAtBEXeJjXBazQqJ8rFZcE/edit?usp=drive_link

Doppler-to-Midi Delay Quickstart: put this device on an audio track, activate the Doppler effect, and choose its rate according to the “Siren” parameters. If you want to send out the delayed pitches as midi, select Start Midi and choose your keyboard octave and other parameters. The midi from this device should be visible on any midi track, just select AZ Doppler-to-Midi as your midi source. This device will not take midi input, only send it out.

Troubleshooting:
Midi not responding? Maybe the audio signal and its delay are too noisy to detect a clear midi pitch, or the incoming audio signal is too weak. Or increase the “Doppler Amt”, intervals that are too small will not register as separate notes in midi.

This is an audio effect that delays incoming audio. Its delay can mimic the doppler effect heard in old-fashioned police siren sounds and take them to extremes in order to create or generate melodic material. The pitches from this effect can be converted to Midi information that can be received on any Midi-track within Ableton or to external hardware by using Ableton’s External Instrument object. AZ Doppler-to-Midi Delay was inspired by the patching found in "Generating Sound and Organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield.

# Spectral Freeze
![AZSpectralFreeze](https://github.com/user-attachments/assets/7b6d1d61-94f5-418c-99b5-bb64f1e3d0b4)

Put on an audio track to record incoming sound that can be frozen in time! You can scroll through the spectrograph (or automate, or modulate with an LFO) to explore the sound at different time frames. Recording can be manually toggled, or you can set the device to start recording with onset detection. 
 
# Az Polyvoice Live Granulator

![Polyvoice_granulator](https://github.com/AffeZwei/AZ-Devices/assets/62151108/2e797832-18df-4542-91d5-715bde79c863)

Granulates live incoming-audio with up to 24 voices. This one allows for minute control and modulation of grain size, rate of emission, pitch and position of grain. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.
​ 
# AZ Modulating Decay

![Modulating_Decay](https://github.com/AffeZwei/AZ-Devices/assets/62151108/6365c0c1-5a12-47a5-a404-4d9f82e43189)

This device can be used as a simple delay effect with variable delay and decay times. A built-in LFO can be set to modulate the delay and/or the decay times individually. Extra-slow and randomization are selectable feature of the built-in LFO. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.

# LFOs
# AZ Random Steps and Shapes LFOs with Trigger for Midi

![RandomShapesB](https://github.com/AffeZwei/AZ-Devices/assets/62151108/21993275-7be4-4747-a2d8-19cfdcc24e8a)

Produces two sets of shapes connected to a single frequency (rate). The first shape is a customizable shape (stable or random). The second LFO is connected by frequency (rate) to the first, but produces random shapes that are interpolated at twice the speed of the first. It won't exactly reproduce the shape at twice the speed, but it will create twice as many shapes. One feature of this LFO is that you can toggle or automate the switch of beat-synchronization to Hz- frequency. These features are not synced like in the LFOi. Another special feature of this LFO is that from the spikes that are produced by the curves, midi may be triggered. Note these triggers are not on the beat, but are related to the curves or steps of the LFO. They can be regular, forming a kind of polyrhythm, or with the random dial up, can produce random triggers. These Midi triggers can be sent anywhere in or out of Ableton. They can be synced or decoupled from playback. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 11 or higher. Tutorial/Demo: https://youtu.be/d_ymAWpafPI

# AZ Stepped and Vactrol-lag LFOs with Trigger for Midi

![VactrolB](https://github.com/AffeZwei/AZ-Devices/assets/62151108/a95706e6-1979-49fb-a629-ff1db1c999c4)

This LFO produces a pair of shapes: one stepped and the other with the same steps smoothed in such a way that emulates analog lag-motion. This is great for generating envelopes or mixing smooth and edgy responses of parameter control. The vactrol refers to a particular lag behavior when opening and shutting an analog current. The rise and fall times can be stipulated but have an exponential response due to a lowpass filter. One feature of this LFO is that you can toggle or automate the switch of beat-synchronization to Hz- frequency. These features are not synced like in the LFOi. Another special feature of this LFO is that from the steps, midi may be triggered. These Midi triggers can be sent anywhere in or out of Ableton. They can be synced or decoupled from playback. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 11 or higher. Tutorial/Demo: https://youtu.be/0OrsI0dEq5A

#  AZ Twin Random Steps and Shapes LFOs

![AZ_Twin_Shaped_LFOs](https://github.com/AffeZwei/AZ-Devices/assets/62151108/200cb9ff-5341-40ae-92c1-70390ba66ccf)
​
This LFO can produce a variety of shapes, from steps to curves to any combination thereof. The second LFO is interpolated at twice the speed of the first, so therefore produces shapes at twice the rate. It won't exactly reproduce the shape at twice the speed, but it will create more curves or steps, but always in relation to the first. The spline-6 offers an interpolation with a shift-register at 6 different points on the curve, so the shapes and steps will be a bit shallower. Each LFO can be individually smoothed. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.

# ​ AZ LorenzXYZA

![Lorenz](https://github.com/AffeZwei/AZ-Devices/assets/62151108/e2f142c4-212c-4773-b1a1-282a532b0bc2)

This is a simple device for modulating curves according to the Lorenz equation which produces random, undulating fluctuations. It has a "slow" feature for really subtle effects, as well as the possibility to produce bipolar signals, and personally I like to see the shapes at the same time as I am mapping. It outputs 4 shapes, the X, Y, and Z curves plus an average of all three. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.

