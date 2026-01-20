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
- [Usage Instructions](#usage-instructions)
- [License](#license)

## Sessions

### Session 1: MIDI Processing

Explore three different Python libraries for working with MIDI files:

- **pretty_midi**: High-level interface focused on musical content
- **mido**: Low-level interface for MIDI messages
- **pypianoroll**: Piano roll representation for multi-track music

Main objective of this session is to learn to parse, analyze, and visualize MIDI files using these libraries, gaining hands-on experience with MIDI representation.

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

---

## License

This repository is licensed under the [Apache License 2.0](LICENSE).

---
