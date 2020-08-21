This is the repository of a subset of speech samples collected using MSC app (https://msc.smc.org.in/). Speech samples are selected on the criteria that they have at least 3 positive reviews.

### Audio

- Single channel audio in .wav format
- 48 kHz sampling rate
- 16 bit encoding

### Metadata

metadata.tsv holds the following details corresponding to every speech file

- speechid	
- speechpath	
- speaker_id	
- review_score	
- transcript
- category	
- speaker_gender
- speaker_age

### DATASHEET

Details of the database is available in the DATASHEET.md file

### CONTRIBUTORS

Voice contributors names are listed in contributors.tsv

### LICENSE

CC-BY-SA 4.0 International License

### To perform Data Analysis

- Create a python virtual environment
- `pip install jupyter`
- `pip install flask`
- `pip install mlphon`
- `pip install pandas`
- `pip install matplotlib`


