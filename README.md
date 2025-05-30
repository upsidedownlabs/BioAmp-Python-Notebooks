# BioAmp-Python-Notebooks

**BioAmp-Python-Notebooks** is a curated collection of beginner-friendly Python notebooks designed to help users understand and work with bio-potential signals using hardware like BioAmp boards and analysis tools such as NeuroKit2.

Currently, this repository features a complete **ECG (Electrocardiogram) Signal Processing and Analysis Notebook**, ideal for students, researchers, and hobbyists who want to learn the step-by-step workflow of acquiring, processing, and analyzing ECG data in real-time.

## 📌 Features of the ECG Notebook

This notebook is structured to guide you through every stage of ECG signal analysis:

### 1. **Library Imports**

Start by importing all necessary Python libraries such as `numpy`, `matplotlib`, `scipy`, `pandas`, and `neurokit2`.

### 2. **Initialize Chords_USB Client**

This cell checks for connected compatible hardware, initializes the client, and starts real-time data streaming from the ECG hardware.

### 3. **Real-time ECG Data Acquisition**

Collect ECG data in real-time. This cell sets up a live plot window that updates continuously as data is received for a specified time duration.

### 4. **Signal Processing**

Apply a **notch filter** (to remove powerline interference) and a **low-pass filter** to clean the raw ECG signal. The processed signals are then saved to a CSV file for further analysis. Visualizations are also provided for comparison.

### 5. **ECG Analysis Pipeline using NeuroKit2**

Use the `neurokit2` library to extract meaningful features from the ECG signal, including:

* **PQRST Complex Analysis**: Detect and label P, QRS, and T waves.
* **ECG Beat Morphology**: Align beats to R-peaks, visualize individual beats, and compute an average beat morphology.

### 6. **Stop Streaming**

Send a STOP command to terminate the data acquisition process safely.

## 🎯 Who Is This For?

* 🧑‍🎓 **Students** looking for a hands-on introduction to bio-potential signal processing.
* 🧪 **Researchers** interested in analyzing ECG data using Python.
* 💡 **Developers** building health-related apps or tools.
* ❤️ **Hobbyists** experimenting with bio-potential signals and DIY health tech.

## 🚀 Getting Started

1. **Clone this repository**

```bash
git clone https://github.com/upsidedownlabs/BioAmp-Python-Notebooks.git
```

2. **Install required packages**

```bash
pip install -r requirements.txt
```

3. **Run the ECG Notebook**

   * Open the `.ipynb` file in Jupyter Notebook or JupyterLab.
   * Follow each cell in sequence.

## 📌 Upcoming Notebooks

The repo will gradually include:

* EMG (Electromyography) Signal Analysis
* EEG (Electroencephalogram) Feature Extraction
* EOG (Electrooculogram) Blink Detection

Stay tuned!

## 🤝 Contributing

Contributions, issues, and suggestions are welcome! If you have your own notebooks or improvements, feel free to submit a pull request.