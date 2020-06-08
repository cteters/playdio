# playdio
A sandbox program to test a variety of digital audio effects

## Project description

As of the current build, this project includes,<br />
&nbsp;&nbsp;&nbsp; An electronic keyboard<br />
&nbsp;&nbsp;&nbsp; A synthesizer for generating sine waves<br />
&nbsp;&nbsp;&nbsp; A synthesizer for generating sawtooth waves<br />
&nbsp;&nbsp;&nbsp; An audio effect for generating delays<br />
&nbsp;&nbsp;&nbsp; A function to blend 2 audio samples<br />
&nbsp;&nbsp;&nbsp; A function to link 2 audio samples<br />

## How the project has come along:

A considerable amount of the project development time was invested toward learning about and designing a functional gui. We didn’t deliver as many audio functions as we would have liked to, but the visual interface does add a nice touch. Having it in place provide for a great foundation for any future project ideas and a pretty handy thing to know how to code in general.

## Areas to consider for future innovation:

Keyboard ideas:<br />
&nbsp;&nbsp;&nbsp; Add a few tone options<br />
&nbsp;&nbsp;&nbsp; Add a couple rhythm options<br />
&nbsp;&nbsp;&nbsp; Add a function for octave adjustments<br />
&nbsp;&nbsp;&nbsp; Add an option to record<br />
<br />

Audio converter ideas:<br />
&nbsp;&nbsp;&nbsp; Sample rate conversion<br />
&nbsp;&nbsp;&nbsp; Compress a signal's dynamic range<br />
<br />

Digital effect ideas:<br />
&nbsp;&nbsp;&nbsp; Convolution a reverberation effect<br />
&nbsp;&nbsp;&nbsp; Square synthesizer wave generator<br />
&nbsp;&nbsp;&nbsp; ADSR envelope generator<br />
&nbsp;&nbsp;&nbsp; Reverb effect<br />
&nbsp;&nbsp;&nbsp; Cutoff and resonance filter<br />

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install

```bash
pip install scipy
pip install numpy
pip install wave
pip install playsound
pip install coverage
pip install simpleaudio
```
If playsound doesn't initially work try installing gstreamer with,
```
sudo apt-get install gstreamer-1.0
```

The current build can be accessed through terminal via,

```
python3 main.py
```

# Contributors

Christopher Teters (cteters@pdx.edu),
Conor Dunlap (conor4@pdx.edu)
