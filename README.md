# WF-8 PRO Digital Mode Terminal
### Version 1.0 — Developed by Wyatt (KF8FQN)

WF-8 PRO is a fast, phase-continuous digital data mode designed to run seamlessly over HF, VHF, and UHF amateur radio bands. It features a built-in live waterfall display, narrow-band DSP tone tracking, and automatic transmitter loopback muting.

## How to Install and Run
1. Look at the right-hand side of this page under the **Releases** tab.
2. Download the compressed **`WF-8_Pro.zip`** application file.
3. Unzip the file on your computer and double-click the executable application icon to launch the visual interface terminal immediately (no Python installation required).

## Hardware Connection Setup
1. Connect a standard USB soundcard interface (like a **Digirig Mobile** or **SignaLink USB**) from your computer to your transceiver's data accessory port.
2. In your computer's system settings, change your default input and output sound devices to match your USB radio interface box.
3. Tune your radio to your target operating frequency and set the modulation mode to **USB** (Upper Sideband) or **USB-D / DATA**.
4. Turn off all speech compression, internal processors, and microphone pre-amps to keep the digital audio tones clear and un-distorted.

## Operating the Terminal
* **Serial Port Input**: Type your computer's USB port path into the configuration field (`/dev/tty.usbserial` on Mac or `COM3` on Windows) to enable automatic RTS/DTR PTT hardware transmitter keying.
* **Gain Adjustment**: Slide the RX Gain control bar up or down to cleanly bring weak signals into focus on your visual waterfall spectrum window.
* **Transmitting Data**: Type your communication text into the message window box and press **TX**. The application will drop the PTT lines, isolate your signal, and stream your digital mode data across the airwaves!
