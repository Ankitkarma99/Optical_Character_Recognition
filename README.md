# **📝 OCR Text Extraction System (Streamlit + EasyOCR)**

[![Python](https://img.shields.io/badge/Python-3.10-blue)]()
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red)]()
[![EasyOCR](https://img.shields.io/badge/EasyOCR-Text_Extraction-green)]()
[![OpenCV](https://img.shields.io/badge/OpenCV-Image_Processing-purple)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

---

## 📌 **Project Overview**

This is a lightweight and accurate **OCR (Optical Character Recognition)** system built using:

* **Streamlit** (Frontend UI)
* **EasyOCR** (Text Extraction)
* **OpenCV** (Preprocessing)
* **Python**

You can upload any image → the system extracts the text → displays it → and saves it inside **text.txt**.

Perfect for:
✔️ Text extraction
✔️ Document scanning
✔️ Image to text conversion
✔️ AI preprocessing tasks

---

## 🚀 **Features**

### 🔹 **Image Upload**

Upload `.png`, `.jpg`, `.jpeg`, `.webp`, `.bmp` files.

### 🔹 **OCR Processing**

Uses EasyOCR to detect English text from images.

### 🔹 **Text Output**

Extracted text is:

* Displayed directly on the app
* Saved to `text.txt` automatically

### 🔹 **Temporary File Handling**

Uploaded file saved as `temp.png` → deleted after OCR.

---

## 🗂 **Project Structure**

```
📦 OCR-Text-Extractor
│
├── app.py               # Streamlit UI
├── main.py              # OCR processing functions
├── text.txt             # Output extracted text
├── img_1.png            # Sample image
├── text.png             # Sample image
└── README.md
```

---

## 🧰 **Tech Stack**

| Technology    | Use                           |
| ------------- | ----------------------------- |
| **Streamlit** | Frontend Web UI               |
| **EasyOCR**   | Image → Text extraction       |
| **OpenCV**    | Image loading + preprocessing |
| **Python**    | Base programming              |

---

## 📥 **Installation**

### **1️⃣ Install Requirements**

```
pip install streamlit easyocr opencv-python matplotlib
```

### **2️⃣ Run the App**

```
streamlit run app.py
```

---

## ▶️ **How to Use**

1. Run the streamlit app
2. Upload an image using the file uploader
3. Click **Start OCR**
4. Extracted text will appear below
5. Same text will be saved to `text.txt`

---

## 📝 **Output Example (text.txt)**

```
An image or picture is a visual representation...
Images can also be animated through digital or physical processes...
```

---

## 📸 Sample Images

* **img_1.png**
* **text.png**

(You may add screenshots in README if needed)

---

## 🤝 Contributing

Pull requests welcome!

---

## 📜 License

MIT License.

---
