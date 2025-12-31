# Audio Latency Tester 🎧

A precise, web-based tool designed to measure the audio delay (latency) of Bluetooth headphones and speakers. Built with the Web Audio API for sample-accurate timing and HTML5 Canvas for high-performance visuals.

Originally vibe-coded using [Gemini Canvas](https://deepmind.google/technologies/gemini/).

## 🚀 Features

- Sample-Accurate Timing: Uses the hardware audio clock for precision superior to video files.
- High-Refresh Rate Ready: Optimized for 144Hz+ monitors for smooth, readable animations.
- Visual Calibration: Includes millisecond sweeper bar, physics-based bounce, and flash triggers.
- Smart Analysis: Calculates average reaction-adjusted latency over the last 10 taps.
- Responsive: Touch-optimized for mobile and desktop.

## 🛠️ How to Use

1. Start: Click Start Test (requires user interaction to enable audio).
2. Test: Close your eyes and tap Spacebar or the Mark button exactly when you hear the beep.
3. Read Results: Repeat 10+ times. The tool displays your average delay in milliseconds.
    - Positive: Audio lag (audio is late).
    - Negative: Early input or predictive tapping.

## ⌨️ Shortcuts

- S - Start / Stop
- Space / Enter - Mark Hit
- C - Clear History

## 👨‍💻 Author

Created by Yuya Iwabuchi
- [GitHub Profile](https://github.com/yuya-iwabuchi)
- [LinkedIn](https://www.linkedin.com/in/yuyai)

📄 License

Open source under the MIT License.
