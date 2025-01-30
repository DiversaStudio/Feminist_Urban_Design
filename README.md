# Feminist Urban Design: AI-Powered Analysis of Public Space Safety

## Overview
This repository contains the research project "Integrating artificial intelligence (AI) and feminist urban design: A comparative study in South America and Southeast Asian public space". The study combines AI models with feminist urban design principles to analyze safety perceptions in public spaces across nine medium-sized cities in South America and Southeast Asia, focusing on low-income peripheral neighborhoods.

## Repository Structure
```bibtex
├── AISegmentation/       # AI models and segmentation analysis notebooks
├── DataExtraction/      # Scripts for data collection and processing
├── SuperResolution/     # Image enhancement using Real-ESRGAN
└── results/            # Output files, visualizations, and analysis results
```

## Methodology
1. **Data Collection**: Street-level images were systematically collected around bus stops using Google Street View API
2. **Image Enhancement**: Implemented Real-ESRGAN super-resolution model to improve image quality
3. **Feature Detection**: Applied YOLO-World object detection model to identify urban features
4. **Analysis**: Categorized features according to six feminist urban design principles:
   - Safety
   - Proximity
   - Diversity
   - Autonomy
   - Vitality
   - Representativeness

## Key Findings
- Safety-related features: 56.37%
- Proximity features: 22.46%
- Autonomy features: 9.66%
- Vitality features: 6.41%
- Diversity features: 4.93%
- Representativeness features: 0.16%

## Requirements
- Python 3.8+
- PyTorch
- YOLO-World
- Real-ESRGAN
- Google Street View API access
- Additional dependencies listed in `requirements.txt`

## Usage
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Follow the notebooks in each directory for specific analysis steps

## Authors
Medina, A., Mosquera, D., & Gallegos, F. (2025).

## Acknowledgements
Special thanks to Vasconez J. & Mosquera K. for their contributions to this research.

## Citation
```bibtex
@article{medina2025integrating,
  title={Integrating artificial intelligence (AI) and feminist urban design: A comparative study in South America and Southeast Asian public space},
  author={Medina, A. and Mosquera, D. and Gallegos, F.},
  year={2025}
}
