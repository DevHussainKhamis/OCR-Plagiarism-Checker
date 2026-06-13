# OCR-Plagiarism-Checker
A simple yet effective mobile app that detects plagiarism in text using manual input or OCR (Optical Character Recognition).

📝 Plagiarism Checker App
This is my university graduation project — a mobile application designed to help users check text for plagiarism quickly and easily. The app supports two input methods: typing directly into the app or using the built-in OCR feature to extract text from images.

✨ Features
Manual Text Input – Type or paste text to check

OCR Text Extraction – Capture an image, and Google ML Kit extracts the text automatically

Plagiarism Checking – Compares input text against sources and returns a similarity rate

Clean & Minimal UI – Simple interface focused on core functionality

🛠️ Tech Stack
Technology	Purpose
Flutter	Cross-platform mobile framework (Dart)
Google ML Kit	OCR – text recognition from images
Firebase	Backend, authentication, cloud functions (for plagiarism API calls)
🚀 How It Works
Enter text manually OR tap the OCR button to scan an image

Press "Check Plagiarism"

App sends text to Firebase Cloud Functions / backend

Similarity Rate (%) is displayed on screen


📂 Project Structure

lib/
├── screens/          # UI screens (home, OCR, results)
├── services/         # Firebase & ML Kit integration
├── widgets/          # Reusable UI components
└── utils/            # Helpers & constants
