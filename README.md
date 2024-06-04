CS 190D - Mitali Gaidhani
# 1. Final Project #

## Background ##
For my final project, I pursued a more detailed sound design project. Because of my extensive training in the Indian classical music tradition over the last decade (sitar, Indian classical dance: kathak, and vocal music), I was eager to develop a novel application of Allolib in this realm. As a result, my final project emulates the sitar, an Indian classical plucked string instrument, using synthesis. In my first attempt at synthesizing a sitar, I attempted to recreate the work in a [research paper](https://ieeexplore.ieee.org/document/9033925/figures#figures) that synthesized sitar using the additive synthesis technique. Additive synthesis uses the summation of sinusoids to create sound. However, the paper's sitar synthesis equation uses the time-varying amplitude of partials in a sitar. This proved to be a challenge because of the complexity of the sitar sound compared to a guitar and piano. With the limietd time and resources left in the quarter, using additive synthesis to synthesize the sound of a sitar was no longer feasible. Therefore, I pivoted to a project that synthesized a sitar using a sampling technique.

## Implementation ##
To accomplish sitar synthesis using sampling, I recorded audio segments of sitar notes. Indian classical music is divided into different *raags* or frameworks that each have a unique combination of ascending and descending scales. For the sake of this project, I sampled with *raag Yaman*. I used the microphone on my computer to record notes in Audacity and export them as .wav files. I built on Jake Delgato's "konpu-STUDIO" music production app and sampling synthesizer.     

# 2. Melody in Allolib #
I arranged "Exile" from Taylor Swift's folklore for the Allolib synthesized piano. I chose this piece for the depth of emotion it conveys, proving that there is much complexity behind the rather simple melody. 
