The Discrete Cosine Transformation
============================
An efficient algorithm which uses the Discrete Cosine Transformation to compress .wav files by breaking long signals into segments and computing the DCT of each segment. Next, it identifies frequency components with amplitudes so low they are inaudible and removes them storing only the frequencies that remain. It then plays the signal back, loads the frequencies and amplitudes for each segment and applies the DCT.

### Freesound

Special thanks to Freesound (http://freesound.org), which is the source of many of the
sound samples I use in this project, and to the Freesound users who
uploaded those sounds.  I may  some of their wave files in
the GitHub repository for this project, using the original file
names, so it should be easy to find their sources.

Unfortunately, most Freesound users don't make their real names
available, so I can only thank them using their user names.  Samples
used in this project  were contributed by Freesound users: iluppai,
wcfl10, thirsk, docquesting, kleeb, landup, zippi1, themusicalnomad,
bcjordan, rockwehrmann, marchascon7, jcveliz.  Thank you all!

Here are links to the sources:

http://www.freesound.org/people/iluppai/sounds/100475/

http://www.freesound.org/people/wcfl10/sounds/105977/

http://www.freesound.org/people/Thirsk/sounds/120994/

http://www.freesound.org/people/ciccarelli/sounds/132736/

http://www.freesound.org/people/Kleeb/sounds/180960/

http://www.freesound.org/people/zippi1/sounds/18871/

http://www.freesound.org/people/themusicalnomad/sounds/253887/

http://www.freesound.org/people/bcjordan/sounds/28042/

http://www.freesound.org/people/rockwehrmann/sounds/72475/

http://www.freesound.org/people/marcgascon7/sounds/87778/

http://www.freesound.org/people/jcveliz/sounds/92002/
