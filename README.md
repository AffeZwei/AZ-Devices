# AZ-Devices

# Grainflow Harmonizer
![Grainflow_Harmonizer](https://github.com/AffeZwei/AZ-Devices/assets/62151108/aa09ca17-b300-4903-9d74-b3ad8293e1df)

Takes incoming audio and granulates 5 streams, transposed in real-time. The harmonizer transposes at ca. third-tone intervals (about a third of a half-step - 33 cents) for unreal atmospheric harmonies.​ Made with Chrisopher Poovey's Grainflow. Ableton 10 or higher.
​
# Grainflow Stochastic 
![Grainflow_Stochastic](https://github.com/AffeZwei/AZ-Devices/assets/62151108/44474ad7-24d7-4ab3-90a0-ec8dc4c1dc7b)

Granulates incoming audio at a set grain size, but offers many possibilities for pitch change, density and rate of emission. Ableton 10+ for normal version, Ableton 11+ for multichanel version.
# There is a multi-channel version of Grainflow Stochastic which will automatically generate five extra tracks for five separate streams of granules. For this reason, it is only available for Ableton 11 and 12. 
Like the 2-channel version, it granulates incoming audio at a set grain size, but offers many possibilities for pitch change (including glissando), density and rate of emission. Made with Chrisopher Poovey's Grainflow. Ableton 11 or higher.
​ 
# Grainflow V-tap

![Grainflow_Vtap](https://github.com/AffeZwei/AZ-Devices/assets/62151108/4814f6f6-1037-4c10-b41f-f6be4ab6316a)

This can also be seen as a kind of delay effect, it is a simple live granulator with 5 channels, each having its own speed ranging from 0 to 5 seconds. There is no pitch transposition, unlike the Grainflow Harmonizer. ​ Made with Chrisopher Poovey's Grainflow. Ableton 10 or higher. 
 
# Az Polyvoice Live Granulator

![Polyvoice_granulator](https://github.com/AffeZwei/AZ-Devices/assets/62151108/2e797832-18df-4542-91d5-715bde79c863)

Granulates live incoming-audio with up to 24 voices. This one allows for minute control and modulation of grain size, rate of emission, pitch and position of grain. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.

# AZ Doppler-to-Midi Delay

![DOppler2midi](https://github.com/AffeZwei/AZ-Devices/assets/62151108/48a261f1-dcde-4e33-8c63-7ebb52a441bf)

This device can be used as a simple delay effect with variable delay time and feedback. Or the "Doppler Delay" can be switched on, which gives a rhythmic modulation of the delay time. This gives the illusion of a doppler effect: pitches shifting higher or lower according to your perspective. These changes of pitch are then translated into Midi notes which can be sent anywhere in or outside Ableton. Note that the midi is not reflecting the incoming audio pitch, but rather the pitch of the delay shifts. Can sync or decouple with Ableton playback. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 11 or higher. Tutorial/Demo: https://youtu.be/pStxcXckTvM
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

![RandomShapesB](https://github.com/AffeZwei/AZ-Devices/assets/62151108/19ebf1d1-2dc8-42bf-a8e7-ad792e9abcb1)
​
This LFO can produce a variety of shapes, from steps to curves to any combination thereof. The second LFO is interpolated at twice the speed of the first, so therefore produces shapes at twice the rate. It won't exactly reproduce the shape at twice the speed, but it will create more curves or steps, but always in relation to the first. The spline-6 offers an interpolation with a shift-register at 6 different points on the curve, so the shapes and steps will be a bit shallower. Each LFO can be individually smoothed. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.

# ​ AZ LorenzXYZA

![Lorenz](https://github.com/AffeZwei/AZ-Devices/assets/62151108/e2f142c4-212c-4773-b1a1-282a532b0bc2)

This is a simple device for modulating curves according to the Lorenz equation which produces random, undulating fluctuations. It has a "slow" feature for really subtle effects, as well as the possibility to produce bipolar signals, and personally I like to see the shapes at the same time as I am mapping. It outputs 4 shapes, the X, Y, and Z curves plus an average of all three. Portions of this device are based on gen~ patching found in "Generating Sound and organizing Time" (https://cycling74.com/books/go) copyright Gregory Taylor and Graham Wakefield. Ableton 10 or higher.

