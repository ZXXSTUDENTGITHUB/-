# Code Running Instructions:
- Environment Preparation: Install dependencies (torch, torchvision, numpy, tqdm, argparse, and OpenCV).
- Data Preparation (using CIFAR100 as an example): Convert CIFAR100 binary data to image format (using file_to_image.py).
- Pre-training (trainstage1.py): Train the model using unsupervised contrastive learning and generate pre-trained weights.
- Fine-tuning (trainstage2.py): Load pre-trained weights and fine-tune on the CIFAR100 classification task.
- Evaluation: Evaluate the fine-tuned model using eval.py.
