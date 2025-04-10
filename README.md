# Hello 3D World 🌍🎥

This project is a **work-in-progress** demonstration of how to go from **multi-camera images** to a basic **3D reconstruction** using Python.

Currently, there is **no real image data** yet — just a few example coordinates in 3D space. The goal is to build toward a working pipeline where pixel detections from multiple camera angles are triangulated into 3D positions.

## 📚 What’s in the notebook?

The [Colab notebook](https://colab.research.google.com/) contains:

- A "Hello World" example that:
  - Defines a few fictional camera positions in 3D
  - Simulates 2D keypoint detections
  - Uses triangulation logic to reconstruct a 3D point
- Simple visualizations of camera rays and 3D results
- Placeholder functions for distortion correction and calibration (not yet implemented)

## 🚀 How to use

1. Open the notebook in Google Colab.
2. Run the cells step by step.
3. See how simulated camera observations can result in a 3D point.

## ⚠️ Disclaimer

This is **not a complete system** yet. It’s just a small testbed to experiment with concepts like:

- 3D geometry
- Triangulation
- Camera calibration
- Multi-view vision

Stay tuned as we continue building toward a real-time 3D pipeline.

---

Made with ♥ by the DairyCampus Vision Team 🐄👁️
