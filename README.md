# Fiber-photometry-analysis
Code to analyse fiber photometry oscillations and micro-arousals 


The code is ordered into folders with "scripts" containing scripts used for analysis and "functions" containing custom functions that are used in the scripts.

Additionally, to load fiber photometry data we use a custom function provided by Tucker Davis Technologies called "TDTbin2mat" that you can find in their [repository](https://github.com/tdtneuro/TDTMatlabSDK/). To load EEG and EMG data obtained using Sleepscore (ViewPoint, France) we use a custom function provided by ViewPoint Behavior Technology called "loadEXP" - this function can be obtained upon request (www.viewpoint.fr).
