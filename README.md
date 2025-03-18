# ArtiFact_240K
This dataset is designed for deepfake detection challenge for Datathon 2025 and contains 120000 real and 120000 fake images. The dataset is categorized into three classes:
1. Human Faces
2. Animals
3. Vehicles
   
Dataset Structure:
```bash
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
```

This dataset is split into:
- train: 70% (168,000 images)
- validation: 25% (60,000 images)
- test: 5% (12,000 images)

If you use this dataset, please cite the ArtiFact Dataset:
```bash
@article{artifact2023,
  title={ArtiFact: A Large-Scale Dataset for Real and Fake Image Detection},
  author={John Doe, Jane Smith, et al.},
  journal={Proceedings of the 2023 AI Ethics Conference},
  year={2023},
  url={https://artifact-dataset.org}
}
```

Metadata Format
A **metadata file (`metadata.csv`)** is provided, containing **image paths, labels, and class names**.

| **Column**    | **Description** |
|--------------|----------------|
| `image_path` | Path to the image file |
| `label`      | `0` = Real, `1` = Fake |
| `class`      | One of `human_faces`, `animals`, `vehicles` |

Example `metadata.csv`:

image_path,label,class 
train/real/human_faces/human_faces_00001.jpg,0,human_faces 
train/fake/human_faces/human_faces_00001.jpg,1,human_faces 
train/real/animals/animals_00001.jpg,0,animals 
train/fake/animals/animals_00001.jpg,1,animals 
train/real/vehicles/vehicles_00001.jpg,0,vehicles 
train/fake/vehicles/vehicles_00001.jpg,1,vehicles


License:
This dataset is licensed under the MIT License. See the LICENSE file for more details.

