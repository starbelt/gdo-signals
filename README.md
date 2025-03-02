# Garage Door Opener Signal Dataset

This repository contains signal data and spectograph images of signals acquired from three garage door opener devices. Each signal is an On-Off Keying (OOK) signal operating at roughly 315 MHz with either two or three unique signals per device. Each signal consists of repeated phrases within each pulse with at least one "word", or unique signal block, within each phrase. This dataset is sorted by the device used, the button pressed to achieve a signal, and the subject word within that signal.

### Example Signal Words
Shown below is an example signal from one of the garage door opener devices. As shown in the image, the signal consists of individual blocks of data which appear to operate on a timed pulse. Each individual block can be referred to as a "word", which in turn allows for the signal pulse to be referred to as a "phrase".

![Door Opener Signal Full](https://github.com/user-attachments/assets/1c80de89-f0a9-4d1a-a109-d45872dbdb27)

To elaborate on each word, two gifs are shown below highlighting words in a given signal. Each word shown below is a piece of the above whole signal, showing how some words can be repeated in a phrase. The first gif below shows the first and third words of the signal, and as can be seen below they are identical. This means each odd word in the above signal is the same word, simply repeated for each pulse.

![Word 1-3](https://github.com/user-attachments/assets/bd4fe2d4-6fe0-4b0b-838c-54cb0ae3c44c)

Just like the gif above, the gif shown below highlights the second and fourth word in the previously shown signal. Each image in this gif is operating at a different spectrogram power level to highlight that they are separate images of separate words. This shows that both the second and fourth word in the signal are also identical, and thus each even word in the signal is an identical word.

![Word 2-4](https://github.com/user-attachments/assets/fd448a79-0c13-4531-bff2-b701a18d21eb)
