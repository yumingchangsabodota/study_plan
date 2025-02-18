# Sound Digitalization Study Plan (with Rust)

## Section 1: Fundamentals of Digital Audio Processing
### Topics:
- Analog to Digital Conversion (ADC)
- Sample Rate and Bit Depth
- Nyquist Theorem and Aliasing
- Digital Filters (Low-pass, High-pass, Band-pass)

### Hands-on Project:
**Build a Basic WAV File Reader in Rust**
- Use the `hound` crate to read `.wav` files.
- Extract and display sample rate, bit depth, and duration.
- Convert raw amplitude values into a simple waveform plot.

---

## Section 2: Fourier Transform & Frequency Analysis
### Topics:
- Understanding the Discrete Fourier Transform (DFT) & Fast Fourier Transform (FFT)
- Spectrograms and Frequency Representation of Sound
- Windowing Functions (Hann, Hamming, Blackman)
- Implementing FFT in Rust using `rustfft`

### Hands-on Project:
**Build a Rust-based Spectrogram Generator**
- Take a `.wav` file as input.
- Apply FFT to analyze frequency components.
- Generate a basic spectrogram visualization using `plotters` crate.

---

## Section 3: Formants & Vocal Tract Resonances
### Topics:
- What are Formants? (Formant 1, Formant 2, Formant 3, etc.)
- How Formants Relate to Speech and Sound Analysis
- Linear Predictive Coding (LPC) for Formant Extraction
- Formant Tracking Algorithms

### Hands-on Project:
**Implement a Basic Formant Estimator**
- Use `rustfft` and apply Linear Predictive Coding (LPC) to extract **Formant 1, 2, and 3**.
- Plot frequency peaks to visualize detected formants.
- Compare results with speech samples.

---

## Section 4: Signal Processing & Noise Reduction
### Topics:
- Filtering Techniques for Noise Removal
- Cepstrum Analysis & Homomorphic Filtering
- Adaptive Filtering in Rust
- Pre-Emphasis Filters for Speech Processing

### Hands-on Project:
**Develop a Noise Reduction System**
- Implement a basic low-pass and high-pass filter.
- Use an adaptive filter to remove background noise.
- Compare pre-filtered vs. post-filtered sound.

---

## Section 5: Real-Time Sound Processing
### Topics:
- Capturing Live Audio Input in Rust (`cpal` crate)
- Real-time Audio Processing Pipelines
- Latency Optimization & Buffering

### Hands-on Project:
**Build a Real-Time Audio Analyzer**
- Capture microphone input using `cpal`.
- Perform FFT in real-time to visualize live sound.
- Display dominant frequency components.

---

## Section 6: Extracting Formant 3 from Live Audio
### Topics:
- Combining FFT and LPC for Formant Extraction
- Real-Time Feature Extraction Techniques
- Optimizing Audio Processing Performance

### Hands-on Project:
**Build a Rust App for Real-Time Formant 3 Extraction**
- Capture live audio input using `cpal`.
- Apply FFT + LPC in real-time to detect **Formant 3 (Hz)**.
- Display real-time frequency tracking on a UI (e.g., using `egui` for visualization).

---

## Section 7: Deploying and Optimizing Your Application
### Topics:
- Building a GUI for Your Rust Audio App (`eframe`, `druid`, or `iced` crates)
- Optimizing Performance for Real-Time Processing
- Packaging and Distributing the Application

### Final Hands-on Project:
**Build & Deploy Your Full-Fledged Formant 3 Analyzer**
- Combine all previous sections into a polished application.
- Provide
