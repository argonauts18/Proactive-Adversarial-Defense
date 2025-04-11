# Paper Title: 
Proactive Adversarial Defense: Harnessing Prompt Tuning in Vision-Language Models to Detect Unseen Backdoored Images

# Abstract:
Backdoor attacks pose a critical threat by embedding hidden triggers into inputs, causing models to misclassify them into target labels. While extensive research has focused on mitigating these attacks in object recognition models through weight fine-tuning, much less attention has been given to detecting backdoored samples directly. Given the vast datasets used in training, manual inspection for backdoor triggers is impractical, and even state-of-the-art defense mechanisms fail to fully neutralize their impact. To address this gap, we introduce a groundbreaking method to detect unseen backdoored images during both training and inference. Leveraging the transformative success of prompt tuning in Vision Language Models (VLMs), our approach trains learnable text prompts to differentiate clean images from those with hidden backdoor triggers. Experiments demonstrate the exceptional efficacy of this method, achieving an impressive average accuracy of 86\%  across two renowned datasets for detecting unseen backdoor triggers, establishing a new standard in backdoor defense.

![My Image](Main_Fig_Proactive.png)

# Datasets
The method was ran on GTSRB and CIFAR-10. Each dataset folder has subfolders with the corresponding attacks.

#### GSTRB: https://drive.google.com/uc?export=download&id=1QXGiIVGctdjoyGPE_CWNIIjLrUT77DSd
#### CIFAR-10: 

# Script
The main script (Prefix_Tuning.ipynb) was ran on Google Colab L4 GPU. To recreate the expriment, follow the script and adjust paths accordingly. 

