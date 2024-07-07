# Manuscript Translator Pro

## Overview
Manuscript Translator Pro is a powerful tool designed to digitize, recognize, and translate historical manuscript images. Leveraging the capabilities of Tesseract OCR and Google Translate, this tool extracts text from scanned images of manuscripts, identifies the language, and provides accurate translations. 

## Features
- **Optical Character Recognition (OCR)**: Extract text from manuscript images using Tesseract OCR.
- **Language Identification**: Automatically detect the language of the extracted text.
- **Text Translation**: Translate the extracted text into English or any other specified language using Google Translate.
- **Image Preprocessing**: Enhance image quality for better OCR results using grayscale conversion and binarization.

## Installation
To get started, clone this repository and install the required dependencies.

### Prerequisites
- Python 3.6 or higher
- Tesseract OCR

### Install Tesseract OCR
For Ubuntu:
```sh
sudo apt-get update
sudo apt-get install -y tesseract-ocr
```

### Install Python Dependencies
```sh
pip install pytesseract Pillow langdetect opencv-python googletrans==4.0.0-rc1
```

## Usage
Follow these steps to use Manuscript Translator Pro:

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/manuscript-translator-pro.git
   cd manuscript-translator-pro
   ```

2. **Upload Images**
   - Upload your manuscript images to the `images/` directory.

3. **Run the Script**
   ```sh
   python main.py
   ```

## Contributing
We welcome contributions! Please read our [CONTRIBUTING.md](https://github.com/Nick9695/Manuscript-Translator-Pro/blob/main/CONTRIBUTING.txt) to get started.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/Nick9695/Manuscript-Translator-Pro/blob/main/License.txt) file for details.

## Acknowledgements
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- [Google Translate](https://cloud.google.com/translate)
- [Google Colab](https://colab.research.google.com/)

## Contact Information 📧
 ![Screenshot 2023-12-11 224350](https://github.com/Nick9695/Personality-Quiz-Assignment/assets/148968130/3c82c2b7-876d-447d-b149-dcd2fddedf23)
**Nikhil Raju Gadekar**


- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/nikhil-gadekar-1951a8245)
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nick9695)
- [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gernikhilgadekar@gmail.com)

---

## References

[Database](https://github.com/tesseract-ocr/tessdata)




