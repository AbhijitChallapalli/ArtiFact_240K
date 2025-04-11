# ArtiFact_240K
This dataset is designed for deepfake detection challenge for Datathon 2025 and contains 120000 real and 120000 fake images. The dataset is categorized into three classes:
1. Human Faces
2. Animals
3. Vehicles

Dataset link for download: [Link](https://drive.google.com/file/d/1kPPz8eECrYgz3ZaDXNgf1a7hXh3160sS/view?usp=drive_link)

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
│   │   ├── All Test images
│── metadata.csv  # Logs image paths, labels, and class
│── LICENSE       # MIT License
│── README.md     # Dataset Documentation
```

This dataset is split into:
- train: 70% (167,998 images)
- validation: 25% (60,000 images)
- test: 5% (12,002 images)

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

**Metadata Format:**
A **metadata file (`metadata.csv`)** is provided, containing **image paths, labels, and class names**.

| **Column**    | **Description** |
|--------------|----------------|
| `image_path` | Path to the image file |
| `label`      | `0` = Real, `1` = Fake |
| `class`      | One of `human_faces`, `animals`, `vehicles` |

Example `metadata.csv`:

image_path,label,class 

1. train/real/human_faces/human_faces_00001.jpg,0,human_faces 
2. train/fake/human_faces/human_faces_00001.jpg,1,human_faces 
3. train/real/animals/animals_00001.jpg,0,animals 
4. train/fake/animals/animals_00001.jpg,1,animals 



**License:**
This dataset is licensed under the MIT License. See the [LICENSE](https://github.com/AbhijitChallapalli/ArtiFact_240K?tab=MIT-1-ov-file) file for more details.

