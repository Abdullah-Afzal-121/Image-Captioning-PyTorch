# Image-Captioning-PyTorch
# Image Captioning with PyTorch

AI that describes images using ResNet50 + GRU. Trained on Flickr30k dataset.

![Example output](https://i.imgur.com/example.jpg)
*Example: "a dog running in the park"*

## ▶️ How to Run

1. **Open in Kaggle** (easiest):  
   [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/YOUR-USERNAME/image-captioning-pytorch/blob/main/image_captioning.ipynb)

2. **Or run locally**:
```bash
pip install torch torchvision gradio pillow numpy pandas nltk
jupyter notebook image_captioning.ipynb
📝 Instructions Inside Notebook
Run Cell 1 once → wait for features to extract (10-15 mins)
COMMENT OUT Cell 1 after first run (Ctrl + /)
Run Cells 2-5 to train model
Run Cell 8 for live demo
⚠️ Important:
Requires Flickr30k dataset added in Kaggle
First run takes ~1 hour (GPU recommended)
After training, Cell 8 launches Gradio app to upload images
