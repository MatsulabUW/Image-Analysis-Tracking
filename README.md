# 3-D Time-Series Microscopy Image Analysis
## Pipeline for time-series microscopy data on Clathrin-Mediated Endocytosis

![main gif](https://github.com/Mdanishnadeem/Image-Analysis-Tracking/blob/main/main_image.gif)

## Overview: 
This project aims to analyze the dynamics of clathrin-mediated endocytosis, with a specific focus on the roles played by dynamin and actin across various membrane domains (apical, basal, and lateral). The dataset comprises 3D time-series data acquired using lattice light sheet microscopy coupled with fluorescence techniques.

Furthermore, this endeavor seeks to elucidate the distinct roles of proteins such as dynamin and actin in orchestrating endocytic events across the diverse membrane landscapes.

Lastly, an interactive dashboard is also developed to assist with viewing raw tracks (2-D projections) and features of each track for all channels. This would assist in manually identifying valid tracks. 


## Installation:

```bash
git clone git@github.com:Mdanishnadeem/Image-Analysis-Tracking.git
conda create --name cme_pipeline python==3.10
conda activate cme_pipeline 
pip install -r requirements.txt
```

## Dashboard:

![dashboard](https://github.com/Mdanishnadeem/Image-Analysis-Tracking/blob/main/dashboard.png)

## Main Functions: 
The [src](https://github.com/Mdanishnadeem/Image-Analysis-Tracking/tree/main/Final/src) folder contains all the source code for this project. You can explore this folder to gain a more detailed understanding of the project's implementation.

Feel free to browse through the files and directories to learn more about how the project works.

## How to Run: 
A detailed guide for the entire project and steps involved can be found in [manual](https://github.com/Mdanishnadeem/Image-Analysis-Tracking/blob/main/Image%20Analysis%20Pipeline%20Explained.docx)


## Acknowledgements:

This project takes assistance from the following two projects:

1. [Pylattice](https://github.com/pylattice)
2. [LapTrack](https://github.com/yfukai/laptrack)