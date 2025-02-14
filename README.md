# Flooded Areas Segmentation

## Overview

The "Flooded Areas Segmentation" project aims to develop a robust model for identifying and segmenting flooded areas in satellite and aerial imagery. This tool is essential for disaster response, urban planning, and environmental monitoring, providing valuable insights into the extent of flooding and its impact on affected regions.

## Table of Contents

- [Features](#features)
- [Data](#data)
- [Model Architecture](#model-architecture)
- [Evaluation](#evaluation)

## Features

- Automated segmentation of flooded areas from images
- High accuracy using state-of-the-art deep learning models
- User-friendly interface for easy interaction
- Visualization of results for better understanding

## Data

Here are some sample of data and their masks

![image](https://github.com/user-attachments/assets/a26be104-a172-4361-80a1-dbf6b8fedc7c)

![image](https://github.com/user-attachments/assets/50911fc7-fe4d-42ed-ad9c-288ab5cc69e0)


## Model Architecture

The architecture used is U-Net

![image](https://github.com/user-attachments/assets/98441183-1927-4c98-81cb-2031dc7afcd8)

## Evaluation 

After 50 epochs, the model reach the validation accuracy of **86.15%** pixel-wise with a validation loss of **0.3430**. 

![image](https://github.com/user-attachments/assets/61a82083-3fba-4e21-a1a0-31b6679f15d0)

Despite the fact that the model validation accuracy if not too high, it work quite well on unseen image, here is the testing result of an image which I picked randomly online.

![image](https://github.com/user-attachments/assets/4b0b4228-7543-4e38-b99a-0e8f7daace07)

