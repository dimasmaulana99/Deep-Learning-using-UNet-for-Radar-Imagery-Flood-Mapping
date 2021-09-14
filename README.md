# UNet-for-Radar-Imagery

## About this project
This is Tensorflow based project using U-Net Architecture to map flooding using Sentinel-1 imagery

## Dataset
You can download our dataset at this link https://www.kaggle.com/dimskeee/unet-segmentation-using-radar-imagery, which includes thousands of tiles that are used to train, test, and validation. The size of tiles is 128 x 128, and the default filter in the script is 16, 32, 48, 64. <br>
Folder Structure: <br>
<img src="https://user-images.githubusercontent.com/35564104/133217714-2584b01e-400d-4d4e-90be-a30116f84e1f.PNG" width="250"> <br>
Images structure: <br>
<img src="https://user-images.githubusercontent.com/35564104/133221680-a2bb4cad-503b-413d-be0c-db530d8a6a53.png" width="250">
## Implementation
Visual interpretation map (manually) <br>
<img src="https://user-images.githubusercontent.com/35564104/133213232-ba812ed4-73d0-4325-ad90-d653230264bb.jpeg" width="500">

**Note:** Training for this model was done on a RTX 2060 Super 6GB

## Prediction
Predicted map (automatically) <br>
<img src="https://user-images.githubusercontent.com/35564104/133213257-78cdcee6-78b9-44b5-8ce4-c971bb72f1ce.jpeg" width="500">

## Network architecture
<img src="https://user-images.githubusercontent.com/35564104/133219716-6242ce0c-ffa4-4977-bac0-54e686148fd9.png" width="500">
