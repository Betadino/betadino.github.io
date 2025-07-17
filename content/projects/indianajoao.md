+++
date = "2024-11-30T22:51:40Z"
title = 'tic80 + raspberry pico project'
image = '/img/INDIANAJOAO.png'
+++
### Indiana João

**Platform:** TIC-80


**Description:**
Indiana João is a game I developed with my fellow students, featuring a unique control mechanism utilizing a Raspberry Pico and advanced programming techniques. The project highlights the integration of the C/C++ SDK, Fourier Fast Transform, and the TinyUSB library to create innovative audio-based controls.


**Work**

My part on the project was the concept of the game and the implementation of a HID through the Raspberry Pico with the use of the C/C++ SDK, Fourier Fast Transform, and the TinyUSB library to implement controls that requires the player to sing a certain note to do an action.

### Check it out [here](https://tic80.com/play?cart=4145).


- **Raspberry Pico:** Utilized as the main micro controller that behaves as a composite HID to process audio input where the algorithm analyzes sound and sends the output signals to the main pc as keyboard inputs.
- **Sound wave analysis with Fourier Fast Transform (FFT):** I utilized a library that had the part to collect and store the samples and analyzes them using the Fourier Transform equation. [This is the library used, made by googol](https://github.com/Googool/pico_fft)
- **TinyUSB Library:** This was the library used for pico to behave as HID and program the base input functions.

**Innovative Controls:**
- **Jump:** Frequencies of C (3rd and 4th octaves)
- **Big Jump:** Frequencies of E (3rd and 4th octaves)
- **Slide:** Frequencies of A (3rd and 4th octaves)

By focusing on these advanced technologies, Indiana João offers an engaging and unconventional gameplay experience, showcasing the potential of integrating hardware and software for interactive entertainment.
