# Digital Signal Processing (DSP) Final Project

This repository contains the final project for the Digital Signal Processing course at the Sharif University of Technology, under the instruction of Dr. M.T. Manzuri. The project encompasses seven distinct questions, each exploring fundamental concepts and applications in DSP.

The complete project description can be found in the PDF file located in the [Question](./Question) directory.

---

## Project Questions Overview

Below is a brief summary of each question and a link to its corresponding solution directory.

* ### [Q1: Fourier Series Coefficients and Spectrogram](./Q1)
    [cite_start]This question focuses on the Discrete Fourier Series and its application to time-varying signals. [cite: 7] [cite_start]The tasks include writing functions to compute Fourier coefficients, reconstructing a signal from its coefficients, and implementing a Short-Time Fourier Transform (STFT) to generate a spectrogram (waterfall plot) for analyzing signals whose frequency content changes over time, such as a chirp signal. [cite: 9, 10, 21, 30]

* ### [Q2: Magnitude and Phase of Transformed Signals](./Q2)
    [cite_start]The goal here is to investigate the relative importance of magnitude and phase components of the Fourier Transform in 1D (audio) and 2D (image) signals. [cite: 58] [cite_start]The process involves swapping the magnitude and phase of two different signals (e.g., two audio files or two images) and then performing an inverse transform to determine which component preserves more of the original signal's perceptual information. [cite: 61, 62, 68]

* ### [Q3: FFT Performance Analysis](./Q3)
    [cite_start]This section analyzes the computational performance of the Fast Fourier Transform (FFT) algorithm. [cite: 72] [cite_start]It involves measuring and plotting the execution time of the FFT for signals of varying lengths to identify which lengths yield the best and worst performance. [cite: 73, 75, 76] [cite_start]Additionally, it compares the speed of direct convolution versus high-speed convolution implemented via FFT. [cite: 77, 84]

* ### [Q4: Up-Sampling and Down-Sampling of Audio Signals](./Q4)
    [cite_start]This question deals with changing the sampling rate of audio signals. [cite: 88] [cite_start]It requires implementing `Up-Sampler` and `Down-Sampler` functions. [cite: 90, 99] [cite_start]Up-sampling is achieved by inserting zeros between samples and applying a low-pass filter, while down-sampling involves low-pass filtering to prevent aliasing before discarding samples. [cite: 91, 100, 101]

* ### [Q5: Z-Transform](./Q5)
    [cite_start]The focus of this problem is the Z-Transform and its properties. [cite: 111] [cite_start]It includes manually calculating the Z-Transform for a given signal and verifying the result by implementing the transform as a digital filter and checking its impulse response. [cite: 112, 115, 119] [cite_start]The question also involves analyzing a causal system by finding its transfer function $H(z)$ and plotting its pole-zero diagram and frequency response. [cite: 122, 125, 126]

* ### [Q6: Channel Equalization for Audio Signals](./Q6)
    [cite_start]This task is an application of DSP in audio processing, specifically channel equalization. [cite: 127, 129] [cite_start]Using a pair of clean and distorted audio signals, the frequency response of the distorting system (channel) is estimated. [cite: 135] [cite_start]This estimated response is then used to create an inverse filter to recover a second distorted signal for which the original clean version is unavailable. [cite: 136]

* ### [Q7: Design and Analysis of a Multi-Band FIR Filter](./Q7)
    [cite_start]The final question involves designing a multi-band Finite Impulse Response (FIR) filter using three different windowing methods: Kaiser, Hamming, and Blackman. [cite: 138, 152] [cite_start]The objective is to design a filter with identical specifications using each window, then compare their performance based on their frequency response, optimal filter order, group delay, and phase linearity. [cite: 144, 160, 164, 167]
