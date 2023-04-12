# HeartsOnFire - Automatic Drum Transcription (ADT)

HeartsOnFire is a project aimed at creating an Automatic Drum Transcription (ADT) system to help beginner drummers create drum scores. This repository contains a series of Jupyter notebooks for generating your own dataset, training the ADT model, and using the trained model to transcribe drum tracks from input .mp3 files into labeled MIDI files.

## Notebooks included

- `generating our own dataset.ipynb`: This notebook provides instructions and code for generating your own dataset for training the ADT model.
- `model training.ipynb`: This notebook guides you through the process of training the ADT model using the generated dataset.
- `main.ipynb`: This notebook allows you to input an .mp3 file and use the trained ADT model to receive a labeled MIDI file for the source-separated drum track.

## Dependencies

The HeartsOnFire ADT project requires the following libraries and tools:

- Python 3
- Librosa (https://librosa.org/doc/main/index.html)
- PyTorch (https://pytorch.org/)
- NumPy (https://numpy.org/)
- Pandas (https://pandas.pydata.org/)
- pretty_midi (https://craffel.github.io/pretty-midi/)
- demucs (https://github.com/facebookresearch/demucs)
- torch_audiomentations (https://github.com/asteroid-team/torch-audiomentations)

Please refer to the individual notebooks for more detailed instructions on using these dependencies.

## Acknowledgements

We would like to express our gratitude to the following resources, libraries, and tools that have been used in this project:

- [Librosa](https://librosa.org/doc/main/index.html) - for audio processing and feature extraction.
- [PyTorch](https://pytorch.org/) - for deep learning model training.
- [NumPy](https://numpy.org/) - for numerical computing in Python.
- [pretty_midi](https://craffel.github.io/pretty-midi/) - for creating MIDI files in Python.
- [demucs](https://github.com/facebookresearch/demucs) - for source separating drum tracks from input .mp3 files.
- [torch_audiomentations](https://github.com/asteroid-team/torch-audiomentations) - for data augmentation during model training.
- [Pandas](https://pandas.pydata.org/) - for data manipulation and analysis in Python.
- [GitHub](https://github.com/) - for providing a collaborative platform for open-source development.

We are grateful to the developers and maintainers of these tools for their contributions to the open-source community, which have greatly benefited our project.

## Contact Information

For any questions or inquiries about the HeartsOnFire ADT project, please contact us at [skittree@gmail.com].

We hope you find this software useful in your drum scoring endeavors! Happy drumming!