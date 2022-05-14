# UNet-for-Radar-Imagery

## About this project
This is Tensorflow based project using U-Net Architecture to map flooding using Sentinel-1 imagery.

## Dataset
You can download our dataset at this link https://www.kaggle.com/dimskeee/unet-segmentation-using-radar-imagery, which includes thousands of tiles that are used to train, test, and validation. The size of tiles is 128 x 128, and the default filter in the script is 16, 32, 48, 64. <br>
Folder Structure: <br>
<img src="https://user-images.githubusercontent.com/35564104/133217714-2584b01e-400d-4d4e-90be-a30116f84e1f.PNG" width="250"> <br>
Images structure: <br>
<img src="https://user-images.githubusercontent.com/35564104/133221680-a2bb4cad-503b-413d-be0c-db530d8a6a53.png" width="250">

## Network architecture
<img src="https://user-images.githubusercontent.com/35564104/133219716-6242ce0c-ffa4-4977-bac0-54e686148fd9.png" width="500"> <br>
**Note:** Training for this model was done on an RTX 2060 Super 6GB

## Results
#### Manual Digitation <br>
<img src="https://user-images.githubusercontent.com/35564104/138245023-9b077f23-a9e1-4396-b701-450d43b0c09c.png" width="1000"> <br>
#### U-Net Prediction <br>
<img src="https://user-images.githubusercontent.com/35564104/138245042-029a7757-1fcc-4c2a-90dc-088e8dfc7407.png" width="1000">
