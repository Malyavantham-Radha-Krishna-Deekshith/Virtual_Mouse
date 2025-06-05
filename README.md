# Virtual Mouse

A Python-based project that allows users to control their computer mouse using hand gestures detected via a webcam. The Virtual Mouse leverages computer vision and machine learning techniques to interpret hand movements and translate them into cursor movements, clicks, and other mouse operations.

## Features

- **Hand Gesture Recognition**: Uses a webcam to detect and interpret hand gestures in real time.
- **Cursor Control**: Move the mouse pointer by moving your hand in front of the camera.
- **Click Simulation**: Perform left and right mouse clicks using specific hand gestures.
- **Scroll Functionality**: Scroll up and down using predefined gestures.
- **No Touch Required**: Completely contactless mouse control for hygiene and accessibility.

## Demo

![Virtual Mouse Demo](assets/demo.gif) <!-- Replace with actual demo path if available -->

## Installation

### Prerequisites

- Python 3.7+
- Webcam

### Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Or install the main dependencies individually:

```bash
pip install opencv-python mediapipe pyautogui
```

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/Malyavantham-Radha-Krishna-Deekshith/Virtual_Mouse.git
    cd Virtual_Mouse
    ```

2. Run the main program:

    ```bash
    python virtual_mouse.py
    ```

3. Allow camera permissions if prompted.
4. Follow the on-screen instructions to control your mouse using hand gestures.

## Configuration

- You can adjust sensitivity, gesture mappings, and other parameters by editing configuration variables in `virtual_mouse.py` (or the main script).
- For custom gestures or advanced features, see the documentation in the code comments.

## Folder Structure

```
Virtual_Mouse/
├── assets/                # Images, demo GIFs, etc.
├── modules/               # Core modules for gesture detection and mouse control
├── requirements.txt       # Dependencies
├── virtual_mouse.py       # Main script
└── README.md
```

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [Mediapipe](https://mediapipe.dev/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)

---

Feel free to open issues or submit pull requests for suggestions, bug reports, or improvements!
