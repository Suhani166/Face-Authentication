# Face Authentication System

This is a Python-based face authentication system that allows users to generate face samples, train the system for recognition, and test the authentication process.

## Features
Face Generation: Users can capture multiple face samples for training the system.

Training Data: The system trains on the collected face samples to recognize users.

Authentication: Users can test the authentication system using trained data.

## Requirements
1) Python 3.x
2) OpenCV
3) NumPy
4) PIL (Python Imaging Library)

## Installation
1) Clone the repository:
   ```git clone https://github.com/Suhani166/Face-Authentication.git```
2) Install required dependencies:
```pip install opencv-python numpy pillow```
3) Run the `faceAuth.py` file: ```python faceAuth.py```
4) Follow the prompts in the terminal for face generation, training, and authentication.

## File Structure
`faceAuth.py`: Contains all functions for face authentication.

`user_data/`: Directory to store captured face samples.

## Instructions
1) Follow the instructions within `faceAuth.py` for each functionality (face generation, training, authentication).
2) Ensure proper lighting and camera setup for accurate face detection.
3) Press `Esc` to close the detection window during authentication.
   
## Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.
