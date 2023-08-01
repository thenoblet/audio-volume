# audio-volume
Modifies / changes the volume of an audio file

The program accepts three command-line arguments: input represents the name of the original audio file, output represents the name of the new audio file that should be generated, and factor is the amount by which the volume of the original audio file should be scaled.
For example, if factor is 2.0, the program doubles the volume of the audio file in input and save the newly generated audio file in output.


How to test the program (on linux):
INPUT.wav is the name of an original audio file and OUTPUT.wav is the name of an audio file with a volume that has been scaled by the given factor (e.g., 2.0 or 0.5).

Execute  $ ./volume INPUT.wav OUTPUT.wav 2.0 
-- When you listen to output.wav (as by control-clicking on output.wav in the file browser, choosing Download, and then opening the file in an audio player on your computer), it should be twice as loud as input.wav!

or

$ ./volume input.wav output.wav 0.5 
--- When you listen to output.wav, it should be half as loud as input.wav!
