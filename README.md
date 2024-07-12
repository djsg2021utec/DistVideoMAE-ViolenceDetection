# DistVideoMAE-ViolenceDetection :movie_camera::boom::walking:

DistVideoMAE-ViolenceDetection is an AI model designed for the detection of violence in surveillance videos. This project uses knowledge distillation techniques applied to VideoMAE (Video Masked Autoencoders) based models to create an efficient and accurate violence detection system.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Citation](#citation)
- [Acknowledgements](#acknowledgements)

## Features
- Efficient violence detection in surveillance videos
- Knowledge distillation from VideoMAE-based models
- Real-time processing capabilities
- High accuracy with reduced computational requirements

## Installation
```bash
git clone https://github.com/yourusername/DistVideoMAE-ViolenceDetection.git
cd DistVideoMAE-ViolenceDetection
pip install -r requirements.txt
```
## Usage

```python
from dist_video_mae import DistVideoMAE

model = DistVideoMAE.from_pretrained('path/to/pretrained/model')
result = model.predict('path/to/video.mp4')
print(result)
```

## Dataset

This model was trained on a subset of the RWF-2000 dataset, which consists of 2000 video clips of violent and non-violent scenes captured by surveillance cameras, this. The guide for generate [Add more details about your specific subset if applicable]

El modelo es probado inicialmente con un subcojunto del dataset RWF-2000 descrito en el artículo [RWF-2000: An Open Large Scale Video Database
for Violence Detection](https://arxiv.org/pdf/1911.05913v3), debido a que el repositorio no contiene la data original se usa 



