# PCVD - A Dataset of Point Cloud Video for Dynamic Human Interaction

This repository introduces PCVD (Point Cloud Video Dataset), which consists of synchronized point cloud video data captured using **six Azure Kinect cameras**. The dataset is designed for tasks such as denoising, segmentation, and motion recognition, providing high-quality data of dynamic human actions.

The dataset includes synchronized depth maps, RGB images, and 3D point clouds, captured from various human activities. It aims to serve as a valuable resource for 3D point cloud processing, especially in the context of dynamic human interaction.

## Features

- Captured with six synchronized Azure Kinect cameras in a 4m × 4m space.
- Relatively high-quality data of dynamic human actions, including a variety of movements from six volunteers.
- Includes synchronized depth maps, RGB images, and 3D point clouds in .obj and .ply formats.
- Optimized for tasks such as denoising, segmentation, and motion recognition.
- Demonstrates superior performance in terms of uniformity, completeness, robustness, and balanced frame distribution compared to other existing datasets.


## Dataset Structure

The dataset is organized into the following directories:

- mesh/: Contains 3D mesh files (e.g., `.obj`, `.mtl`) for each frame.
- point_cloud/: Contains point cloud files (e.g., `.ply`, `.png`) for each frame.

## Dataset Evaluation

This dataset was carefully designed with the following key metrics in mind:

- Spatial-Color Consistency: The dataset ensures a high degree of spatial-color consistency across frames, reducing color inconsistencies.
- Missing Ratio: We ensure that the dataset minimizes missing data, resulting in fewer gaps in point cloud and depth map information.
- Shadow Ratio: The dataset is designed to minimize the presence of shadows, which can negatively impact point cloud quality.
- Average Frame Count: The dataset emphasizes balanced frame distribution across sequences, avoiding excessive variation in the number of frames.


## Contributions

We welcome contributions to this project. If you have suggestions, improvements, or issues, please feel free to fork the repository, create a pull request, or open an issue.
