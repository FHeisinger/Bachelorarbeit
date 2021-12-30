# Bachelorthesis 
Yo, here is all the stuff for my bachelor thesis, all the data and code. If you don't like my style of programming, well sucks to be you then.

I will give a short explanation about the stuff in the respected folders. The rest is up to you.


## InN:
### InN Martins double resonanz:
The measurements for this part were done at the "Leibniz-Institut für Analytische Wissenschaften" - ISAS - in Berlin Adlershof. Here I helped my supervisor perform some measurements and became acquainted with Raman spectroscopy. The two python files with 266 and 405nm are data evaluations for Raman data performed with the respected Laser wavelengths, while the main file plots the diagrams and stuff for a small part of the thesis. All other measurements are from a basement laboratory of the Technical university Berlin, were I spend my summer 2021.


### InN Mapping all samples:
Here you will find two programs that do the same thing, but for measurements with different lasers. Only a small part of the  532 nm laser results are useful, so most of this is not in the thesis. You will see (if you actually browse through my code) that I made everything two times, for different laser intensity filters. That is because I noticed one sample being burned after the measurement, so everything had to be done again.
The txt-files are used to hand over data to the "InN MBE Mapping different Pinholes" file manually, because I did not bother implementing that in a better way.

### InN MBE Mapping different Pinholes:
In this programm, the main part of the thesis in created. 
One of my samples showed by for the best results, so I tried/was forced to make the measurements even better. So I tried to change some stuff around (measuring with different parameters), improved the resolution and paid with an immense measurement time (up to 3 days). In the end, only the measurement for the smallest confocal Pinhole is actually used in the thesis, so scroll down if you want to see that. The txt-files from the last folder are use here to create a compact version of the Raman frequency pictures.

## GaN:
### GaN Mapping different Pinholes:
This is an earlier version of the InN MBE Mapping stuff, just for another sample. I compared basically everything from the measurements and created an unnecessary amount of useless pictures. In the end, I snuck one in the thesis. Most of the stuff here is just preparation for the actual GaN work. The results are packed in txt-files for further tinkering.

### Curvature GaN:
In this folder are two versions of the same program, there I use in situ data provided by Dr A. Dadgar to calculate stress and compare it to stress from my Raman measurements. 
This stuff goes in the Paper, that I have hopefully finished by now. 
