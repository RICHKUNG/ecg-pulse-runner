# Bio-Voice Commander Documentation

This directory contains the comprehensive documentation for the Bio-Voice Commander project.

## 📚 Core Documentation

### 1. [Audio System Architecture](AUDIO_SYSTEM.md)
**Start here to understand how the system works.**
-   System overview and pipeline.
-   Comparison of recognition methods (MFCC vs Mel vs Ensemble).
-   Troubleshooting common issues (PyAudio errors, mic sensitivity).
-   Configuration guide.

### 2. [Experiment History & Optimization Log](EXPERIMENT_HISTORY.md)
**Read this to understand the "Why" behind the current design.**
-   Chronological log of all experiments.
-   Details on Latency Optimization (FastLPC, DTW Radius).
-   Details on Noise Robustness (Adaptive Ensemble, Spectral Subtraction).
-   Bug fix reports (SNR estimation, VAD adaptation).

### 3. [Testing & Benchmarking Guide](TESTING_GUIDE.md)
**Use this for validation and development.**
-   How to run the "Arena" benchmark (`test_file_input.py`).
-   How to view and compare historical results (`view_history.py`).
-   Tools for analyzing failures and bad templates.

### 4. [Project Plan & Roadmap](PROJECT_PLAN.md)
-   Current project status.
-   Completed milestones.
-   Future goals and advanced feature ideas.

---

## 📂 Other material

-   **[User guide (繁體中文)](user-guide.zh-TW.md)**: calibration flow, freedom mode, controls, ECG fallback options.
-   **[Results](results/)**: live-microphone QA reports and confusion matrices (`results/live_qa/`), template distance table.
-   **[Development notes](dev-notes/)**: integration log, ensemble arena report, file-organization notes; older notes in `dev-notes/archive/`.
-   **[Course documents](course/)**: project proposal and TA feedback.
-   **Experiment logs**: `../record/` and `../tests/record/` (JSON/Markdown output of the arena and QA scripts).

---

*Last Updated: 2026-10-08*
