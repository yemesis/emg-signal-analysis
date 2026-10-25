# EMG: How the Biceps and Triceps Work During a Curl

What do your biceps and triceps actually do during a bicep curl, and does it change as the weight goes up?

**Lab experiment with individual report · Neuromechanics and Bioelectricity of Movement · Queen Mary University of London, 2023–24**

## What I did

We placed surface EMG electrodes on the biceps and triceps of two subjects and recorded their muscle activity during bicep curls with no weight, 2 kg, 4 kg and 6 kg. I processed the raw signals in MATLAB: notch and bandpass filtering to remove noise, then rectifying and smoothing. From the processed signals I calculated maximum amplitude, mean rectified value and RMS, and used a Fast Fourier Transform to look at frequency content.

## What went wrong

The first recordings were noisy. Poor electrode contact and movement during the curls were getting into the signal, so we made sure the electrodes were placed properly and cut down outside sources of interference.

## Results

- The biceps showed clearly higher activation than the triceps on every measure (maximum amplitude, mean rectified value and RMS), as you'd expect from the main lifting muscle.
- In the frequency analysis, the biceps had a sharper peak at lower frequencies, pointing to stronger, more synchronised activation while lifting.

![Raw EMG signal](figures/raw-emg-biceps.png)

![Rectified EMG signal](figures/rectified-emg-biceps.png)

![FFT of the biceps signal](figures/emg-fft-biceps.png)

## Tools

Surface EMG · MATLAB

## Files

- [Lab report](./emg-signal-analysis-report.pdf)
