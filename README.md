# speech-to-asl

Speech to American Sign Language Generation


1. Execution Environment: The project is executed on Google Colab utilizing an Nvidia Tesla L4 GPU.

2. Dataset: The dataset used includes labels with video IDs, sourced from How2Sign.

3. Storage of Output Images: Output images generated from videos are stored in Google Drive, considering the huge size of the dataset.

4. Fine-tuning the Model: After initial training, the model is fine-tuned using DreamBooth. Post fine-tuning, the output images are stored in Google Drive.

5. One-time Execution: The video to images generation block should only be run once. It takes approximately 30 minutes to convert videos into images and should not be executed multiple times to avoid redundancy.

6. Duration of Fine-tuning: Fine-tuning the model with DreamBooth takes about 3 hours.
