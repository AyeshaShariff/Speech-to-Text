# Speech-to-Text

## PROBLEM STATEMENT
Speech to Text conversion using microphone and audio files and creating UI sing tkinter.

## Toolkit
1. speech_recognition 
2. pydub
3. tkinter

## Project
Created user interface for speech to text convertor using tkinter. The interface has two options
![st1](https://user-images.githubusercontent.com/93417235/183219659-41183629-07a7-4a06-bf09-09ac357e65c8.png)

1. Speech-to-Text
   The user recodrs the speech using microphone. The speech gets converted to text and this is done by using the library speeh-recognition.
   The user has to click on the record button to record the speech and wait for few seconds. The speech gets converted to text and the output is presnt in the textbox.
   
   ![st2](https://user-images.githubusercontent.com/93417235/183219612-7a0c2164-7afa-4282-8856-b7d338b8edea.png)

2. Audio-to-Text
   The user uploads the audio file(.wav format), the files can be of large size. The audio is seperated into chunks and then each chunk is converted into text. Finally,    all the text chunks are appended and the whole text is printed. All this is done using the pydub library since we are dealing with .wav format files. Pydub is used      for playing, splitting and merging the .wav files.
   The user can uplaod the file from his/her system by clicking the upload button and then click the convert button to convert it into text.
   
   ![st3](https://user-images.githubusercontent.com/93417235/183219627-d68d235b-5631-4fb2-b3ad-6e88b577b28f.png)
   
## Conclusion
Using speech_recognition and pydub one can successfully built a speech/audio to text convertor.
