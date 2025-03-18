# ADAS & AI/ML Assessment

This project implements an Advanced Driver Assistance System (ADAS) using AI/ML techniques. It involves sensor data fusion, object detection using YOLOv8, and a simple collision avoidance system.

## Project Structure
- `adas_ai_ml_code.py`: Core implementation for data preprocessing, object detection, and collision avoidance.
- `sample_video.mp4`: Input video simulating camera data.

## Requirements
Ensure the following are installed:
- Python 3.8+
- OpenCV: `pip install opencv-python`
- NumPy: `pip install numpy`
- Matplotlib: `pip install matplotlib`
- YOLOv8: `pip install ultralytics`

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd adas-ai-ml-assessment
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the code:
   ```bash
   python adas_ai_ml_code.py
   ```

## Features
- **Camera Data Processing:** Utilizes YOLOv8 for real-time object detection.
- **Radar Data Simulation:** Generates random object data with distance, speed, and angle.
- **Object Visualization:** Displays detected objects using Matplotlib.
- **Collision Avoidance:** Provides warnings and triggers simulated braking if a collision is predicted.

## Example Output
- Visual representation of detected objects from the camera and radar.
- Real-time collision alerts in the console.

## Improvements
To enhance system efficiency, consider:
1. Integrating LiDAR data for more accurate distance estimation.
2. Implementing a Kalman Filter for better sensor fusion.
3. Applying model quantization to reduce YOLOv8's inference time.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV and Matplotlib libraries

