## Computer Vision Project — Facial Emotion Recognition
This repository contains the Colab notebooks and supporting code used for the course on AI in Service (**DLBDSEAIS02**).
It provides the full training pipeline and a ready-to-use web interface for facial emotion recognition using transfer learning.

The RAF-DB dataset used for fine-tuning is available at: https://www.kaggle.com/datasets/shuvoalok/raf-db-dataset

Note: The dataset is not included in this repository as it is licensed for non-commercial research and educational purposes only and cannot be redistributed. It is accessed directly via KaggleHub inside the training notebook.

The trained model weights are hosted on Hugging Face at: https://huggingface.co/cws18/CV_uni_project

---

### Repository Structure
| Path | Description |
|------|--------------|
| `computer_vision_project.ipynb` | Training notebook including data loading, model training and evaluation |
| `gradio_interface_demo.ipynb` | Gradio demo notebook, loads weights from Hugging Face |
| `README.md` | Project information |

### Running the Demo in Google Colab
To run the web interface without training the model, open the Gradio demo notebook directly in Google Colab:

[Open Gradio Demo in Colab](https://colab.research.google.com/github/cws18/CV_uni_project/blob/main/gradio_interface_demo.ipynb)

Run all cells and the trained model weights are downloaded automatically from Hugging Face. 
No dataset download or training required.


### Running the Full Training Notebook in Google Colab
To run the full training pipeline, open the main notebook in Google Colab:
[Open Training Notebook in Colab](https://colab.research.google.com/github/cws18/CV_uni_project/blob/main/computer_vision_task_3.ipynb)

