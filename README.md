Jamulus - Internet Jam Session Software
---------------------------------------

The Jamulus software enables musicians to perform real-time jam sessions over the internet.
There is one server running the Jamulus server software which collects the audio data from
each Jamulus client, mixes the audio data and sends the mix back to each client.


Low-Latency (Internet) Connection tool
Under the GNU General Public License (GPL)
http://llcon.sourceforge.net


INTRODUCTION:
The Jamulus software enables musicians to perform real-time jam sessions over
the internet. There is one server running the Jamulus server software which
collects the audio data from each Jamulus client, mixes the audio data
and sends the mix back to each client.

Jamulus is Open Source software (GPL, GNU General Public License) and runs under
Windows (ASIO), MacOS (Core Audio) and Linux (Jack). It is based on the Qt
framework and uses the OPUS audio codec. 

The required minimum internet connection speed is 200 kbps for the up- and
downstream. The ping time (i.e. round trip delay) from your computer to the
server should not exceed 40 ms average.

The source code is hosted at Sourceforge.net.


EXTERNAL CODE:
This code contains open source code from different sources. The developer(s) want
to thank the developer of this code for making their efforts available under open
source:

- Qt cross-platform application framework: http://qt-project.org

- Opus Interactive Audio Codec: http://www.opus-codec.org

- Audio reverberation code: by Perry R. Cook and Gary P. Scavone, 1995 - 2004
  (taken from "The Synthesis ToolKit in C++ (STK)"):
  http://ccrma.stanford.edu/software/stk
  
- Some pixmaps are from the Open Clip Art Library (OCAL):
  http://openclipart.org

- Audio recording for the server and SVG history graph, coded by pljones: http://jamulus.drealm.info