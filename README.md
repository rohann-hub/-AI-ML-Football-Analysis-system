<!-- GitHub-Compatible README HTML -->

<h1 align="center">⚽ AI/ML Football Analysis System using YOLOv8 + OpenCV + Python</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenCV-Installed-green?logo=opencv" />
  <img src="https://img.shields.io/badge/YOLOv8-Ultralytics-blueviolet?logo=ultralytics" />
  <img src="https://img.shields.io/badge/RealTime-Football_Tracking-orange" />
</p>

<p align="center">
  <strong>⚡ A real-time Football Player & Ball Analysis System using Deep Learning, YOLOv8, and OpenCV.</strong><br>
  <em>Detect. Track. Analyze. Visualize.</em>
</p>

<hr>

<h2>✅ Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>YOLOv8 Model (Ultralytics)</li>
  <li>OpenCV</li>
  <li>Supervision</li>
  <li>Roboflow (Optional: Dataset Management or Train Dataset)</li>
  <li>Webcam or match video input</li>
</ul>

<hr>

<h2>📦 Installation</h2>
<p>Install all required libraries:</p>

<p>
  🔹 <strong>Install OpenCV:</strong><br>
  <img src="https://img.shields.io/badge/pip--install-opencv--python-orange?logo=pypi" />
  <pre><code>pip install opencv-python</code></pre>
</p>

<p>
  🔹 <strong>Install Ultralytics (YOLOv8):</strong><br>
  <img src="https://img.shields.io/badge/pip--install-ultralytics-blueviolet?logo=pypi" />
  <pre><code>pip install ultralytics</code></pre>
</p>

<p>
  🔹 <strong>Install Other Required Libraries:</strong>
  <pre><code>pip install numpy pandas scikit-learn matplotlib roboflow supervision</code></pre>
</p>

<p>
  🔹 <strong>Built-in Python Modules:</strong><br>
  <code>pickle, os, shutil</code> – No installation required.
</p>

<hr>

<h2>🧠 YOLOv8 Model</h2>
<ul>
  <li>Model used: <code>yolov8n.pt</code> (YOLO Nano for speed)</li>
  <li>Place model at: <code>./models/yolov8n.pt</code></li>
  <li>Download from: <a href="https://github.com/ultralytics/ultralytics#models" target="_blank">Ultralytics Model Zoo</a></li>
</ul>

<hr>

<h2>🚀 How to Run</h2>

<pre><code># 1. Clone this repository
git clone https://github.com/rohann-hub/AI-ML-Football-Analysis.git
cd AI-ML-Football-Analysis

# 2. Run the main script
python main.py
</code></pre>

<p>
  The script will automatically process a match video or webcam and begin live detection, tracking, and analysis.
</p>

<hr>

<h2>📂 Project Structure</h2>

<pre><code>
AI-ML-Football-Analysis/
├── main.py
├── camera_movement/
│   └── __init__.py
├── player_ball_assigner/
│   └── player_ball_assigner.py
├── team_assigner/
│   └── team_assigner.py
├── trackers/
│   └── tracker.py
├── utils/
│   └── helpers.py
├── models/
│   └── yolov8n.pt
</code></pre>

<hr>

<h2>🛠 Technologies Used</h2>
<ul>
  <li><strong>Python</strong> – Core programming language</li>
  <li><strong>OpenCV</strong> – Frame handling and visualization</li>
  <li><strong>YOLOv8</strong> – Object detection (Ultralytics)</li>
  <li><strong>Supervision</strong> – Bounding box and annotation support</li>
  <li><strong>Roboflow</strong> – Dataset processing (optional)</li>
  <li><strong>scikit-learn</strong> – Team classification (optional)</li>
</ul>

<hr>

<h2>📌 Core Features</h2>
<ul>
  <li>Real-time Football Detection & Tracking</li>
  <li>Player and Ball Identification</li>
  <li>Team Color Assignment</li>
  <li>Motion and Tactical Analysis (Extensible)</li>
  <li>Minimal, modular codebase</li>
</ul>

<hr>
<h3 align="center">
  📁 <a href="https://drive.google.com/drive/folders/1oEZ3o797LzqEcSk86u0EqF-00Qbm4Yp1?usp=sharing" target="_blank"><strong> Download Pretrained Models & Training Files Below</strong></a>
</h3>


<h2>📬 Connect with Me</h2>
<ul>
  <li>🔗 <a href="https://www.linkedin.com/in/rupjit-shil/" target="_blank">LinkedIn – Rupjit Shil</a></li>
  <li>🐙 <a href="https://github.com/rohann-hub" target="_blank">GitHub – rohann-hub</a></li>
</ul>

<hr>


<p align="center">
  ⭐ <strong>If you like this project, please consider giving it a star!</strong> ⭐
</p>
