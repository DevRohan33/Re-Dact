<p align="center">
  <img src="assets/logo.png" alt="Auto-Redaction Logo" width="150px"/>
</p>

<h1 align="center">🔒 Auto-Redaction Web App 🔒</h1>

<p align="center">
  <b>An Intelligent Redaction System to Protect Sensitive Data</b>  
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-Streamlit-orange?style=for-the-badge" alt="Built with Streamlit"/>
  <img src="https://img.shields.io/badge/OCR-TesseractOCR-red?style=for-the-badge" alt="OCR Tesseract"/>
  <img src="https://img.shields.io/badge/PDF-PyPDF-blue?style=for-the-badge" alt="PDF with PyPDF"/>
  <img src="https://img.shields.io/badge/Detection-PyTorch-purple?style=for-the-badge" alt="PyTorch Data Detection"/>
  <img src="https://img.shields.io/badge/InMemory%20Processing-Secure-green?style=for-the-badge" alt="In Memory Processing"/>
</p>

---

## 🌟 **About the Project**

🚀 The **Auto-Redaction Web App** is a state-of-the-art tool that allows users to **automatically redact sensitive information** in PDFs and images securely and efficiently. This tool utilizes **OCR technology** and **AI-based models** to ensure **privacy protection**, leveraging in-memory data processing to provide maximum security.

✨ **Key Highlights:**

- **Text Extraction**: Powered by **PyPDF**, **OpenCV**, and **TesseractOCR** to handle various formats.
- **Data Detection**: Implemented using **PyTorch** and **Pseudo Analyzer** to identify and redact sensitive data.
- **In-Memory Processing**: All operations occur in memory, ensuring no sensitive data is stored during processing.
- **User-Friendly Interface**: Built using **Streamlit**, the app provides an intuitive interface with easy file upload and download options.

---

## 🎬 **How It Works**

<p align="center">
  <img src="assets/flowchart.png" alt="How it works flowchart" width="600px"/>
</p>

Here’s a simple overview of the process flow for redacting sensitive data:

1. **Upload Your File**: Upload your PDF or image that contains sensitive data.
2. **Text & Data Detection**:
   - **Text Extraction** using **TesseractOCR** for images and **PyPDF** for PDF files.
   - **Sensitive Data Detection** using **PyTorch** and **Pseudo Analyzer** for identifying private or confidential information.
3. **Auto-Redaction**: The system applies redaction over the detected data with color overlays.
4. **Download the Redacted File**: Once processed, the system generates a link to download the redacted version of the file.

---

## ⚙️ **Technologies & Tools**

<p align="center">
  <img src="assets/tech_stack.png" alt="Technology Stack" width="700px"/>
</p>

| **Technology**         | **Purpose**                    |
| ---------------------- | ------------------------------ |
| **Streamlit**           | Frontend & UI Framework        |
| **TesseractOCR**        | Text Extraction from Images    |
| **PyPDF**               | PDF Text Extraction            |
| **OpenCV**              | Image Processing               |
| **PyTorch**             | AI-based Sensitive Data Detection |
| **Pseudo Analyzer**     | Advanced Data Analyzer for Redaction |
| **In-Memory Processing**| Ensures Data Security          |

---

## 🎥 **Demo Video**



https://github.com/user-attachments/assets/493cb849-b345-4702-9c9c-5ed8a7d00df9



<p align="center">
  <video width="600" controls>
    <source scr = "https://github.com/user-attachments/assets/493cb849-b345-4702-9c9c-5ed8a7d00df9
">
  </video>
   
</p>


## 📊 **Project Presentation**

Explore our detailed project presentation below!

<p align="center">
  <a href="https://github.com/user-attachments/files/17063803/presentation.pdf" target="_blank">
    <img src="https://github.com/user-attachments/assets/4c457fb5-cec0-4d99-bffc-5999246b7eaf" alt="Presentation Thumbnail" width="600" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/user-attachments/files/17063803/presentation.pdf" target="_blank">
    <img src="https://img.shields.io/badge/View%20Presentation-Download%20PDF-blue?style=for-the-badge" alt="Download Presentation"/>
  </a>
</p>



## 🛠 **Installation & Setup Guide**

To run this project locally, follow the steps below:

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/DevRohan33/Re-Dact.git
cd Re-Dact
```
### 2. 🧪 Create a Virtual Environment (Optional, but Recommended)

```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
```
### 3. 🧪 Install Dependencies

```bash
pip install -r requirements.txt
```
If you don't have a requirements.txt file, here’s a list of necessary packages:

```bash
pip install streamlit
pip install pytesseract
pip install opencv-python
pip install PyPDF2
pip install torch
pip install torchvision
pip install pseudo-analyzer  # Assuming it's a real package
```

### 4. 🔍 Install Tesseract OCR
- **Windows:** Download and install from here.{https://github.com/UB-Mannheim/tesseract/wiki}
- **macOS:** Install via Homebrew:
```bash
brew install tesseract
```
- **Linux (Ubuntu)**
```bash
sudo apt-get install tesseract-ocr
```
 
### 5. 🚀 Run the App
```bash
streamlit run app.py
```

### 🚨 Troubleshooting
- ⚠️ **Tesseract Path Issue:** Ensure Tesseract is added to the system PATH.
- 📦 **Package Errors:** If any packages raise issues, try updating them using:
```bash
pip install --upgrade <package_name>
```




## 🚀 **SIH 2024 - Auto-Redaction Web App (Project ID: 6069)** 🚀

We are an energetic and passionate team participating in **Smart India Hackathon 2024 (SIH 2024)** under the **Blockchain & Cybersecurity** category. With a shared goal of building a cutting-edge solution, we have combined our diverse skills and talents to develop an **Auto-Redaction Web App** that protects sensitive information through secure redaction.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/018c6989-1b17-4f8d-a5ca-eb4a77b34d83" alt="Logo" width="150px"/>
</p>


## 🌟 **Meet Our Incredible Team!** 🌟

| **Role**               | **Name**            | **Responsibilities**                                                                                         |
| ---------------------- | ------------------- | ------------------------------------------------------------------------------------------------------------ |
| 🧑‍💻 **Team Leader**        | **Syanjit Das**     | Leader of the project, managing development and overseeing team coordination. Developer for backend solutions. |
| 👨‍💻 **Co-Leader & Tech Lead** | **Rohan Parveag**   | Main developer, in charge of implementing the technical core of the project. Hands-on with Streamlit, OCR, and AI-based models. |
| 📝 **Content Writer (Co-Leader)** | **Isha Bishal**     | Co-Leader responsible for clear, concise, and creative content. Writes documentation, descriptions, and project summaries. |
| 🎨 **Presentation Designer** | **Subhamay Pal**    | Creative lead for presentations, ensuring engaging and impactful slides. Finds references to support project work. |
| 📊 **Researcher & Designer** | **Subhashish De**   | Works with Subhamay to design polished presentations and conduct research for references and project insights. |
| ✍️ **Content Developer**  | **Sumit Pal**       | Develops tutorials and user-friendly guides. Ensures all technical aspects are explained clearly in the documentation. |

---

### 🎯 **What We Do:**
Our project is centered on creating a **fully automatic redaction system** that identifies sensitive information within files and redacts it with color overlays. Here’s how we contribute:

- **Syanjit Das**: Leads the team with strong backend development. Ensures everything works securely and efficiently.
- **Rohan Parveag**: The technical brain of the project, developing both the core functionalities and advanced features of the web app.
- **Isha Bishal**: Writes compelling content, ensuring all documentation is clear, and the user experience is smooth.
- **Subhamay Pal & Subhashish De**: These two bring the project to life with visually stunning presentations and well-researched materials to back up our work.
- **Sumit Pal**: Ensures users understand the project with tutorials, guides, and easy-to-read documentation.

---

### 🏆 **Our Vision**: 
We believe in the power of collaboration and innovation. Together, we are building a **secure redaction system** that will protect sensitive data and keep users safe. We are excited to bring this solution to **SIH 2024** and demonstrate our collective efforts.

<p align="center">
  <img src="https://media.giphy.com/media/3oEjHP8ELRNNlnlLGM/giphy.gif" alt="Teamwork" width="300"/>
</p>

---

### 👥 **Team Members:**

<p align="center">
  <img src="https://img.shields.io/badge/Team-Leader-blue?style=for-the-badge&logo=github" alt="Team Leader"/>
  <b>Syanjit Das</b>  
  <br>
  <img src="https://img.shields.io/badge/Co-Leader-orange?style=for-the-badge&logo=github" alt="Co-Leader"/>
  <b>Sk Rohan Parveag</b> | <b>Isha Bishal</b>
  <br>
  <img src="https://img.shields.io/badge/Content%20Developer-red?style=for-the-badge&logo=github" alt="Content Developer"/>
  <b>Sumit Pal</b>
  <br>
  <img src="https://img.shields.io/badge/Presentation%20Designers-purple?style=for-the-badge&logo=github" alt="Presentation Designers"/>
  <b>Subhamay Pal</b> | <b>Subhashish De</b>
</p>

---

### 💡 **Want to Know More?**

Stay tuned for updates on our progress as we tackle this exciting challenge at **SIH 2024**! We are constantly improving and enhancing our solution, pushing the boundaries of cybersecurity and redaction technology.

---



