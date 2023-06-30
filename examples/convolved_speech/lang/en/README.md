# Convolved speech

<p align="center">
  <span>🇬🇧 English</span> |
  <a href="https://github.com/Jerboas86/astrone-feedback/tree/master/examples/pitch_measure">🇫🇷 Français</a>
</p>

## Description

An audio file is played in an acoustical space. The acoustical space is represented by an impulse response.\
You can control:

- The sound level of the narrow-band noise with the `Volume` slider.

You can find impulse responses records from many places, and open source.\
the impulse response `church_ir.wav` used in this example comes from a site maintained by the university of York ([openair](https://www.openair.hosted.york.ac.uk/)).

The narrow band noise needs to be produced at a confortable level. The frequency needs to be adjusted to the reference signal.
The widening of the noise pass band increase the spectral richness.

## Usage

- Dowload the file `convolved_speech.astrone` in the parent folder
- Dowload the audio file `monolog.mp3` in the accelerated_speech folder
- Import this file in the [playground](https://www.astrone.app/playground)
- Add the audio file `church_ir.wav` in the buffer of `Convolver` node
- And Add the audio file `monolog.mp3` in the playlist of `AudioPlayer` node
