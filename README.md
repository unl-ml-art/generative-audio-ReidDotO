# Project 2 Generative Audio

Reid Brockmeier, rbrockmeier2@unl.edu

## Abstract

For this project, I wanted to train text to speech on my voice, so that I could use it as a tool for YouTube videos. The original plan was to use it to record the transcripts for videos through text to speech, but the final utilization varied a bit. I had an idea for a video that integrated the text to speech in a way that used it as part of the content. If the whole video were transcribed in text to speech, it surely would have been too much. I trained a TTS model using the provided Jupyter Notebook with voice lines recorded live in order make them as genuine as possible. The final outcome was a video that I am genuinely proud of, and the text to speech adds a lot to the video without being the main focus. Although the generated audio is far from perfect, the result it provided is perfect for the way I used it, so I am very satisfied with my results. I will definitely use this again when relevent because it is a very useful tool that adds an unique element to videos.

## Model/Data

- Training Data 
    - voice clips from live recordings:
        - [wav](https://github.com/unl-ml-art/generative-audio-ReidDotO/tree/master/wav)

## Code

- [ReidTTS_zeroshot_TTS.ipynb](ReidTTS_zeroshot_TTS.ipynb)

## Results

- Resulting TTS wav files - Some are better than others, and most are not used.
    - [out](https://github.com/unl-ml-art/generative-audio-ReidDotO/tree/master/out)
- Final YouTube Video - The text to speech is used at the very beginning and later in the video.
    - [The Problem with Shiny Hunting in Pokemon Legends: Arceus](https://www.youtube.com/watch?v=zgGw7GRMZfA)

## Technical Notes

All the technical steps used to create TTS using my voice were done through the included [notebook](ReidTTS_zeroshot_TTS.ipynb). 

## Reference

[TTS Demo](https://github.com/roberttwomey/ml-art-code/tree/master/voice_cloning)
