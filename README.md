# 🎥 Depth Estimation from Video using MiDaS

This project performs monocular depth estimation on video frames using the [MiDaS](https://github.com/isl-org/MiDaS) deep learning model. It processes video files, extracts frames, generates depth maps, and optionally creates 3D point clouds from the predicted depth.

---

## 🧠 What It Does

- Extracts frames from an input video using OpenCV
- Applies MiDaS model to estimate depth from each frame
- Normalizes and saves depth maps as grayscale images
- Visualizes output with Matplotlib
- Generates a 3D point cloud using Open3D

---

## 🛠️ Tech Stack

- Python
- PyTorch (MiDaS via `torch.hub`)
- OpenCV
- Open3D
- Matplotlib
- NumPy

---

## 📝 How to Use

1. Upload a video (`.mp4`) to your working directory.
2. Run the Jupyter Notebook (`depth_estimation.ipynb`) cell by cell.
3. The notebook will:
   - Extract frames
   - Resize and process them
   - Estimate depth using MiDaS
   - Generate and visualize depth maps
   - Create a point cloud (optional)

---

## 📦 Dependencies

Install using:

```bash
pip install torch torchvision opencv-python open3d matplotlib numpy
