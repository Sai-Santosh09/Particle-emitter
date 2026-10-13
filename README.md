# particle emitter

A HTML interactive particle emitter. It combines a Web Audio API Theremin synth with a 2D canvas particle system.

## how to use it

Open `dist/uri.txt` and copy the text and paste it in any browswer:
- **Move cursor/finger:** Controls pitch (X-axis) and volume (Y-axis).
- **Click/tap:** Triggers a particle burst!

*Note: You need to click once on the website to start the audio.*

## how it works

- **Web Audio API:** Dual synth oscillators (sine + triangle sub-octave) through a lowpass filter.
- **Canvas:** 60fps particle motion and fading light trails.

## building

No build step needed just Run `dist/uri.txt` in any browser directly.
