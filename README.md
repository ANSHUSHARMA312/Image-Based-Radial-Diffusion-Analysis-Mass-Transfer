# Image-Based Radial Diffusion Analysis - Mass Transfer

## Overview

This project analyzes mass transfer and diffusion phenomena using image-based computational methods. It focuses on radial diffusion analysis, providing tools to process, visualize, and analyze diffusion patterns from image data.

## Project Description

This is a course project (CHE213) that combines image processing with chemical engineering principles to:
- Extract diffusion profiles from image data
- Analyze radial diffusion patterns
- Calculate mass transfer coefficients
- Visualize concentration gradients over time

## Features

- **Image Processing**: Load and preprocess image data for analysis
- **Radial Diffusion Analysis**: Calculate diffusion coefficients from concentration profiles
- **Mass Transfer Calculations**: Compute key mass transfer parameters
- **Visualization**: Generate plots and heatmaps of diffusion patterns
- **Data Export**: Save results in multiple formats

## Technologies Used

- **Python**: Main programming language
- **NumPy**: Numerical computations
- **OpenCV/Pillow**: Image processing
- **Matplotlib/Seaborn**: Data visualization
- **SciPy**: Scientific computations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ANSHUSHARMA312/Image-Based-Radial-Diffusion-Analysis-Mass-Transfer.git
cd Image-Based-Radial-Diffusion-Analysis-Mass-Transfer
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

```python
# Basic usage example
from analysis import RadialDiffusionAnalyzer

# Load your image
analyzer = RadialDiffusionAnalyzer('path/to/image.jpg')

# Perform analysis
results = analyzer.analyze()

# Visualize results
analyzer.plot_results()
```

## Project Structure

```
├── README.md
├── requirements.txt
├── data/
│   └── sample_images/
├── src/
│   ├── image_processing.py
│   ├── diffusion_analysis.py
│   └── visualization.py
├── notebooks/
│   └── analysis.ipynb
└── results/
    └── outputs/
```

## Results

The analysis produces:
- Concentration vs. radial distance plots
- Diffusion coefficient calculations
- Mass transfer coefficient estimates
- Time-dependent concentration profiles

## Course Information

**Course**: CHE213 - Chemical Engineering Course Project  
**Topic**: Image-Based Analysis of Radial Diffusion in Mass Transfer

## Author

**Anshu Sharma** (ANSHUSHARMA312)

## License

This project is open source and available for educational purposes.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For questions or suggestions, please open an issue on GitHub.

---

**Last Updated**: July 6, 2026
