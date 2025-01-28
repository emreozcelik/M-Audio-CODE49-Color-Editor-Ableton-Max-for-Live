<p align="center">
  <img src="/preview.jpg" width="720">
</p>

# M-Audio CODE49 Color Editor (Ableton - Max for Live)

### Overview:

This plugin allows editing the Pad and Button colors of the M-Audio CODE49 MIDI keyboard directly within Ableton. Built using MAX for Live, it integrates with Ableton's interface. Additionally, the plugin can be customized or adapted for use with other devices or for educational purposes.

**Live Version Used:** 10.0.1<br/>
**Max Version Used:** 8

---

### Requirements:

1) Ensure that your device is up to date, as older firmwares had MIDI communication bug.<br/>
https://m-audio.com/support/drivers

2) Ensure that Port 1 Input and Port 1 Output are activated in Ableton’s settings, and not set or enabled as a Control device.

---

### Instructions:

1) Drag and drop the .amxd file into Ableton, or place it in a folder accessible through Ableton.
2) Create a new MIDI track.
3) Set the track’s input to 'All Ins' or 'Code 49' (Port 1).
4) Set the track’s output to 'Code 49' (Port 1).
5) Enable Arm Recording on the MIDI track to receive signals from the device.
6) Add the CODE49 Color Editor to the track and perform a Memory Dump on the device. <br/>(Edit > Mem. Dump > Enter)
7) After applying, reload the preset on the device by switching forwards and backwards.

---

### Schema:

The schema is shown in the image below, providing an overview of the setup. The .amxd file can be edited directly within Ableton's MAX for Live, and the code is also included as a JSON file.

<p align="center">
  <img src="/schema.jpg" width="560">
</p>

For a deeper understanding of the SysEx procedure and how it interacts with the device, refer to the following link:

https://github.com/emreozcelik/M-Audio-CODE-MIDI-Keyboard-SysEx-Reverse-Engineering
