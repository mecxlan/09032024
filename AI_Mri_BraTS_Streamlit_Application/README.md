Mri Brain Tumor Segmentation FyP/
│
├── app.py                  # Streamlit application
├── model/
│   ├── model.hdf5          # U-Net architecture
│   └── unet.hdf5           # Pre-trained model weights
│
├── utils/
│   └── utils.py            # Utility functions
│
├──img/                                     # Images storing directory
│   ├── TCGA_CS_4941_19960909_10.png
│   ├── TCGA_CS_4941_19960909_14.png
│   ├── TCGA_CS_6667_20011105_14.png
│   ├── TCGA_DU_7013_19860523_24.png
│   ├── TCGA_DU_7014_19860618_24.png
│   ├── TCGA_DU_7019_19940908_19.png
│   ├── TCGA_DU_7304_19930325_25.png
│   ├── TCGA_DU_8163_19961119_19.png
│   ├── TCGA_DU_A5TP_19970614_24.png
│   ├── TCGA_DU_A5TU_19980312_14.png
│   ├── ars_logo.png                        # Logo image for app
│   └── mth_logo.png                        # Another logo image for app
│
├── requirements.txt        # Dependencies to install
├── README.md               # Project documeentation and setup instructions
└── .gitignore              # Specifies internationally untracked files

.\unetv1\Scripts\Activate

# MRI Brain Tumor Segmentation

## Description
This project utilizes a U-Net convolutional neural network to segment brain tumors from MRI scans. It is designed as a web application using Streamlit, allowing users to upload MRI images and view the segmentation results overlaid on the original images.

# Credits 
Developed by [https://img.shields.io/badge/Github:-mecxlan-black](https://github.com/mecxlan).

[https://img.shields.io/badge/Author:-mecxlan-blue](https://www.linkedin.com/in/mecxlan/)


# Acknowledgments
* [Dataset Source](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=5309188)
