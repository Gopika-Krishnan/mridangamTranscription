# Mridangam Transcription and Konnakol Sequence Generation

This repository contains the data, results, and pipeline for automatic transcription of **Mridangam** (a South Indian percussion instrument) and **Konnakol** (a vocal percussion language) sequences. Our work involves converting audio recordings of Mridangam and Konnakol into transcriptions of syllables and generating rhythmic sequences based on those transcriptions.

We are building on the **Konnakol Typewriter** web application, which converts Konnakol sequences into Mridangam rhythms. Our work expands its functionality by integrating transcription and rhythmic sequence generation tools, and we eventually aim to introduce features like grammar checking and more advanced analysis tools.

This work was carried out at the **Music and Sound Cultures (MASC) research group**, New York University Abu Dhabi, UAE.


## Project Overview

The pipeline includes:
1. **Mridangam Transcription**: Converting audio samples of Mridangam into a transcription of rhythmic syllables.
2. **Konnakol Transcription**: Converting spoken Konnakol sequences into transcriptions of syllables.
3. **Rhythmic Sequence Generation**: Using the transcriptions as input to a Markov model to generate rhythmic sequences.

## Data

### Audio Samples and Transcriptions

| **Mridangam Audio**                         | **Konnakol Audio**                         | **Transcription**                             |
|---------------------------------------------|-------------------------------------------|-----------------------------------------------|
| [![Mridangam Sample 1](https://img.shields.io/badge/play%20audio-Mridangam%20Sample%201-blue)](data/audio/mridangam_sample_1.wav) | [![Konnakol Sample 1](https://img.shields.io/badge/play%20audio-Konnakol%20Sample%201-blue)](data/audio/konnakol_sample_1.wav) | [mridangam_transcription_1.txt](data/transcriptions/mridangam_transcription_1.txt) |
| Sample 1 for Mridangam transcription         | Sample 1 for Konnakol transcription        | Transcription of Mridangam Sample 1             |
| [![Mridangam Sample 2](https://img.shields.io/badge/play%20audio-Mridangam%20Sample%202-blue)](data/audio/mridangam_sample_2.wav) | [![Konnakol Sample 2](https://img.shields.io/badge/play%20audio-Konnakol%20Sample%202-blue)](data/audio/konnakol_sample_2.wav) | [konnakol_transcription_1.txt](data/transcriptions/konnakol_transcription_1.txt) |
| Sample 2 for Mridangam transcription         | Sample 2 for Konnakol transcription        | Transcription of Konnakol Sample 1             |

## Pipeline Diagrams

Below are the pipeline diagrams that illustrate the overall process:

![Pipeline 1](images/pipeline_1.png)  
*Pipeline diagram illustrating the transcription process for Mridangam.*

![Pipeline 2](images/pipeline_2.png)  
*Pipeline diagram illustrating the transcription process for Konnakol and rhythmic sequence generation.*

## Results

---

## Konnakol Typewriter Audio vs Original
We compare the original Konnakol audio with the Konnakol Typewriter-generated audio. The results show the performance of our transcription-to-audio pipeline.

### Comparison Table:

| **Audio**                        | **Original Konnakol Audio**                        | **Generated Konnakol Typewriter Audio**        |
|-----------------------------------|----------------------------------------------------|----------------------------------------------|
| [konnakol_sample_1.wav](data/audio/konnakol_sample_1.wav) | Original Konnakol Audio Sample 1                   | [Generated Sample 1](data/audio/gen_konnakol_sample_1.wav) |
| [konnakol_sample_2.wav](data/audio/konnakol_sample_2.wav) | Original Konnakol Audio Sample 2                   | [Generated Sample 2](data/audio/gen_konnakol_sample_2.wav) |

---


## Future Work

Future steps will include:
- Expanding the dataset to improve model performance.
- Refining the transcription models and enhancing rhythmic sequence generation.
- Exploring real-time transcription and synthesis for live performances.
- Grammar Check tool for Konnakol Sequences

