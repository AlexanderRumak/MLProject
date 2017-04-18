# MLProject
Machine Learning (Spring 2017) Project


## Environment and Packages

### Anaconda with Python 3.6
This project has been created using the Anaconda package manager with Python 3.6.

## LibreSpeech Data Set

The [LibreSpeech Data Set](http://www.openslr.org/12/) was used because of its large quantity of 'clean' data. The algorithms in this file directory were originally written for .wav files, and the original data was in .wav format, so a conversion to .wav was necessary. There is minimal quality loss in this process, as .flag and .wav files hold similar quality.

### .flac to .wav converter

In order to use the .flac to .wav converter, the [PySoundFile](https://pysoundfile.readthedocs.io) library must be installing on your Python installation. If you are using Anaconda with Python 3.6, then the dependencies required for PySoundFile are already included.

To install it using anaconda, run the following command in conda command:

```Bash
pip install pysoundfile 
```

To import soundfile:
```Python
import soundfile as sf
```

The converter can be run in Python command-line in flacToWaveConverter. The converter will prompt you to input a file directory. The converter will then crawl the entire file directory, converting every possible .flac file to a .wav file.
