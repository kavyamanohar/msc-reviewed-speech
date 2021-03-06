This is the repository of a curated subset of speech samples collected using [MSC app](https://msc.smc.org.in/). Speech samples are selected on the criteria that they have at least 3 positive reviews. The original corpus of collected audios is available [here](https://gitlab.com/smc/msc/-/tree/master/audio). The latest version of curated Malayalam Speech Corpus is hosted [here](https://releases.smc.org.in/msc-reviewed-speech/).

### Audio

- Single channel raw audio
- 48 kHz sampling rate
- 16 bit encoding

### Metadata

metadata.tsv holds the following details corresponding to every speech file.

- speechid
- speechpath
- speaker_id
- review_score
- transcript
- category (optional speech category)
- speaker_gender (optionally self declared)
- speaker_age (optionally self declared)


### DATASHEET

Details of the database creation and usage is available in the DATASHEET.md file

### DATA ANALYSIS

Quick details:
- 1541 speech samples
- 75 speech contributors
- 1:38:16 hours of speech
- 482 unique sentences
- 1400 unique words
- 553 unique syllables
- 48 unique phonemes

For more detailed analysis see the python notebook provided [here](https://gitlab.com/smc/msc-reviewed-speech/-/blob/master/analysis/EDA.ipynb)


### CONTRIBUTORS

Voice contributors names (if self provided) are listed in contributors.tsv

### LICENSE

CC-BY-SA 4.0 International License

### To perform Data Analysis

Create a python virtual environment and run 

```pip install -r requirements.txt```

Exploratory Data Analysis notebook is available as: `./analysis/EDA.ipynb`



