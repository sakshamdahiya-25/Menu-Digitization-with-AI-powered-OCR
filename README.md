# 🍽️ Menu Digitization with AI-powered OCR

## 🚀 Project Overview
This project aims to **digitize food menu images** using **AI-powered Optical Character Recognition (OCR)** techniques. By leveraging **OpenCV, PIL, Tesseract, and EasyOCR**, we extract text from images and structure it into **JSON format** for seamless integration into digital platforms.

## 🔥 Features
- **Advanced Image Preprocessing**: Resizing, noise reduction, and binarization for improved OCR accuracy.
- **OCR Comparison**: Evaluating **Tesseract vs. EasyOCR** to determine the best performance.
- **Structured Data Output**: Extracted text is formatted into **JSON** for easy database integration.
- **User-Friendly Implementation**: Simple input mechanism for menu images.

## 📂 Project Structure
```
📦 Menu-Digitization-with-AI-powered-OCR
├── 📜 FOOD_MENU.ipynb  # Jupyter Notebook with complete implementation
├── 📁 images           # Sample food menu images
├── 📁 preprocessing    # Scripts for image preprocessing
├── 📁 results          # Extracted text and JSON outputs
├── 📄 README.md        # Project documentation
└── 📜 requirements.txt # List of required Python libraries
```

## 🛠️ Installation & Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/sakshamdahiya-25/Menu-Digitization-with-AI-powered-OCR.git
   cd Menu-Digitization-with-AI-powered-OCR
   ```

2. **Create a virtual environment (optional but recommended)**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🖼️ How It Works
1. Upload or provide a path to a **food menu image**.
2. The image undergoes **preprocessing** (resizing, denoising, binarization).
3. **OCR engines (Tesseract/EasyOCR)** extract text from the image.
4. Extracted text is structured into **JSON format**.
5. The output JSON can be stored in a **database or used for further applications**.

## 📌 Example Output (JSON)
```json
{
  "Restaurant": "Pizza Palace",
  "Items": [
    { "name": "Margherita Pizza", "price": "$10" },
    { "name": "Pepperoni Pizza", "price": "$12" },
    { "name": "Veggie Pizza", "price": "$11" }
  ]
}
```

## 🚀 Future Enhancements
- **Improve OCR accuracy** using deep learning-based text recognition.
- **Multi-language support** for menu digitization.
- **Automated category detection** (Appetizers, Mains, Desserts, etc.).
- **Integration with restaurant management systems**.

## 🤝 Contributing
We welcome contributions! If you'd like to improve the project, feel free to fork the repository and create a pull request. 😊

## 📝 License
This project is licensed under the **MIT License**.

## 📬 Contact
For any queries or collaborations, reach out via GitHub or LinkedIn! 🚀
