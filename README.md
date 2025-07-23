# Screen Reader – Screen Reading Application

A Python application that lets you select any region of your screen, extract text with OCR, and play it back as speech.

---

## ✔️ Project Files

* **Screen reader.ipynb**
  Full demo: select region, OCR, and display results.
* **Screen reader used by openai.ipynb**
  Integration with OpenAI API for text-to-speech.
* **Creating a new voices.ipynb**
  Generating and saving new voice files (`.wav`).
* **Hearing the sounds created.ipynb**
  Playback and quality testing of generated voices.

---

## 🚀 Installation & Usage

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
2. (Optional) Set OpenAI API key:

   ```bash
   export OPENAI_API_KEY="sk-..."
   ```
3. Open and run the main notebook:

   * Launch Jupyter and open `Screen reader.ipynb`.
   * Execute cells (Shift+Enter).

---

## 📖 Quick Start

1. Run each cell as instructed.
2. Follow prompts to select a screen region.
3. Choose OCR engine (Tesseract/EasyOCR/OpenAI) and a voice.
4. Listen to the spoken text.

---

## 🤝 Contributing

Interested in improvements? Open an Issue or submit a Pull Request.

---

## 📄 License

Released under the MIT License.
