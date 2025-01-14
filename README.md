
# Gaussian and Laplacian Pyramids, Lucas-Kanade Optical Flow

## Project Description
This repository includes the implementation of Gaussian and Laplacian pyramids, along with the Lucas-Kanade optical flow algorithm. The project demonstrates image processing techniques such as reducing, expanding, and calculating optical flow between images. The hierarchical Lucas-Kanade algorithm is applied to different image sequences, and the results are analyzed through warping and computing difference images.

## Features
- **Gaussian Pyramid Construction**: Implements the REDUCE operation to generate Gaussian pyramids of multiple levels.
- **Laplacian Pyramid Construction**: Combines the REDUCE and EXPAND operations to generate Laplacian pyramids.
- **Lucas-Kanade Optical Flow**:
  - Single-level implementation.
  - Hierarchical implementation to handle large displacements.
- **Visualization**: Plots the results of optical flow and difference images for better analysis.
- **Applications**:
  - Optical flow calculation for various sequences like DataSeq1, DataSeq2, Juggle, and Taxis.

## Included Files
- `gaussian-laplacian-opticalflow.ipynb`: Jupyter Notebook containing the code for Gaussian and Laplacian pyramids, Lucas-Kanade optical flow, and hierarchical Lucas-Kanade.

## Requirements
- Python 3.x
- Libraries:
  - OpenCV
  - NumPy
  - Matplotlib

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/gaussian-laplacian-opticalflow.git
   ```
2. Navigate to the directory:
   ```bash
   cd gaussian-laplacian-opticalflow
   ```
3. Open `gaussian-laplacian-opticalflow.ipynb` in Jupyter Notebook or any compatible IDE.
4. Run the cells to execute the project and analyze the results.

## Results
- Constructed Gaussian and Laplacian pyramids for various image sequences.
- Optical flow results for sequences like Juggle and Taxis.
- Visualized warped images and difference images.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, feel free to reach out to Ricardo Modrego at [r.modrego.e@gmail.com](mailto:r.modrego.e@gmail.com).
