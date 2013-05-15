sub3dtool
=========

A simple 3D subtitles convert, convert SRT to ASS format, work well with MPlayer and VLC.

This tool is made for GNU/Linux but is reportedly working fine with OS X (previously known as Mac OS X).

Basic Usage
===========

To compile from source code. Run in CLI:

	wget http://sub3dtool.googlecode.com/files/sub3dtool-0.4.2.tar.xz
	tar -xf sub3dtool-0.4.2.tar.xz
	cd sub3dtool-0.4.2
	make
	./sub3dtool

Note that the above commands may change as later versions of the software are released.

To convert a subtitle to Side-by-Side, first cd to the folder you put the sub3dtool program. Then run:

	./sub3dtool input.srt --3dsbs -o output.ass

Whereas *input.srt* is the path to the file you need to convert.

*output.ass* is the name of the file you want as the result.

*--3dsbs* indicates that you want to convert the subtitle to 3DSBS (Side-by-Side) format. 
