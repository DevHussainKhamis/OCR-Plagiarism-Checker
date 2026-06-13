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


📱 Screenshot


<img width="200" alt="App main screen" src="https://github.com/user-attachments/assets/119b7391-88c7-4943-87a0-fdc2bc9e35c5" />

<img width="200" alt="OCR feature screen" src="https://github.com/user-attachments/assets/c3a70fb5-899a-4bc0-bb72-2781e85c50e9" />

<img width="200" alt="Plagiarism result screen" src="https://github.com/user-attachments/assets/7afcc8d2-797d-4847-868d-4f342e035c94" />

<img width="200" alt="Another app screen" src="https://github.com/user-attachments/assets/3b226095-9066-4b9c-9c37-9442117c046f" />

<img width="200" alt="Final app screen" src="https://github.com/user-attachments/assets/2dcd46ad-8a79-435e-ae8e-38e82a8bb2f9" />
