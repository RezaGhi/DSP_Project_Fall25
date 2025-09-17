# Digital Signal Processing (DSP) Final Project

This repository contains the final project for the Digital Signal Processing course at the [Sharif University of Technology](https://en.sharif.ir/), under the instruction of [Dr. M.T. Manzuri](https://scholar.google.com/citations?user=NXYyxTMAAAAJ&hl=en). The project encompasses seven distinct questions, each exploring fundamental concepts and applications in DSP.

The complete project description can be found in the PDF file located in the [Question](./Question) directory.

---

## Project Questions Overview

Below is a brief summary of each question and a link to its corresponding solution directory.

* ### [Q1: Fourier Series Coefficients and Spectrogram](./Q1)
    This question focuses on the Discrete Fourier Series and its application to time-varying signals. The tasks include writing functions to compute Fourier coefficients, reconstructing a signal from its coefficients, and implementing a Short-Time Fourier Transform (STFT) to generate a spectrogram (waterfall plot) for analyzing signals whose frequency content changes over time, such as a chirp signal.

* ### [Q2: Magnitude and Phase of Transformed Signals](./Q2)
    The goal here is to investigate the relative importance of magnitude and phase components of the Fourier Transform in 1D (audio) and 2D (image) signals. The process involves swapping the magnitude and phase of two different signals (e.g., two audio files or two images) and then performing an inverse transform to determine which component preserves more of the original signal's perceptual information.

* ### [Q3: FFT Performance Analysis](./Q3)
    This section analyzes the computational performance of the Fast Fourier Transform (FFT) algorithm. It involves measuring and plotting the execution time of the FFT for signals of varying lengths to identify which lengths yield the best and worst performance. Additionally, it compares the speed of direct convolution versus high-speed convolution implemented via FFT.

* ### [Q4: Up-Sampling and Down-Sampling of Audio Signals](./Q4)
    This question deals with changing the sampling rate of audio signals. It requires implementing `Up-Sampler` and `Down-Sampler` functions. Up-sampling is achieved by inserting zeros between samples and applying a low-pass filter, while down-sampling involves low-pass filtering to prevent aliasing before discarding samples.

* ### [Q5: Z-Transform](./Q5)
    The focus of this problem is the Z-Transform and its properties. It includes manually calculating the Z-Transform for a given signal and verifying the result by implementing the transform as a digital filter and checking its impulse response. The question also involves analyzing a causal system by finding its transfer function $H(z)$ and plotting its pole-zero diagram and frequency response.

* ### [Q6: Channel Equalization for Audio Signals](./Q6)
    This task is an application of DSP in audio processing, specifically channel equalization. Using a pair of clean and distorted audio signals, the frequency response of the distorting system (channel) is estimated. This estimated response is then used to create an inverse filter to recover a second distorted signal for which the original clean version is unavailable.

* ### [Q7: Design and Analysis of a Multi-Band FIR Filter](./Q7)
    The final question involves designing a multi-band Finite Impulse Response (FIR) filter using three different windowing methods: Kaiser, Hamming, and Blackman. The objective is to design a filter with identical specifications using each window, then compare their performance based on their frequency response, optimal filter order, group delay, and phase linearity.
