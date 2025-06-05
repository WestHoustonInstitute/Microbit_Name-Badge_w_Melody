# Microbit Name-Badge with Melody

This repository will:
1. Help you **get started** with entry‑level micro:bit programming by building an interactive digital name badge.
2. Demonstrate how to add **custom melodies** and control sound playback with the micro:bit’s buttons.
3. Provide clear, step‑by‑step instructions so you can **customise** the badge text, tune, and behaviour using Microsoft MakeCode.

---

# What do you need for this project?

* 1× micro:bit (V1 or V2)
* 1× micro:bit battery pack (2 × AAA)
* 1× USB‑C (or micro‑USB) cable
* A computer with internet access

<img src="https://github.com/user-attachments/assets/75cfca30-1a0a-4230-8a99-a390e0032995" alt="Required hardware" width="300" height="300">

---

# Step 1 – Flash the Name‑Badge code

1. Download the compiled hex file for the project → **[name‑badge‑with‑melody.hex](Software_Setup/microbit-Name-badge.hex)**.
2. Open the file at <https://makecode.microbit.org/#> (drag‑and‑drop or use *Import → Import File*).
3. Personalise the **`show string`** block with your name.
4. Connect the micro:bit via USB and click **Download** to flash the code.
5. Disconnect USB and power the board with the battery pack.

> The badge will now scroll your name on the LED display in a continuous loop.

---

# Step 2 – Play and customise melodies

| Button | Behaviour |
| ------ | ---------- |
| **A** | Plays your **custom melody** (defined in the `melody` variable). |
| **B** | Plays a **built‑in micro:bit tune** (e.g. *Jump Up*). |
| **A + B** | **Stops** all sounds immediately. |

### Editing the melody

* In MakeCode, open the **`music.melody`** block.
* Click the musical note icons to compose a new tune or paste a Melody String such as `C5:1 G4:1 A4:2`.
* Press **Download** again to flash the updated file.

---

# Step 3 – Next steps

* Try adding a **gesture** event (e.g. `shake`) to trigger a sound effect.
* Experiment with different text—add your role or fun emojis like `☺` and `♥`.
* Change the *tempo* with `music.setTempo(bpm)` for faster or slower playback.
* Share your remix by committing the `.hex` file or the MakeCode URL to this repository.

---

<img src="https://github.com/user-attachments/assets/059c55b1-74da-473b-9483-48e882b88874" alt="Finished badge demo" width="300" height="300">

*Inspired by the official [micro:bit Name Badge lesson](https://microbit.org/teach/lessons/name-badge/) – now with music!*
