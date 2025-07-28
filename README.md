# Air Canva

Air Canva is an interactive virtual drawing application that allows users to draw in the air using hand gestures, typically captured via webcam. It includes a Chrome Extension to interact with a webpage, making it suitable for remote collaboration or web-based interaction.

## 🧠 Features

- Draw using hand gestures without touching the screen.
- Real-time drawing via webcam using computer vision.
- Logging and server integration for communication and event tracking.
- Chrome extension for web interaction and additional controls.

## 📁 Project Structure

```
Air-Canva-master/
├── AirCanva.py                 # Main Air Canvas app
├── server.py                   # Backend server logic
├── requirements.txt            # Python dependencies
├── aircanva.log                # Application log
├── server.log                  # Server log
├── LICENSE                     # License file
├── Extention/                  # Chrome extension directory
│   ├── Webpage.html            # Extension webpage
│   ├── background.js           # Background logic for extension
│   └── content.js              # Script to manipulate webpage content
└── .idea/                      # IDE-specific project settings
```

## ⚙️ Installation

### Prerequisites
- Python 3.x
- Webcam
- Google Chrome (for using the extension)

### Steps
1. Clone or download this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Air Canva application:
   ```bash
   python AirCanva.py
   ```
4. (Optional) Launch `server.py` in a separate terminal if needed:
   ```bash
   python server.py
   ```

## 🧩 Chrome Extension

To use the extension:
1. Go to `chrome://extensions/`.
2. Enable "Developer Mode".
3. Click "Load unpacked" and select the `Extention/` folder.

## 📝 Logs

- `aircanva.log` – Captures runtime events of the Air Canva app.
- `server.log` – Records server-side events and communications.

## 🪪 License

This project is licensed under the terms of the LICENSE file in this repo.

## 🙌 Acknowledgements

- OpenCV for real-time image processing.
- Chrome APIs for browser extension interaction.
