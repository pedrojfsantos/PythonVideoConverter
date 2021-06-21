# Python Video Converter

This is a simple script to automatize the conversion of several videos to .MP4,
using ffmpeg (it can be updated to convert to other formats).
This requires the previous installation of ffmpeg on your system. 
For that use "brew install ffmpeg" command to make sure ffmpeg package is available for all
system and not just for a specific environment.

ffmpeg is a fast video encoder, with no interface, so it should be used from
the command line. This is ok if just one file is needed to be encoded, however
it is not much practical when dealing with several video files.

In fact, I have more than 200 small .MOV videos, captured with an iPhone, and I
wanted to save them in a laptop (not Mac). The problem is that laptops don't
read .MOV, unless codecs are installed (I can't install codecs in that laptop),
so the solution is to convert all the videos files to MP4. For a more practical
way to do it, I used a simple python script to run a for loop that runs ffmped
command for each video I wanted to convert.
Take a look at the notebook.
