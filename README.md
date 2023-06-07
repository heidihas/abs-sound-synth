# Audio and Text Conditioned Abstract Sound Synthesis through Human-AI Interaction
(Code and evaluation resources)

This repository is related to the Master's thesis work by Heidi Hassinen at Aalto University, under the Computer, Communication and Information Sciences programme.

The Audio and Text Conditioned Abstract Sound Synthesis algorithm generates novel, abstract sounds from audio and/or text input. The sound synthesis process bases on sound construction with multiple sine waves. In the algorithm, [the AudioCLIP model](https://github.com/AndreyGuzhov/AudioCLIP) is used for calculating audio and text embeddings in a shared vector space in order to compare the similarity between the embeddings of the two modalities. [The DDSP library](https://github.com/magenta/ddsp) enables the usage of digital sound processing tools, such as a sinusoidal synthesizer, inside the optimization loop. In this work, the content of the DDSP library was translated by the author from TensorFlow to PyTorch, in order for the functions to merge well with the AudioCLIP model based on the latter library.

## Thesis

[PDF file](https://aaltodoc.aalto.fi/bitstream/handle/123456789/119485/master_Hassinen_Heidi_2023.pdf?sequence=1&isAllowed=y)

## Code

[Colab file](https://colab.research.google.com/drive/1jSIdy-9ocLMVp6YEpGRMxx1rzZ4PXIq2?usp=sharing)

## Evaluation resources

### Experiments

[Folder](https://github.com/heidihas/abs-sound-synth/tree/main/Experiments)

### User study

[Folder](https://github.com/heidihas/abs-sound-synth/tree/main/User_study)
