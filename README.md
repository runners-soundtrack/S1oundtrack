# Runners S-1oundtrack

An unofficial phone companion app for the **Roland AIRA Compact S-1 Tweak Synth**. It turns your phone into a live display for the S-1 and adds guides, a recorder and a sound analyser. It installs like an app on Android and has an 8-bit athletics-track look.

**Not affiliated with, endorsed by or sponsored by Roland Corporation.** Roland, AIRA, S-1 and SH-101 are trademarks of Roland Corporation.

## What it does

- **Live display:** shows knob and pad changes from the S-1 as they happen, over USB MIDI.
- **Scope, spectrum and spectrogram:** watch the sound using the phone's audio input.
- **Pattern view:** see sequencer steps and patterns.
- **Rec:** record audio to WAV files stored on your phone.
- **Learn:** over 90 step-by-step guides for bass, leads, keys and pads, drums, soundscapes, patterns and SH-101 classics, including the 40 sample sounds from the SH-101 owner's manual converted to S-1 settings. Each knob has a live bar that follows the real knob, and turns green when you reach the target.
- **Match:** play a sound for 5 seconds (microphone, USB audio or an audio file) and get suggested S-1 settings to recreate it.

## Install on Android

1. Open the app's web address in **Chrome** on your phone.
2. Open the menu (three dots) and choose **Install app** or **Add to Home screen**.
3. Plug the S-1 into the phone with a USB-C cable.
4. On the S-1, turn AIRA Link off (menu item `A.LnK`), then power it off and on.
5. In the app, tap **Connect MIDI** and allow access.

After the first visit it works offline.

## Notes

- The SH-101 slider values were read by eye from the manual's diagrams, so they are starting points. Adjust by ear.
- The S-1 has one envelope shared by filter and amp, so SH-101 envelope settings are approximated.
- Match works best on a single instrument or drum hit in a quiet room. A full mix gives a rough guess.
- Works with Chrome on Android, and Chrome or Edge on a computer. iPhone and iPad are not supported, because Safari does not support Web MIDI.

## Hosting your own copy

The app is plain HTML, CSS and JavaScript with no build step. Upload the files to any https host (GitHub Pages, Netlify, Cloudflare Pages). The app must be served over https for MIDI, the microphone and installation to work.

## Fonts

Uses Press Start 2P and VT323, both free fonts under the SIL Open Font License.

## Author

Made by runners-soundtrack
