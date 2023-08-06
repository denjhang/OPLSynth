# OPL3 synthetic real instrument experiment
 I spent a lot of time experimenting with the OPL3 Bank Editor, starting from the DMXOPL3 sound bank and gradually approaching the sound of a real instrument. To make the 2x2op sound of OPL3 close to the sound of real instruments, in addition to repeated experiments, it also requires perceptual knowledge of OPL3 FM synthesis. At present, I am used to using OPL3 to model the sound of musical instruments. Of course, all this is done in the brain. I don't use FFT software to analyze the sound, I just use my ears and brain.  
For DMXOPL3, only a small amount of modification is needed to make the instrument sound more realistic and "high-fidelity", but this requires a brain capable of sound structure 🧠.  
Yamaha FM synthesis made my description of sound more concrete, and OPL3 synthesis brought a new kind of thinking. So much so that when I hear any sound, I will use "OPL3 thinking" to think about how such a sound is composed.  
Through a lot of experiments, the FM synthesis parameters closest to real instruments can be found by chance. I think this is suitable for artificial intelligence to solve. 
I currently have a perceptual understanding of OPL3 sound synthesis, and I have roughly figured out what effects certain parameters will bring through exploration.  
In fact, many of my sounds here start from DMXOPL3.  
OPL3 can use a variety of waveforms, 2x2op mode, which is easier to understand than the pure sine wave synthesized OPM, OPN series.  
Changing the waveform is more significant to the sound than changing the algorithm.  
I actually recently made a realistic solo violin sound, but that requires an external reverb to achieve a good effect.  
For familiar instruments, I will deconstruct these sounds in my brain, mainly the overtones of the instrument, and approach the sound in memory through constant experiments.  

https://www.youtube.com/watch?v=9-6SGzon37U  
https://www.youtube.com/watch?v=9-6SGzon37U  
https://www.youtube.com/watch?v=7j9nBKrJ8i4  

At present, I have achieved high fidelity on the two instruments of Harpsichord and Accordion, and I have also made variant sounds of many instruments to be closer to real instruments. For the piano sound, it currently sounds more like a synthesized sound.  
These OPL3 instruments feature "native FM reverb", you don't need to add any post-processing DSP reverb to hear crisp instrument sound and moderate reverb.
These are all music in VGM format, you can play them on MegaGRRL (OPL3) without any problem  
I have some newly made OPL3 music packs, which are the original OPL3 instruments I adjusted by myself, which can subvert many people's perception of the sound of OPL3 to some extent.😅  

Using the FM-FM algorithm in the 2x2op mode of OPL3 seems to be four operators in series, which seems abstract, but when adjusting the parameters of these four operators, these four operators can be understood as four groups of overtones, When adjusting the parameters, please feel the change of the overtone of the sound with your heart.  
For Yamaha FM synthesis, parameters such as ADSR just adjust the "outer shape" of the sound, for 2x2op or 2op, you can make these four operators into 4 independent sounds, but in some magical combination way to superimpose into one sound. In fact, a real instrument sound also has many overtones, and these overtones change the frequency and volume all the time. In FM synthesis, you can use multiple operators to "superpose" the sound you want. ADSR determines the "movement" of the sound produced by each operator, such as when it appears, volume change, duration, etc., just like four stage actors dancing together, ADSR is their script.  
However, changing the three parameters of octave, waveform, and algorithm will directly determine the "inner shape" of the sound. These three parameters will greatly change the type of sound, such as from piano to guitar, you only need to use 1 octave and 3-octave combination. If you want the sound of harpsichord, you need to use half sine wave and 1-1/1-2/octave combination, changing the waveform is an exclusive function of the OPL series, which provides a difference from OPM, OPN and the like just by adjusting Algorithms to change the sound. Changing the waveform is a way to dramatically change the sound. If you need harsh sounds like bells, you need to adjust the octave above 10.  
For beginners, I recommend starting with 2op OPLL or OPL2, because 2op compositing is more intuitive and straightforward. You can try the multiplier combination I mentioned above, then you can understand.  
