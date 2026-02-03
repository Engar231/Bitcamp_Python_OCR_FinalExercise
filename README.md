# Bitcamp_End_Project/EasyOCR,Tesseract,Read_TGC_Artist
Final project for Bitcamp.
This application uses pytesseract and EasyOCR to perform optical character recognition on trading cards.
Through a manually selected crop area, the program detects the illustrator’s name and displays it in the application interface (main.py).

#The dataset includes:

Trained models for macro categories (One Piece, Magic, Digimon, etc.)

A separate model for micro categories (Italian playing cards – Briscola)

The Briscola dataset was built manually using both online images and personal photographs. Due to its limited size, a custom strategy was applied to improve usability during training.

The model was trained using 224×224 input images, focusing on demonstrating performance under limited hardware resources.

This project has significant room for improvement and will be further developed in future iterations.

#Requirements

Python

Tesseract OCR (Windows installer included)

Required language packages for Tesseract

#Note

Image quality strongly affects OCR accuracy; very low-resolution images (60–120 px) may reduce performance.

The default directory in main.py points to a local path and must be updated before execution.
