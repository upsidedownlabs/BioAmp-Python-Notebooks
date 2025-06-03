# BioAmp-Python-Notebooks

**BioAmp-Python-Notebooks** is an open-source collection of Python notebooks for biosignal processing, designed to make bio-potential signal analysis accessible to everyone. Whether you're working with BioAmp hardware or other acquisition systems, these notebooks provide complete workflows for processing and analyzing physiological signals.

## Featured Notebooks

- **ECG Signal Processing**: Complete pipeline for electrocardiogram analysis from acquisition to feature extraction
- **EMG Signal Processing**: End-to-end electromyography processing for muscle activity analysis

Perfect for:
- **Students** learning bio-potential signal processing
- **Researchers** needing reproducible analysis pipelines
- **Developers** building health-tech applications
- **Hobbyists** exploring physiological computing

## 📌 Features of the Notebooks

### ECG Notebook
This notebook guides you through every stage of ECG signal analysis:
1. **Library Imports** - All necessary Python libraries
2. **Initialize Chords_USB Client** - Connect to BioAmp boards
3. **Real-time ECG Data Acquisition** - Collect data with live plotting
4. **Signal Processing** - Notch and low-pass filtering
5. **ECG Analysis Pipeline** using NeuroKit2:
   - PQRST Complex Analysis
   - ECG Beat Morphology
6. **Data Export** - Save processed signals to CSV
7. **Stop Streaming** - Terminate acquisition safely

### EMG Notebook
This notebook provides comprehensive EMG signal processing:
1. **Library Imports** - All necessary Python libraries
2. **Initialize Chords_USB Client** - Connect to BioAmp boards
3. **Real-time EMG Data Acquisition** - Collect data with live plotting
4. **Signal Processing**:
   - 50Hz notch filter for powerline noise removal
   - 70Hz high-pass filter for EMG signal isolation
5. **Visualization**:
   - Raw vs filtered signal comparison
   - Muscle activation envelope
6. **EMG Strength Meter** - Real-time muscle activation level display
7. **Data Export** - Save processed signals to CSV
8. **Stop Streaming** - Terminate acquisition safely

## 🎯 Who Is This For?

- 🧑‍🎓 **Students** looking for hands-on biosignal processing
- 🧪 **Researchers** analyzing physiological data
- 💡 **Developers** building health-related applications
- ❤️ **Hobbyists** experimenting with bio-potential signals

## 🚀 Getting Started

1. **Clone this repository**
```bash
git clone https://github.com/upsidedownlabs/BioAmp-Python-Notebooks.git
```

2. **Install required packages**
```bash
pip install -r requirements.txt
```

3. **Run the Notebooks**
   - Open the `.ipynb` file in Jupyter Notebook/Lab
   - Follow each cell in sequence

## 📌 Upcoming Notebooks

The repo will gradually include:

* EEG (Electroencephalogram) Feature Extraction
* EOG (Electrooculogram) Blink Detection

Stay tuned!

## 🤝 Contributing

Contributions, issues, and suggestions are welcome! If you have your own notebooks or improvements, feel free to submit a pull request.