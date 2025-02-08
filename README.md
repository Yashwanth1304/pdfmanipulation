# 📄PDF Manipulation Tool

This Python project provides a collection of useful utilities for working with PDF files. It includes features such as merging PDFs, rotating pages, splitting PDFs, adding watermarks, extracting text, and converting text to audio. The tool uses popular libraries like `PyPDF2`, `pyttsx3`, and `PyMuPDF`.

## 🚀 Features

- 📑 **Extract Text** from PDFs  
- 🔗 **Merge Multiple PDFs**  
- 💧 **Apply Watermarks**  
- ✂️ **Split PDFs** into smaller sections  
- 🔄 **Rotate PDFs** at different angles  
- 🔊 **Convert PDF Text to Audio**


## Requirements

Make sure to install the necessary dependencies before using the tool:

```bash
pip install PyPDF2 pyttsx3 pymupdf
```

### 📚 Modules Used
- **PyPDF2** – Handles PDF operations  
- **PyMuPDF (fitz)** – Extracts text from PDFs  
- **pyttsx3** – Converts text to speech

## 🔧 Installation

1️⃣ Clone the repository:
   ```bash
   git clone https://github.com/Yashwanth1304/pdfmanipulation.git
   cd pdfmanipulation
   ```
2️⃣ Install requirements:
   ```bash
pip install PyPDF2 pyttsx3 pymupdf
```

   

## 🛠️ How to Use

Run the script and follow the menu options:


### 🎯 Available Operations

| Operation         | Description                                               |
| ----------------- | --------------------------------------------------------- |
| **Extract Text**  | Retrieve text from a specific page or paragraph 📄        |
| **Merge PDFs**    | Combine multiple PDFs into one 🔗                         |
| **Apply Watermark** | Add a watermark to a PDF 💧                             |
| **Split PDF**     | Extract a range of pages into a new PDF ✂️                 |
| **Rotate PDF**    | Rotate entire PDF or specific pages 🔄                    |
| **Text to Audio** | Convert extracted PDF text to speech 🔊                    |

## 📂 Example Usage

### 1️⃣ Extract Text from a PDF
- **Select option 1** in the menu.
- Input the PDF file name and the page number.
- **Output:** Displays the extracted text on the console.

### 2️⃣ Merge PDFs
- **Select option 2** in the menu.
- Enter the names of the PDFs to merge when prompted.
- **Output:** A merged PDF is saved with the specified output name.

### 3️⃣ Apply Watermark
- **Select option 3** in the menu.
- Provide the input PDF and the watermark PDF.
- **Output:** A new watermarked PDF is generated.

### 4️⃣ Split PDF
- **Select option 4** in the menu.
- Enter the start and end page numbers to split.
- **Output:** A new PDF with the specified range of pages is created.

### 5️⃣ Rotate PDF
- **Select option 5** in the menu.
- Input the rotation angle and choose the rotation option.
- **Output:** The PDF (or specific pages) is rotated as specified.

### 6️⃣ Text to Audio
- **Select option 6** in the menu.
- Enter the file name and specify the page range for conversion.
- **Output:** The text from the PDF is read aloud using text-to-speech.

## 👨‍💻 Author

This project was developed to provide a simple way to handle various PDF operations using Python. Happy coding! 🚀

## ⭐Contributing

Feel free to fork the repo, submit issues, and contribute!

## 📜License

This project is licensed under the MIT License.
