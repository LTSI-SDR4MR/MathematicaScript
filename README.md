# SDR4MR project
We would like to propose a simple and cost-effective solution to specifically solve the measurement of the Radiofrequency  (RF) component of Magnetic Resonance (MR) sequences. This  SDR for magnetic resonance (SDR4MR) project uses :

*a SDR, for example, implemented as a USB stick directly connected to a computer,

*a SDR software (CubicSDR in our case) which manages the demodulation methods, adjusts the gains, and receives the demodulated data. This software allows to record the RF pulse sequence as a .wav file,

*a Mathematica script which provides a summary analysis of WAV files recorded by the software-defined radio during an MR pulse sequence. 
# Mathematica script
This open source project is for Mathematica (Wolfram Language). This is a basic version given as a notebook .nb file. For the moment the variables and comments are in French.
# License matters
All code files and executable documents are with the license GPL 3.0. For details see http://www.gnu.org/licenses/ .

All documents are with the license Creative Commons Attribution 4.0 International (CC BY 4.0). For details see https://creativecommons.org/licenses/by/4.0/ .
# Usage
An example wav file of a SE-EPI (SpinEcho-Echo Planar Imaging) diffusion weighted sequence recorded at 1.5 T is added to the project to test the SDR4MR Script.nb file.
# Limits
Please consider that this is a simple illustrative version of the method that can, and must, be improved.
# 
Hervé Saint-Jalmes 13/02/2024
