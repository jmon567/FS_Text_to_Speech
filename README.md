```markdown
# TalkyFiles Audiobook Suite & Storefront

A full-stack audio publishing suite that instantly converts standard documents (PDF, Word, TXT) into high-quality MP3 audiobooks using Google Text-to-Speech. It pairs a multithreaded desktop generator with a responsive, Tailwind-styled web storefront to seamlessly create, host, and distribute digital audio content.

## 🛠️ Tech Stack
- `Python 3.8+`
- `Tkinter` (Desktop GUI)
- `gTTS` (Google Text-to-Speech)
- `PyMuPDF` & `docx2txt` (Document Parsing)
- `HTML5` / `Vanilla JS` / `Tailwind CSS` (Web Storefront)

## 🚀 Key Features
- **Multi-Format Text Extraction**: Accurately parses and extracts text from `.pdf`, `.docx`, and `.txt` files using optimized libraries to prepare content for vocal synthesis.
- **Automated TTS Conversion**: Leverages Google's Text-to-Speech engine to generate natural-sounding MP3 audio files, complete with exact runtime calculations via `mutagen`.
- **Asynchronous Desktop GUI**: Implements Python threading within a modern Tkinter interface to ensure the application remains highly responsive and prevents UI freezing during large file conversions.
- **Dynamic Web Distribution**: Includes a lightweight, responsive HTML frontend that utilizes Vanilla JavaScript to dynamically inject and serve generated audiobooks in a modern, scalable web grid.

## 📦 Installation & Setup

```bash
# Clone the repository
git clone [https://github.com/your-username/talkyfiles-audiobooks.git](https://github.com/your-username/talkyfiles-audiobooks.git)

# Navigate to the project directory
cd talkyfiles-audiobooks

# Create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install the required Python dependencies
pip install gTTS PyMuPDF mutagen docx2txt

# Launch the desktop audiobook generator
python app.py

# To view the storefront, open the HTML file in any modern browser
# (e.g., double-click index.html or serve locally)
python -m http.server 8000

```

## 📝 License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

```
