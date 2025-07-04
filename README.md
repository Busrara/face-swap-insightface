# face-swap-insightface

This project demonstrates a simple face swapping application by the InsightFace library and a pre-trained ONNX model (`inswapper_128.onnx`). The project detects faces in images, extracts source faces, and swaps them onto target faces. 

This project is based on the tutorial found here: https://www.youtube.com/watch?v=a8vFMaH2aDw&t=2s 


## Features

- Face detection with InsightFace's `FaceAnalysis` model  
- Face swapping using the `inswapper_128.onnx` pre-trained model  
- Support for multiple faces in images  
- Visualizations using Matplotlib  
- Model downloaded directly from Hugging Face Hub  

## Installation

Make sure you have Python 3.7+ installed. Then install the required packages using pip:

```bash
pip install insightface opencv-python matplotlib huggingface_hub numpy
