Sign Language to Text and Speech Conversion

Requirements:
- Python 3.7+ installed (download from python.org if needed).
- Webcam (built-in or external) for hand gesture detection.

Setup Steps:
1. Unzip this folder to your desired location.
2. Open a terminal/command prompt in the unzipped folder.
3. (Optional but recommended) Create a virtual environment: python -m venv venv
4. Activate the virtual environment: venv\Scripts\activate (Windows) or source venv/bin/activate (macOS/Linux)
5. Install dependencies: pip install -r requirements.txt
6. For the spell-check feature (enchant), you may need to install additional system libraries:
   - On Windows: Download and install from https://pypi.org/project/pyenchant/ (follow the "enchant" C library instructions).
   - On macOS: brew install enchant
   - On Linux: sudo apt-get install libenchant-2-2 (or equivalent for your distro)
7. Run the app: python final_pred.py

Notes:
- The app uses your webcam for real-time gesture recognition and text-to-speech.
- If you encounter errors, ensure all packages installed correctly and Python is in your PATH.
- Tested on Windows; may need adjustments for other OSes.