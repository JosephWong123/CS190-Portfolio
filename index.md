## Joseph's CS 190 Portfolio

Welcome to my portfolio page for CS 190 / Music 147 (Computer Music Programming) for Spring 2022! 
This page will contain links to my projects from this class.

[Programming Assignment 1: Type Your Name](https://drive.google.com/drive/folders/10aKLRyiVmyiCHwwhuGNVV2HzZfrqsTMN?usp=sharing).

This is a Max patcher which responds to the input "Joseph Wong", with the correct capitalization. I recorded my own sounds for this project. When the correct letters are inputted, the patcher plays a simple violin melody. I used the preload function to load the ezdac~ object with several different tracks. I used a coll object to effectively map key values (of their corresponding ASCII values) to values that correspond to the sound to play. After this, the value (of the track to play) is passed to the sfplay~ object, which then plays the appropriate sound file.

[Programming Assignment 2: Web Audio API](https://josephwong123.github.io/CS-190-Assignment-2/)

This project is similar to the Type Your Name project from Programming Assignment 1. This application takes name as an input and uses the ASCII values of 
the characters inputted in the text box to generate a chord through the Web Audio API in JavaScript. A GainNode was used to combine the sounds into a
chord, and multiple OscillatorNodes were used to play the various tones in the chord.

[Programming Assignment 3: Max Synthesizer](https://drive.google.com/drive/folders/1NfVt6NcptgCOCx-dr_3dyBtyPhg9JCJV?usp=sharing)

This is a very basic Max synthesizer, based off of several examples from the Max Cookbook. This synthesizer responds to note messages and plays the
corresponding pitches associated with the MIDI notes inputted. Additionally, you can use the modulation slider to control the vibrato depth, as well
as send in a pitch bend message to bend the pitch being played. This patcher also features ADSR control with dials.

[Programming Assignment 4: Algorithmic Composition](https://drive.google.com/file/d/173TMDf2vAgErNueHzl7kZSuF4EqFVIpX/view?usp=sharing)

This Max patcher is a simple project, which randomly generates MIDI notes to be played on each 16th note, using the metro and transport objects in Max. The user can set the probability to generate notes, as well as the probability to generate additional notes to be played at the same time (up to 3 notes at a time). The note duration, pitch, and velocity are all randomly generated using the random object in Max.

[Final Project: Progress Report](https://josephwong123.github.io/CS190Final/)
