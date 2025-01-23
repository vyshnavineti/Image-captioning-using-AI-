# Image-captioining-

Abstract::

The creation of descriptive captions for images is now becoming a mission-critical application area in the intersection of natural language processing and computer vision. This work provides the hybrid model VisionGPT2, combining ViT for encoding images and GPT2 for text generation, which enables accurate, coherent, and context-aware descriptions for images. The model is tested over a dataset by using BLEU score metrics and has achieved a high BLEU score of 0.4877, which ascertains the strength of cross-modal architectures for image captioning. In this paper, the design and training process of VisionGPT2 has been discussed along with the benefits and challenges faced while proceeding and the potential applications that the model has gained in performance for future use.

bleu score::

0.4877492180835421

•	Learning Rate: 1e-4 (with OneCycleLR scheduler)
•	Batch Size: 32
•	Epochs: 5
•	Freeze Epochs for GPT-2: 1
•	Freeze All Layers: 2
•	Optimizer: Adam optimizer
•	Dropout Rates: Attention dropout 0.1, MLP dropout 0.1, Residual dropout 0.1


![image](https://github.com/user-attachments/assets/7d7d44c6-5655-4b3e-bf34-d9943cbcbc73)
![image](https://github.com/user-attachments/assets/35b55437-f6db-43b2-9f32-ada303d9eaf0)

dataset from kaggle : https://www.kaggle.com/datasets/nikhil7280/coco-image-caption
