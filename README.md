# 🎥🔊 Video to Audio Converter

This is a simple Python-based tool that extracts audio from a video file and saves it as an MP3 file using the powerful `moviepy` library.

## 🚀 Features
- Convert video files to audio (MP3)
- Fast and lightweight
- Easy to use

## 🛠️ Requirements
- Python 3.x
- `moviepy`

Install dependencies with:
```bash
pip install moviepy
```

## 📂 Usage
1. Clone the repository:
```bash
git clone https://github.com/tanush-47/Video-to-Audio-Conversion.git
cd Video-to-Audio-Conversion
```

2. Place your video file (e.g., `video.mp4`) in the project folder.

3. Run the script:
```bash
python convert.py
```

4. The audio will be saved as `output_audio.mp3` in the same folder.

## 🧾 Example
```python
from moviepy.editor import *

video = VideoFileClip("video.mp4")
video.audio.write_audiofile("output_audio.mp3")
```

## 📌 Notes
- Make sure the video file name matches the one in the script.
- Output format is `.mp3` by default but can be customized.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [Tanush Sharma](https://github.com/tanush-47)
