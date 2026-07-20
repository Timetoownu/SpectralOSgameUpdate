# SpectralOSgameUpdate
# 🚀 SpectralOS v0.9.1 Update

Welcome to **SpectralOS v0.9.1**! 🎉 This update brings a massive leap forward for our 2D Replay Viewer, adding gorgeous new visuals, live match animations, and squashing several bugs. 

Best of all, we've completely stripped out the legacy AI tracking engine, meaning SpectralOS is now lightning-fast and the installation size is nearly 10x smaller! 📉 *(Dropped from ~3.7 GB down to under 400 MB!)*

### ✨ New Features
- 🎨 **Stunning Replay Visuals:** The 2D replay viewer now features a custom visual field, highly-detailed car sprites, and the actual ball from the game.
- ⚡ **Boost Pads & VFX:** Big and small boost pads are now fully rendered on the field! You'll also see a dynamic thruster flame trailing behind cars when they hit the boost.
- 🎬 **Live Match Animations:** The viewer now reacts to the game! Watch for explosive "GOAL!" graphics, "SAVE!" and "EPIC SAVE!" pop-ups, and chat bubbles like "WHAT A SAVE LOL" appearing right over the players who score. Oh, and everyone throws out a synchronized "GGs" when the match ends!
- 📏 **Interactive Sizing:** New sidebar sliders let you adjust the size of the cars and the ball on the fly to match your preference.

### 📈 Improvements
- 🏷️ **Better Replay Names:** The replay list now shows human-readable names with the mode and date (e.g. "3v3 7/19 7:15 pm") instead of those long, confusing ID numbers.
- 🖥️ **Upgraded Viewer Layout:** The 2D canvas size was increased to 800x640, stretching the field out nicely while fitting perfectly on your screen without scrolling.
- 🔵🟠 **Team Glows:** Cars now emit a glowing aura matching their team color (Blue or Orange) so you can instantly tell who is who.
- 📐 **Perfect Alignments:** Car sprites have been re-calibrated so they perfectly face the ball during kickoff and accurately trace their velocity vector.
- 🏎️💨 **Lightning Fast & Lightweight:** We've completely ripped out the old YOLO visual engine! SpectralOS is now driven entirely by blazing-fast native telemetry. **As a result, the installed application footprint has plummeted from a massive ~3.7 GB down to just under 400 MB!**

### 🐛 Bug Fixes
- 🔧 Fixed an annoying bug in the replay viewer where cars would randomly swap team colors mid-match due to engine identifier recycling.
- 🔌 Fixed an issue where the replay list sometimes failed to load if the underlying connection wasn't fully initialized.
