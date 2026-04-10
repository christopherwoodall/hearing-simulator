# Auditory Phenomena Simulator

Hey there. This is a lightweight, single-page web app built to simulate a few specific hearing and middle-ear phenomena using the native Web Audio API. 

Please keep in mind that hearing is incredibly subjective. This tool is meant to be an educational simulation, not a perfect 1:1 recreation of what everyone experiences just yet. It's simply a starting point to help explain these sensations to others.

### What it simulates

* **Wave-like Tinnitus:** A smooth 3000Hz tone that rhythmically fades in and out.
* **Constant High-Frequency Tone:** A pure 6000Hz sine wave (classic sensorineural tinnitus).
* **Muffled Talking:** Modulated, low-pass filtered noise to simulate hearing speech through a barrier like a wall or paper bag.
* **Tensor Tympani Rumble:** A brief, deep low-frequency thrum that simulates voluntarily flexing the "ear popping" muscle.

### How to use it

There are no external libraries or downloads needed. 

1. Save the code as an `index.html` file.
2. Open it in any web browser.
3. Click "Enable Audio & Start" (this is required by browsers to allow sound to play).

### Warning

This application generates high-frequency tones. Please turn your device volume down before starting to avoid ear strain. The sliders are intentionally set to very low volumes (1% to 3%) by default for your safety.