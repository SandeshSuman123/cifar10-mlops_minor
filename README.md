CIFAR10 MLOps Pipeline

Steps implemented:
1. Loaded dataset from HuggingFace
2. Created custom dataloader with augmentations
3. Trained pretrained ResNet18
4. Logged metrics using wandb
5. Uploaded best model to HuggingFace
6. Reloaded model and evaluated
7. Generated confusion matrix and class-wise accuracy
