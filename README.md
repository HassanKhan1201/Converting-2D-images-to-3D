# Project Title: 2D to 3D Conversion using Depth and Structure Maps

# Description:
This project aims to convert 2D images, specifically paired depth and structure maps, into 3D CAD models saved in the PLY format. It utilizes OpenCV and Open3D libraries to generate a 3D mesh from the input images and exports it for further use in CAD software.

# Features:
. Loads and processes depth and structure maps.

. Generates 3D point clouds from depth information.

. Performs Poisson surface reconstruction to create a 3D mesh.

. Saves the 3D model in PLY format for CAD applications.

# Installation:
To run this project, you will need to have the following libraries installed:
```
pip install opencv-python
pip install open3d
```

If you are using Google Colab, ensure that Open3D is installed using:
```
!pip install open3d
```

# Usage:
1. Clone the repository:

