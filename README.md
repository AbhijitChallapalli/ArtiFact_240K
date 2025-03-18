# ArtiFact_240K
This dataset is designed for deepfake detection challenge for Datathon 2025 and contains 120000 real and 120000 fake images. The dataset is categorized into three classes:
1. Human Faces
2. Animals
3. Vehicles

Dataset Structure:
ArtiFact_240K/
│── train/
│   ├── real/
│   │   ├── human_faces/
│   │   ├── animals/
│   │   ├── vehicles/
│   ├── fake/
│   │   ├── human_faces/
│   │   ├── animals/
│   │   ├── vehicles/
│── validation/
│   ├── real/
│   │   ├── human_faces/
│   │   ├── animals/
│   │   ├── vehicles/
│   ├── fake/
│   │   ├── human_faces/
│   │   ├── animals/
│   │   ├── vehicles/
│── test/
│   ├── real/
│   │   ├── human_faces/
│   │   ├── animals/
│   │   ├── vehicles/
│   ├── fake/
│   │   ├── human_faces/
│   │   ├── animals/
│   │   ├── vehicles/
│── metadata.csv  # Logs image paths, labels, and class
│── LICENSE       # MIT License
│── README.md     # Dataset Documentation


This dataset is split into:
- train: 70% (168,000 images)
- validation: 25% (60,000 images)
- test: 5% (12,000 images)

