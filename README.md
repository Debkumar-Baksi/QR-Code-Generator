# 📱 QR Code Generator

## 📜 Description

This **QR Code Generator** is a Python script that allows users to generate a custom QR code for a provided URL. Users can customize the fill and background colors of the QR code. The generated QR code image is saved as `MyQR.png` in the same directory where the script is run.

---

## ✨ Features

- **Generate QR Codes**: Users can enter a URL to generate a QR code that links to that URL.
- **Customizable Colors**: Users can choose the fill and background colors for the QR code.
- **Image Output**: The generated QR code is saved as `MyQR.png` in the current working directory.

---

## 🛠️ Requirements

- Python 3.x
- `qrcode` library (for generating the QR code)
- `Pillow` library (for handling image processing)

Install the required libraries using pip:

```bash
pip install qrcode
pip install pillow
```
## 🖥️ How to Run
- **Prerequisites**: Ensure Python and the required libraries are installed.

- **Run the Script**:

  - Save the code to a file, for example, qr_code_generator.py.
  - Open a terminal/command prompt and navigate to the directory containing the script.
  - Run the script using the following command:
```bash
python qr_code_generator.py
```
- **Follow the Prompts**:

  - Enter the URL you want to encode into a QR code.
  - Enter the fill color (e.g., black).
  - Enter the background color (e.g., white).
The QR code will be saved as MyQR.png in the current working directory.

## 🛠️ Code Overview
**Imports**
- qrcode: A library for generating QR codes.
- qrcode.constants: Constants used to control QR code settings (e.g., error correction).
- Pillow: Used for saving the QR code image.

**Steps in the Script**
- User Input:

  - Takes input for the URL, fill color, and background color.
- QR Code Generation:

  - The qrcode.QRCode class is used to generate the QR code with the provided URL.
  - The QR code is customized with the user-specified colors.
- Saving the QR Code:

  - The QR code is saved as an image file (MyQR.png) using Pillow.
- Confirmation:

  - The script prints a confirmation message after the QR code is successfully generated.

## 📂 License
This project is licensed under the MIT License.

## 👤 Author
[Debkumar Baksi](https://www.linkedin.com/in/debkumar-baksi-269738279/) 

