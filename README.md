# RAW SAS-4

**Sound Art Studio, version 4**

RAW SAS-4 is my browser-based sound art studio for layering generative textures with field recordings. Built by Loosetriggers (Alan Raw) as part of my Creative Practice MA Project.

Live at: https://misterraw.github.io/raw-sas-4/

## Origins

RAW SAS-4 grew from GNOME (Generative Nexus for Open Musical Exploration), which itself grew from RAW SAS-1 (Sound Art Studio One). I started RAW SAS-1 in 2026 after a Make Happen Institute Learning Lab session inspired me to experiment. That first version was very basic: nine generator layers, a sample player and a recorder.

During my MA Creative Practice at the Make Happen Institute I'm developing this software in the wild, adding elements based on feedback and user experience. GNOME remains online at https://misterraw.github.io/gnome/ for those already using it.

## Design notes

- **Black and red, on purpose.** The colour scheme preserves night vision, so it can be operated backstage and in darkened installation spaces without dazzling the operator.
- **Runs in a browser.** No install, so it is easy to deploy on any machine instantly. Works on desktop and mobile, including iOS.
- **Soundscape layers.** The generators are grouped by the three layers of soundscape ecology: Geophony (Texture, Wind, Waves), Biophony (Birds, Insects, plus field recordings on the sample players) and Anthrophony (Drone, Tones, Rumble, Arpeggio, Pulse, Modem, Static, Oscillators, Machine, Construction).

## Changelog

### v4: RAW SAS-4 (November 2026)

- Renamed from GNOME to RAW SAS-4, at a new address.
- Records 16-bit PCM WAV.
- New Birds generator, modelled on Humber and Yorkshire species: curlew, redshank, oystercatcher, skylark and blackbird, with a distant bird of the same species that sometimes answers.
- New Insects generator, modelled on species found in Yorkshire: common field grasshopper, meadow grasshopper and Roesel's bush-cricket.
- New Machine generator: industrial cycle of marching thud, compactor and clank over a transformer hum, all tied to the UK grid's 50 Hz (transformers hum at 100 Hz, twice the mains frequency; the clank is tuned to 50 Hz).
- New Construction generator: a building site by a busy road, with pile driving, jackhammer and car horns (two clashing tones near 400 and 500 Hz, as most car horns are).
- New Wind generator: gusting air with a faint whistle. New Waves generator: a low wash with waves that swell, break and drain away.
- Generators regrouped into the three layers of soundscape ecology: Geophony, Biophony and Anthrophony.
- Net Gain slider: one control from degradation to net gain. A switch sets whether it moves just Birds, Insects, Machine and Construction, or every generator to a preset blend. Construction only comes in over the last quarter towards degradation.

### v0.2: GNOME (Pushed to GitHub Pages October 3rd 2026, MA Action 1)

- Added minor keys.
- Pushed with sharable link for feedback.

### v0.2: GNOME (started 29 September 2026, MA Action 1)

- Renamed from RAW SAS-1 to GNOME
- Four sample players now (was one, then made it two after beta feedback)
- Sound bank: preloading field recordings selectable from each player from my own collection.
- Feedback prompt for the MA cohort on the player page.

### v0.1: RAW SAS-1 (May 2026)

- Added speed control and volume sliders like a DJ mixer.
- Added stereo panning, BPM detection.
- Added recorder.
- Nine generator layers, sample player.
- Built after a Make Happen Learning Lab session, as an experimental work station.
