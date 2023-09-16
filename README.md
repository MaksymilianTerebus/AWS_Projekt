# AWS Project

## Table of Contents

1. [About The Project](#about-the-project)
    - [Aim of the Project](#aim-of-the-project)
    - [Technical Architecture](#technical-architecture)
    - [Tech Stack](#tech-stack)
    - [Dataset](#dataset)

## About the Project

### Aim of the Project

The primary aim of this project is to analyze variations in terrain elevation in specific regions across North and South America. The project focuses on identifying six regions with the most significant elevation changes to better understand the geographical features of these areas.

### Technical Architecture

The architecture of this project is designed for efficient data processing and visualization. AWS EMR handles resource management, while Spark serves as the principal tool for data processing. For analysis and visualization, Jupyter Notebooks are utilized alongside Python libraries like Matplotlib.

### Tech Stack

- Data Processing: Spark, PySpark
- Data Storage: AWS S3
- Visualization: Matplotlib
- Image Processing: OpenCV
- Numerical Computing: NumPy
- Backend: AWS EMR
- Source Control: GitHub

### Dataset

The project leverages data from the terrain-tiles dataset available on AWS. This dataset provides terrain height information globally and is formatted for ease of use. It's securely stored on AWS S3 and constitutes the foundation for the project's elevation change analysis in North and South America. [Access the dataset here](https://registry.opendata.aws/terrain-tiles/).
