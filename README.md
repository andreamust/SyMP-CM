# Symbolic Music Analysis and Computational Musicology

Course repository for the [*"Symbolic Music Analysis and Computational Musicology"*](https://www.upf.edu/web/smc/symbolic-music-analysis-and-computational-musicology) course taught at the [Music Technology Group (MTG)](https://www.upf.edu/web/mtg) of [Universitat Pompeu Fabra (UPF)](https://www.upf.edu/), Barcelona.


## About

This course provides a comprehensive introduction to computational approaches for analyzing symbolic music representations. 
The main objective of the course is to learn to work with various music encoding formats and apply computational methods to musicological research questions.


## Table of Contents

- [About](#about)
- [Table of Contents](#table-of-contents)
- [Sessions](#sessions)
	- [Session 1: MIDI Processing](#session-1-midi-processing)
	- [Session 2: Introduction to Music21](#session-2-introduction-to-music21)
	- [Session 3: Processing Symbolic data with Music21](#session-3-processing-symbolic-data-with-music21)
	- [Session 4: Tokenization of Symbolic Music Data](#session-4-tokenization-of-symbolic-music-data)
- [Usage Instructions](#usage-instructions)
- [Dataset](#dataset)
- [License](#license)

## Sessions

### Session 1: MIDI Processing

Explore three different Python libraries for working with MIDI files:

- [**pretty_midi**](https://craffel.github.io/pretty-midi/): High-level interface focused on musical content
- [**mido**](https://mido.readthedocs.io/en/latest/): Low-level interface for MIDI messages
- [**pypianoroll**](https://pypianoroll.readthedocs.io/en/latest/): Piano roll representation for multi-track music

Main objective of this session is to learn to parse, analyze, and visualize MIDI files using these libraries, gaining hands-on experience with MIDI representation.

### Session 2: Introduction to Music21

Introduction to [**music21**](https://www.music21.org/music21docs/moduleReference/), a Python toolkit for symbolic music analysis and manipulation.

#### Key Topics (notebook 2)
- Basic objects (notes, rests, chords, pitches)
- Musical structures (streams, parts, scores)
- Musical attributes (keys, time signatures, tempo)
- Analysis functions (key detection, intervals)

#### Key Topics (notebook 3)
- Multi-format support (MIDI, MusicXML, ABC)
- Batch processing and statistical analysis
- Format conversion 

### Session 3: Tokenization of Symbolic Music Data
Hands-on activity on the usage of the [**Miditok**](https://miditok.readthedocs.io/en/latest/index.html) library for tokenizing symbolic music data and [**linearized-musicxml**](https://pypi.org/project/linearized-musicxml/) for MusicXML data.

#### Key Topics
- Tokenization concepts and techniques
- MIDITok library usage (REMI, CPWord, MIDILike, Structured tokenizers)
- MusicXML linearization and tokenization


## Usage Instructions


1. **Clone the repository:**
	```bash
	git clone <repo-url>
	cd SyMP-CM
	```

2. **Set up a Python environment (recommended):**
	- Use either a [conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) or a [virtual environment (venv)](https://docs.python.org/3/library/venv.html) to manage dependencies and avoid conflicts with your system Python.
	- Example with conda:
	  ```bash
	  conda create -n sympcm python=3.11
	  conda activate sympcm
	  ```
	- Example with venv:
	  ```bash
	  python3 -m venv venv
	  source venv/bin/activate
	  ```

3. **Before every class:**
	- Pull the latest changes:
	  ```bash
	  git pull
	  ```
	- Install or update requirements:
	  ```bash
	  pip install -r 2026/requirements.txt
	  ```
	- Check the session folder for new or updated notebooks and data.

4. **Run the notebooks:**
	- Open the relevant session notebook in your editor of choice.
	- Follow the instructions in each notebook for setup and execution.


## Dataset

All datasets used in this course are located in the [2026/data](2026/data) folder. Each dataset is a small, copyright-free subset sampled from a larger public collection:

- **MIDI Dataset** ([2026/data/midi](2026/data/midi)):
	- Source: [Lakh MIDI Dataset (LMD)](https://colinraffel.com/projects/lmd/) ([Kaggle link](https://www.kaggle.com/datasets/imsparsh/lakh-midi-clean))
	- Description: A subset of 100 MIDI files sampled from the Lakh MIDI Dataset, a large collection of unique MIDI files for music information retrieval research.

- **MusicXML Dataset** ([2026/data/musicxml](2026/data/musicxml)):
	- Source: [PDMX: Public Domain MusicXML](https://zenodo.org/records/13763756) ([Zenodo link](https://zenodo.org/record/13763756))
	- Description: A subset of 100 MusicXML files sampled from PDMX, a large collection of public domain MusicXML files from musescore.com.

- **ABC Dataset** ([2026/data/abc](2026/data/abc)):
	- Source: [Nottingham Dataset](http://abc.sourceforge.net/NMD/) ([Kaggle link](https://www.kaggle.com/datasets/tishyatripathi/nottingham-music-dataset))
	- Description: A subset of 100 folk tunes in ABC notation, sampled from the Nottingham dataset of traditional music.



## License

This repository is licensed under the [Apache License 2.0](LICENSE).

---
