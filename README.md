Enhanced Template Matching using OpenCV

This project enhances the classical template matching algorithm to overcome its limitations regarding orientation, scale, and single-object detection. The implementation extends traditional template matching to support rotation-invariant, scale-invariant, and multi-object detection, with an additional bonus implementation combining all three enhancements.

The system is implemented using Python and OpenCV, and each enhancement is applied independently to clearly demonstrate its effect. The project follows a structured, modular approach and is fully compatible with Google Colab.

🧠 Project Features
✅ Rotation-invariant template matching
✅ Scale-invariant template matching
✅ Multi-object template detection
✅ Combined rotation + scale + multi-object detection (BONUS)
✅ Google Colab compatible visualization
✅ Clear modular structure for educational purposes

🛠 Technologies Used
Python
OpenCV
NumPy
Google Colab

📂 Project Structure
Organized into clear sections for imports, parameters, functions, and execution
Each assignment part implemented and tested independently

📊 Input & Output
Input: Grayscale image and template image
Output: Image with detected template regions highlighted using bounding boxes

🎓 Academic Context
This project was developed as part of a Computer Vision / Image Processing assignment, focusing on improving template matching robustness against geometric variations.

🚀 Future Improvements
Non-Maximum Suppression to reduce overlapping detections
Feature-based matching (SIFT / ORB)
Performance optimization for large images
