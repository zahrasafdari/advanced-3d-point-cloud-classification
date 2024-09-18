# PointCloudX: Precision Classification Redefined

This project enhances 3D point cloud classification by applying advanced data augmentation techniques and refining model architectures.

## Installation

To get started, install the required dependencies:

```bash
pip install trimesh torch torchvision
```

## Dataset

Ensure your ModelNet40 dataset is organized as follows:

```
data/
    ModelNet40/
        train/
            class1/
                file1.off
                ...
        test/
            class1/
                ...
```

## Usage

1. **Data Augmentation**: Includes transformations like random scaling and jittering to improve model robustness.
2. **Training**: Adjust the dataset path in the `PointCloudDataset` class. Run the training script to start training the model.
3. **Testing**: After training, evaluate the model's performance on the test set.

## Features

- **Enhanced Architecture**: Improved PointNet structure with increased final layer channels, batch normalization, and dropout.
- **Robust Data Augmentation**: Advanced augmentation strategies to handle varied point cloud distributions.

