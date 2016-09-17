# dspectrum:
Automated RF/SDR Signal Analysis [Reverse Engineering]

<img src="https://raw.githubusercontent.com/tresacton/dspectrum/master/dspectrum_comparison.png"> 

Pre-requisites
------------
Inspectrum (https://github.com/miek/inspectrum)

Ruby

Installation
------------

    $ git clone https://github.com/tresacton/dspectrum
    $ cd dspectrum
    $ chmod +x ./dspectrum
    $ ./dspectrum


Usage:
------------

    $ ./dspectrum
    
This will spawn an interactive shell, along with inspectrum itself.
As you usually would, open your capture file. Then align the cursors, right click the signal, add amplitued plot (for OOK) or add frequency plot (for 2FSK). Right click the plot that appeared, and click extract data. The demodulated bits should appear in your terminal.

This script has been tested with OOK & 2FSK signals with a 100% success rate (so far...). It does some sanity checking and will alert if you something doesn't feel right.

You can also use this tool to compare 2 parts of a signal in the same file, or signals from two separate files.

      

Demo
---------------

Video demonstration - Capturing signals from two files, and comparing them:
[![YouTube Video](https://raw.githubusercontent.com/tresacton/dspectrum/master/youtube.png)](https://youtu.be/wR0HpWfeVRU)



Thanks
------

> nullwolf 

> GitHub [@tresacton](https://github.com/tresacton) &nbsp;&middot;&nbsp;
> Twitter [@tresacton](https://twitter.com/tresacton)

