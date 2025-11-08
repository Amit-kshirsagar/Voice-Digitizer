# Voice Digitizer
Originally developed in 2020 as part of a Microprocessor and Interfacing Course; this repository contains the finalized and cleaned version for public release.
## Overview
The project digitizes a voice signal and reproduces it with user-defined modifications using a microprocessor. The output from the microphone is sampled and digitized by an 8-bit ADC at a rate of 1000 samples per second. The microphone output is pre-processed to provide a signal with an amplitude range of 0–5 V, and the digitized data is stored in RAM for further processing.

A 6-second segment of the voice signal is digitized and can be replayed with a delay when the Sound Replay switch is activated. The delay value (1–9) is entered using a keypad consisting of digits (0–9), a backspace, and an enter key. A seven-segment display shows the delay value entered by the user. During playback, the entered delay is applied between successive samples — for example, if the user enters a value of 5, a delay of 5 ms is introduced between adjacent samples.
