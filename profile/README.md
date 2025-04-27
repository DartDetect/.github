# Dart Detect 🎯
 Dart Detect is a cross-platform, mobile-friendly application designed for dart players of all skill levels to improve their performance with automated scoring and performance tracking. 
 The application provides users with real-time dart detection, score calculation, and player/game statistics with the aid of cloud services and a trained Yolov5 model.
 ---
 ## Features
 - Real-time dart detection from both captured and uploaded images
 - Automated score calculation for Training Mode and Play Mode (501)
 - Player statistic tracking and history
 - Manual score editing for error correction
 - CSV export feature for play session data
 - Responsive design for web, Android, and IOS
 
 ## Technlogies
 - **Frontend**: React Native with EXPO
 - **Backend**: Flask API (Python)
 - **Cloud Storage**: AWS S3
 - **Authentication and Database**: Firebase Authentication & Firestore
 - **AI Model**: Yolov5 (PyTorch)
 
 ## Deployment
 - The frontend is deployed to **Firebase Hosting** for web access:[https://dartdetect-88d33.web.app/](https://dartdetect-88d33.web.app/)
 - The backend API runs **locally** for model inference and image processing

 ## Setup Instructions

 ### Frontend Setup (React Native App)
 1. Clone the repository:
    ```bash
    git clone https://github.com/DartDetect/dartdetect-cross-platform-app.git
    cd dartdetect-cross-platform-app/dart-detect-app
    ```
    
 2. Install Dependencies:
    ```bash
    npm install
    ```

 3. Start the Application:
    ```bash
    npx expo start
    ```
    
 The app can be opened on a web browser or for mobile, simply scan the QR code using the EXPO GO app.

### Backend Setup (Flask API)
1. Clone the repository:
   ```bash
   https://github.com/DartDetect/dartboard-backend-api.git
   cd dartboard-backend-api
   ```
2. Create a Python virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the virtual environment:
   ```bash
   venv\Scripts\activate
   ```
4. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. To run the backend Server:
    ```bash
   Python app.py
   ```
6. Python path might have to be set:
    ```bash
   $env:PYTHONPATH = "[YOUR_BACKEND_PROJECT_PATH]"
   python backend/app.py
   ```
 
 ## Usage
- Open the app using the Expo development server, or visit the [Dart Detect App](https://dartdetect-88d33.web.app/).
- Log in or create a new account.
- Navigate to  **Training Mode** or **Play Mode** using the navigation bar.
- Capture and upload images using the device's camera to detect darts.
- View or manually edit scores if needed in both modes.
- Navigate to **Dashbaord** to view statistics and previous **Play Mode** stats.
- Navigate to **PlayHistory** to view and filter all past play mode games and export to CSV to download game stats.
 
 
 ## Acknowledgements
 -  I would like to thank my supervisor, Ihab Salawdeh, for their continuous support 
and guidance throughout this project.
- Thanks also to the staff at ATU, and to friends and testers who provided valuable feedback during development.

 
