sub3dtool
=========

A simple 3D subtitles convert, convert SRT to ASS format, work well with MPlayer and VLC.

This tool is made for GNU/Linux but is reportedly working fine with OS X (previously known as Mac OS X).

Basic Usage
===========

To convert a subtitle to Side-by-Side

	sub3dtool input.srt --3dsbs --depth 3 -o output.ass

Whereas **input.srt** is the path to the file you need to convert.

**output.ass** is the name of the file you want as the result.

**--3dsbs** indicates that you want to convert the subtitle to 3DSBS (Side-by-Side) format. 

**--3dsbs** indicates that you want to convert the subtitle to 3DSBS (Side-by-Side) format. 

**--depth** is the depth of the legend in relation to screen. use values between -10 and 10. Default: 1


For Development
===============

after clone run:

	automake -a -c
	./configure
	make install
	make dist (generate a zip for distribution)


