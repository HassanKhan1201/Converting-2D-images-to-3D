# Project Title: 2D to 3D Conversion using Depth and Structure Maps
![image](https://github.com/user-attachments/assets/b23398cb-3154-47d8-9da4-ac59e752a7a5)

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
```
git clone https://github.com/HassanKhan1201/Converting-2D-images-to-3D.git
```
  
2. Navigate to the project directory:
```
cd your-repo-directory
```

3. Open and run the Jupyter notebook `ipynb file` using Jupyter or Google Colab.

4. Ensure that your depth map and structure map images are available in the expected format and paths.

5. Modify the code to point to your image files if needed, and execute the notebook to generate a 3D PLY file.
   
# Inputs:
**Depth Map:** A grayscale image where the intensity values represent the distance of each pixel from the camera.

**Structure Map:** An outline or wireframe of the object's geometry for boundary detection.

# Output:
**PLY file:** A 3D CAD model in PLY format that can be visualized in tools like MeshLab, Blender, or CAD software.
