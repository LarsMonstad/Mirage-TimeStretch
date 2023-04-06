# Time-stretch Audio and Annotations for MIRAGE

This script applies time-stretching to an audio file and its associated annotation file. It can be used to generate new audio data for data augmentation purposes. It is part of the MIRAGE project at the University of Oslo (UiO).

MIRAGE - A Comprehensive AI-Based System for Advanced Music Analysis. The main goal is to improve computers' capability to listen to and understand music, and to conceive technologies to facilitate music understanding and appreciation. One primary application is to make music more accessible and engaging.

Created by Lars Løberg Monstad.


## Requirements

- Python 3.6 or higher
- Packages listed in `requirements.txt`

## Installation

To install the required packages, run:

```bash
pip install -r requirements.txt
```

Usage
The script can be run from the command line with the following arguments:

input_audio_file: Path to the input audio file (FLAC or WAV)
input_ann_file: Path to the input annotation file (.ann)
output_directory: Path to the output directory
stretch_factor: Time stretch factor (e.g., 1.4 for 40% faster, 0.8 for 20% slower)
Example usage:

```bash
python tempoaug2.py input_audio_file.flac input_ann_file.ann output_directory 1.4
```
This will create a time-stretched version of the input audio and its annotations, and save the output files in the specified output directory.

![alt text](https://raw.githubusercontent.com/LarsMonstad/Mirage-TimeStretch/main/plot2.png)

License
MIT License
