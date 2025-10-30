```markdown
# 🎬 Auto Reel Generator

An AI-powered Python project that automatically generates **short video reels** using **OpenCV**, **MoviePy**, and **Google Image Crawler**.  
Each reel compares two visual concepts (like *Cat vs Dog*, *Iron Man vs Captain America*, etc.) and combines them with background music and video — ready for YouTube Shorts, Instagram Reels, or TikTok!

---

## 🚀 Features

- 🧠 **Automatic Image Downloading:** Fetches themed images for each category pair.  
- 🎥 **Video Creation:** Combines images with a background video and smooth transitions.  
- 🎵 **Music Integration:** Adds background audio automatically.  
- 💾 **Progress Tracking:** Automatically resumes from where it stopped.  
- ⚙️ **Fully Customizable:** Change categories, background videos, and output folder easily.

---

## 🧩 Project Structure

```

AutoReelGenerator/
│
├── main.py                # Main script to generate reels
├── requirements.txt       # Required Python libraries
├── README.md              # Project documentation
├── .gitignore             # Files/folders to ignore in Git
├── images/                # Downloaded images
└── All_Reels/             # Final generated reels

````

---

## 🧠 How It Works

1. The script loops through **category pairs** (e.g., "Cat vs Dog").  
2. Downloads 1–2 images for each category using **Google Image Crawler**.  
3. Combines them with:
   - A **background video**
   - **Music track**
   - Simple transitions  
4. Saves the final short video inside the `All_Reels` folder.  
5. Updates progress in `progress.json` for restart-safe execution.

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/auto-reel-generator.git
   cd auto-reel-generator
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python main.py
   ```

---

## 🧰 Requirements

* Python 3.8 or higher
* Libraries:

  * `opencv-python`
  * `moviepy`
  * `icrawler`
  * `numpy`

Install all at once:

```bash
pip install opencv-python moviepy icrawler numpy
```

---
---

## 🧑‍💻 Author

**Abdul Rehman Makki**
AI Engineer 
📍 Karachi, Pakistan
🌐 [LinkedIn Profile](www.linkedin.com/in/abdul-rehman-makki)

---

## ⭐ Support

If you like this project:

* Give it a ⭐ on GitHub

---


or keep this **detailed version** (good for showcasing your work to recruiters or clients)?
```
