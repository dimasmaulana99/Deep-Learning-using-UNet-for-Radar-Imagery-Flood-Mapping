# UNet-for-Radar-Imagery

## About this project
This is Tensorflow based project using U-Net Architecture to map flooding using Sentinel-1 imagery

## Dataset
You can download our dataset at this link https://www.kaggle.com/dimskeee/unet-segmentation-using-radar-imagery, which includes thousands of tiles that are used to train, test, and validation. The size of tiles is 128 x 128, and the default filter in the script is 16, 32, 48, 64.

## Implementation
Visual interpretation map (manually)
![Digitasi](https://user-images.githubusercontent.com/35564104/133213232-ba812ed4-73d0-4325-ad90-d653230264bb.jpeg = 500x500)

**Note:** Training for this model was done on a RTX 2060 Super 6GB

## Prediction
Predicted map (automatically)
![Predict](https://user-images.githubusercontent.com/35564104/133213257-78cdcee6-78b9-44b5-8ce4-c971bb72f1ce.jpeg = 500x500)


## Network architecture
![WhatsApp Image 2021-09-02 at 19 46 35](https://user-images.githubusercontent.com/35564104/133194630-aaf30552-029d-450d-a726-336ef52b850b.jpeg = 500x500)

