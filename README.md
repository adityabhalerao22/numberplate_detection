# numberplate_detection
A computer vision solution for automatic license plate detection and character recognition using MATLAB. The system processes vehicle images to locate number plates and extracts alphanumeric characters through template matching and correlation analysis.

Automatic license plate localization using edge detection and region properties,
Character segmentation with morphological operations and area filtering,
Template-based character recognition for alphabets (A-Z) and digits (0-9),
Correlation-based matching algorithm for accurate character identification,
Preprocessing pipeline with grayscale conversion, binarization, and noise removal,
Robust bounding box detection for precise plate cropping,
Support for various image formats and plate orientations


- Letter_detection.m: Character recognition using template matching
- Plate_detection.m: Main plate detection and segmentation logic
- template_creation.m: Template creation for alphabets and numbers
