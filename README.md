# Multi-Image Encryption System  
### Secure Image Encryption & Decryption with Fixed-Dimension Preprocessing
A modular image encryption and decryption system designed to securely process multiple images using controlled preprocessing and structured encryption logic.
This project demonstrates applied cryptography concepts, secure file handling, and modular software architecture with a Streamlit-based user interface.

##  Project Overview
Images come in varying dimensions and formats.  
For consistent encryption processing, this system:
1. Normalizes image dimensions to fixed square frames
2. Applies encryption logic
3. Allows secure decryption
4. Supports processing multiple images
The design ensures controlled preprocessing before cryptographic transformation.

##  System Architecture
Input Image
      ↓
Dimension Normalization (Fixed Square Frame)
      ↓
Encryption Algorithm
      ↓
Encrypted Output
      ↓
Decryption Module
      ↓
Original Image Restoration

##  Core Modules

### 1️. Streamlit Interface (`app.py`)
- Interactive user interface
- Upload images
- Trigger encryption / decryption
- Display processed results

### 2️. Image Preprocessing (`paste.py`)
- Resizes images into fixed square frames (e.g., 256x256, 512x512)
- Ensures uniform encryption processing
- Maintains image integrity

### 3️. Encryption Module (`encryption.py`)
- Implements image encryption logic
- Handles pixel-level transformations
- Produces encrypted output

### 4️. Decryption Module (`decryption.py`)
- Reverses encryption logic
- Restores original image
- Ensures data consistency

##  Tech Stack
- Python
- Streamlit
- Pillow (PIL)
- NumPy
- Cryptography
- Encryption Algorithm
Open the local URL in your browser and upload images for encryption or decryption.

## Key Features
- Multi-image processing capability
- Fixed-dimension normalization before encryption
- Modular encryption and decryption pipeline
- Streamlit-based interactive UI
- Clean separation of concerns
- Secure file handling workflow

##  Concepts Demonstrated
- Applied cryptography principles
- Image preprocessing for consistent encryption
- Modular software design
- Batch image handling
- Secure transformation pipeline
- Reversible encryption logic
- UI integration with backend processing

##  Potential Enhancements
- Add AES-based encryption mode
- Generate secure key management system
- Add password-based encryption
- Support bulk folder processing
- Add cloud deployment
- Add logging and audit trails
- Add checksum validation

## Real-World Applications
- Secure image storage
- Digital asset protection
- Secure image transmission
- Confidential document imaging
- Image-based data security pipelines
