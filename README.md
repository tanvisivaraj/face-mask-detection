# face-mask-detection

This repository contains code for detecting face masks using deep learning. The model can classify whether a person is wearing a mask or not in real-time from webcam or image input.

## Features
- Real-time face mask detection via webcam
- Pre-trained model for quick deployment

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/tanvisivaraj/face-mask-detection.git
   cd face-mask-detection
   ```

2. **Set up your environment**:

   Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**:

   Install the required packages from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Run Face Mask Detection with Webcam

To detect masks in real-time using your webcam:
```bash
python detect_mask.py
```
