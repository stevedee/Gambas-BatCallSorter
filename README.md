# Gambas-BatCallSorter
<<<<<<< HEAD
"BatCallSorter" is a Gambas application to sort full-spectrum bat call recordings.

Full-spectrum bat calls are recorded in real-time as .wav files, via a bat detector and an audio card that supports a sample rate of 192kHz or higher.

In order to streamline the assessment of these recordings, a folder containing a group of these WAV files is opened by this application. The application processes these files using SoX commands to create:-
1. a "normalised" single channel wav file (currently the "left" channel is saved and the "right" channel is deleted.
=======

"BatCallSorter" is a Gambas application to sort full-spectrum bat call recordings.

Full-spectrum bat calls are recorded in real-time as .wav files, via a suitable bat detector and an audio card that supports a sample rate of 192kHz or higher.

In order to streamline the assessment of these recordings, a folder containing a group of these WAV files is opened by this application. The application processes these files using SoX commands to create:-
1. a "normalised" single channel wav file (currently the "left" channel is saved and the "right" channel is deleted).
>>>>>>> 4705e6a94f1b5856effd60aec0c8a55c16c013a3
2. a spectrogram image file.
3. a 10 times "time-expanded" MP3 file.

As each file is selected in the BatCallSorter:-
 - the corresponding spectrogram is displayed
 - they user may play the associated MP3 file
 - the user may open the file in Audacity
 - the user may save "bat species" & "call type", which are saved as Tags in the MP3 and WAV files (using id3 tags)
<<<<<<< HEAD
 - the user may delete any file sets (including wav, MP3 & png image file)
=======
 - the user may delete any file, which automatically deletes the corresponding wav, MP3 & png image file
>>>>>>> 4705e6a94f1b5856effd60aec0c8a55c16c013a3
 - a running total of files is displayed

You will find more information for this project on my blog: https://captainbodgit.blogspot.co.uk
(click on the "bats" tab)
