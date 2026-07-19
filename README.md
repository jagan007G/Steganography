# 🖼️ Image Steganography Application

A Python-based desktop application that securely hides and extracts confidential messages inside digital images using **Least Significant Bit (LSB) Steganography**. The application provides an intuitive graphical user interface (GUI) built with **Tkinter**, allowing users to embed and retrieve secret messages without noticeably altering image quality.

---

## 📌 Features

- Hide secret text inside PNG images using LSB steganography
- Extract hidden messages from encoded images
- User-friendly graphical interface using Tkinter
- Preview selected images before encoding
- Save encoded images with embedded secret messages
- Supports image browsing through file explorer

---

## 🛠️ Technologies Used

- Python 3.x
- Tkinter (GUI)
- Pillow (PIL)
- Stegano Library
- LSB (Least Significant Bit) Steganography

---

## 📂 Project Structure

```
Image-Steganography/
│
├── main.py              # Main application
├── README.md
├── requirements.txt
├── assets/
│   ├── logo.png
│   └── screenshots/
└── output/
    └── hello.png
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Image-Steganography.git

cd Image-Steganography
```

### 2. Install dependencies

```bash
pip install pillow
pip install stegano
```

or

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python main.py
```

---

## 📖 How It Works

### Encoding Process

1. Open an image using **Open Image**
2. Enter the secret message in the text box
3. Click **Hide Data**
4. Save the encoded image using **Save Image**

### Decoding Process

1. Open the encoded image
2. Click **Show Data**
3. The hidden message is displayed in the text area

---

## 🔒 Steganography Technique

This project uses the **Least Significant Bit (LSB)** steganography technique.

The least significant bit of image pixels is modified to embed secret information while maintaining nearly identical visual appearance. Since only the least significant bits are changed, the modifications are imperceptible to the human eye.

---

## 💡 Applications

- Secure communication
- Digital watermarking
- Data privacy
- Information hiding
- Educational demonstration of steganography concepts

---

## 🚀 Future Enhancements

- AES encryption before embedding
- Password-protected extraction
- Support for larger payloads
- Drag-and-drop image support
- Multiple image format support
- Improved GUI design
- Save As functionality
- Progress indicator during encoding

---

## 📸 Screenshots

### Home Screen

*(Add screenshot here)*

### Hidden Message Extraction

*(Add screenshot here)*

---

## 📄 License

This project is developed for educational and learning purposes.
