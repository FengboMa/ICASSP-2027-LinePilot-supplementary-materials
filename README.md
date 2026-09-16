# LinePilot Digitizer: Online Appendix and Supplementary Materials

This repository contains the online appendix for the manuscript **“LinePilot Digitizer: Line-Plot Recovery with Manual and Automatic Calibration.”**

The appendix provides:

1. the complete representative digitization example;
2. additional details on the construction of DigitizerBench;
3. the analysis of benchmark factor effects for LinePilot (OCR) on DigitizerBench-Full; and
4. the human-guided analysis of LinePilot (standard) and LinePilot (enhanced) on DigitizerBench-Lite.

The compiled appendix is available as [`LinePilot_Online_Appendix.pdf`](LinePilot_Online_Appendix.pdf). The LaTeX source and figure used to build it are included in this repository.

## Terminology

- **LinePilot** refers to the complete digitizer.
- **LinePilot (OCR)** is the automatic calibration mode.
- **LinePilot (standard)** and **LinePilot (enhanced)** are the two human-guided calibration modes.
- **DigitizerBench** is the complete benchmark framework.
- **DigitizerBench-Full** is the 2,980-image automatic-evaluation benchmark.
- **DigitizerBench-Lite** is the 60-image human-guided benchmark.

## Build

Compile `main.tex` with a LaTeX engine that supports the supplied ICASSP style files. The bibliography uses `IEEEbib.bst`, `strings.bib`, and `refs.bib`.
