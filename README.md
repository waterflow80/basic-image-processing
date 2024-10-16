# basic-image-processing
In this project, we tried to implement multiple **computer vision & image processing** techniques, starting from the basic level of image manipulation to some advanced images segementation and texture analysis.

## Setup and Run
- Clone the repository on your local machine
- Create a virtual environemnt and activate it:
 ```sh
  python3.8 -m venv venv
  . venv/bin/activate
  ```
- Install the dependencies using `pip install -r requirements.txt`

## Code Structure
In this project, the code is structured into 4 main modules: `fundamentals`, `frequency-filters-segmentation`, `image-segmentation`, and `texture-analysis`.
### fundamentals/
In this modules, we make some basic image manipulation like:
- Image loading
- Handling channels
- Converting between channels
- Thresholding
- Histogram & intensity transformations:
  - Negative transformation
  - Log transformation
  - Power-law transformation (gamma transformation)
  - Histogram equialization
- Calculating image contrast

### frequency-filters-segmentation/
In this module, we do image segmentation using some frequency filtering techniques:
- Filter images using Fourier Transform
- Filter images using Wavelet Transform (also for image compression)
- Correct image using erosion and dilation

### image-segmentation/
