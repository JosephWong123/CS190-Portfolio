## Joseph's CS 190 Portfolio

Welcome to my portfolio page for CS 190 / Music 147 (Computer Music Programming) for Spring 2022! 
This page will contain links to my projects from this class.

[Programming Assignment 1: Type Your Name](https://drive.google.com/drive/folders/10aKLRyiVmyiCHwwhuGNVV2HzZfrqsTMN?usp=sharing).

This is a Max patcher which responds to the input "Joseph Wong", with the correct capitalization. I recorded my own sounds for this project. When the correct letters are inputted, the patcher plays a simple violin melody. I used the preload function to load the ezdac~ object with several different tracks. I used a coll object to effectively map key values (of their corresponding ASCII values) to values that correspond to the sound to play. After this, the value (of the track to play) is passed to the sfplay~ object, which then plays the appropriate sound file.
