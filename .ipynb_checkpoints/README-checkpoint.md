# audioAnn_GUI
A simple iPyWidgets Audio Annotator to label audio data with minimal setup and maximum convnenience.

**[ADD A GIF]**
![Demo](labelling_tool.png)

What Is This?
-------------

We have been working with audio data for long time. It was only until custom labelling (of this audio data), we realised the dearth of tools available online. For us the core 



Setup
---------------
To run download the necessary pip packages in requirements.txt file. 

1. **ipywidgets**
2. librosa
3. matplotlib
4. pandas
5. numpy

Start Labelling
===============


1. jupyter-lab
7. Navigate to http://localhost:8888 in your browser

Current Features
----------------
Checklist based features implemented.

Fixes & Bugs
----------------
- [x] Fix Skip Button
- [x] Continue from Previously stored labelled_df
- [x] Drop files already in labelled_df
- [x] Audio Sample & Predictions in text area widget
- [ ] Refactor Code
- [ ] Audio samples display side by side

Future Features
----------------
- [x] Add Test Set Tag to Layout
- [x] Add Difficulty Tag to Layout
- [ ] Undo Last Label Option (CTRL + Z)
- [ ] On the run thresholding of predictions *(Slider with Live-Observe)*
- [ ] Reset Widget Values Button
- [ ] Weekly based Goal Tracker & associated Progress Bar
- [ ] Optimized Layout for Labelling (How??)


Making Requests
---------------
Please feel free to contribute to this contribute project.
