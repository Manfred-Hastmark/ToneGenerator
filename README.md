# Foobar

This project is a simple implementation of a tonegenerator which plays a tone given a frequency and a duration

## Installation

First of you need to download python to your computer, please follow this [tutorial](https://www.dataquest.io/blog/installing-python-on-windows/) to do so.

Secondly, the package [pydaudio](https://pypi.org/project/PyAudio/) will have to be installed. Todo so, run the following command in command prompt:

```bash
py -m pip install pyaudio
```
## Usage

First open command prompt in the directory of the project, it should look like below:

```bash
...\ToneGenerator>
```
Secondly run the program by typing the following in the command prompt:

```bash
...\ToneGenerator> py main.py
```
Next a prompt asking you to enter the length of the tone should pop up, it should look like below. Please enter the duration as a floating point number here and press enter.

```bash
...\ToneGenerator> py main.py
How many seconds should the sound play?
```
Next, the program will prompt you to enter the frequency of the sound. Please enter an integer number and press enter. The program should now play the desired note.

```bash
\ToneGenerator> py main.py
How many seconds should the sound play? 1.0
What frequency should the note have?
```
