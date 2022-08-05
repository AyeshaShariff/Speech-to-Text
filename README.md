# Speech-to-Text

##PROBLEM STATEMENT
Speech to Text conversion using microphone and audio files and creating UI sing tkinter.

##Toolkit
1. speech_recognition 
2. pydub
3. tkinter

##Project
Created user interface for speech to text convertor using tkinter. The interface has two options
![alt text]()
1. Speech-to-Text
   The user recodrs the speech using microphone. The speech gets converted to text and this is done by using the library speeh-recognition.
   The user has to click on the record button to record the speech and wait for few seconds. The speech gets converted to text and the output is presnt in the textbox.

2. Audio-to-Text
   The user uploads the audio file(.wav format), the files can be of large size. The audio is seperated into chunks and then each chunk is converted into text. Finally,    all the text chunks are appended and the whole text is printed. All this is done using the pydub library since we are dealing with .wav format files. Pydub is used      for playing, splitting and merging the .wav files.
   The user can uplaod the file from his/her system by clicking the upload button and then click the convert button to convert it into text.
