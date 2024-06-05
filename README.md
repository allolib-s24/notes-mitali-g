CS 190D - Mitali Gaidhani
# 1. Final Project #

## Background ##
For my final project, I pursued a more detailed sound design project. Because of my extensive training in the Indian classical music tradition over the last decade (sitar, Indian classical dance: kathak, and vocal music), I was eager to develop a novel application of Allolib in this realm. As a result, my final project emulates the sitar, an Indian classical plucked string instrument, using synthesis. In my first attempt at synthesizing a sitar, I attempted to recreate the work in a [research paper](https://ieeexplore.ieee.org/document/9033925/figures#figures) that synthesized sitar using the additive synthesis technique. Additive synthesis uses the summation of sinusoids to create sound. However, the paper's sitar synthesis equation uses the time-varying amplitude of partials in a sitar. This proved to be a challenge because of the complexity of the sitar sound compared to a guitar and piano. With the limietd time and resources left in the quarter, using additive synthesis to synthesize the sound of a sitar was no longer feasible. Therefore, I pivoted to a project that synthesized a sitar using a sampling technique.

## Implementation ##
To accomplish sitar synthesis using sampling, I recorded audio segments of sitar notes. Indian classical music is divided into different *raags* or frameworks that each have a unique combination of ascending and descending scales. For the sake of this project, I sampled with *raag Yaman*. I used the microphone on my computer to record notes in Audacity and export them as .wav files. I built on Jake Delgato's "konpu-STUDIO" music production app and sampling synthesizer. The naming convention for the .wav files in Jake's app is with MIDI notes. Therefore, I had to transcribe the Indian classical music scale (Sa, Re, Ga, Tiwra Ma, Pa, Dha, Ni, Sa) for raag Yaman into Western notes. I identified the tonic used for tuning the sitar as C so the Indian scale translates to Western music as follows: C4, D4, E4 F4#, G4, A4, B4, C5. Then, I added these notes to the sound bank in Jake's app. A major part of my project was experimenting with the amount of samples in the sound bank and how that influences the quality of the notes that are synthesized as a result. For example, I hypothesized that having a smaller number of recorded notes produce a lower sound quality in the synthesized notes because there are less data points to use. However, after trying different combinations of the number of notes, I preferred the sound of the synthesis with just one audio file, Sa (C4), and felt like it best matched the true sound of a sitar. While this goes against my intution, this is probably because of the quality of the recordings. Lastly, I added graphics that change colors and shape based on the note you play. A key component of Indian classical music is improvisation, so my final piece is one that I recorded myself playing on the synthesized sitar keyboard.

## Music Composition Video ##
https://github.com/allolib-s24/notes-mitali-g/assets/46696490/ed73360a-b5a2-461c-bdf3-9d728be18902

## Final Project Demo ##


# 2. Melody in Allolib #
I arranged "Exile" from Taylor Swift's folklore for the Allolib synthesized piano. I chose this piece for the depth of emotion it conveys, proving that there is much complexity behind the rather simple melody. 

## Arrangement Video ##
https://github.com/allolib-s24/notes-mitali-g/assets/46696490/fc6af18d-631c-4348-9e29-8a944a69c30e

