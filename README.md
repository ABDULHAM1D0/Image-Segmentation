# 🧠 SAM2 Object Segmentation Demo
This project demonstrates interactive object segmentation using Meta's Segment Anything Model 2 (SAM2).
Users can upload an image and segment specific objects using prompts such as points or bounding boxes.
The project is designed as a beginner-friendly demo to understand how modern foundation models can be used for image segmentation tasks.

# 🎯 Project Goal
To segment user-specified objects in an image using SAM2 Large with prompt-based guidance.

# 📥 Input and 📤 Output
## Input:
- An image file
- A prompt indicating the object to segment:
  - Point prompt (click location on object)
  - Box prompt (bounding box around object)
## Output:
- Segmentation mask image of the selected object
- Saved mask file for further use

# 🧩 Features
- Prompt-based object segmentation
- Supports point prompts
- Supports bounding box prompts
- Uses SAM2 Large pretrained weights from Meta
- Saves segmentation masks as image files
- Simple and easy-to-understand notebook implementation

# 🏗️ Model Information
- Component	Details
Model	Segment Anything Model 2 (SAM2)
Variant	SAM2 Large
Weights	Official pretrained weights from Meta
Fine-tuning	❌ No fine-tuning (inference only)
▶️ How to Run

This project is implemented in a Jupyter Notebook.

Install required dependencies (PyTorch, OpenCV, SAM2 libraries, etc.)

Open the notebook:

jupyter notebook


Run all cells step by step

Upload an image

Provide a point or box prompt to segment the object

The segmentation mask will be displayed and saved

🧰 Technologies Used

Python

PyTorch

SAM2 (Meta AI)

OpenCV

Jupyter Notebook

👨‍🎓 Intended Audience

This project is intended as a beginner-level demonstration for students and developers who want to:

Learn how SAM2 works

Understand prompt-based image segmentation

Experiment with foundation models in computer vision
