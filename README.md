# kaggle-DigitRecognizer
Digit recognizer using Convolution Neural Network (CNN)

## Notes
This project has very big dataset. 42000 rows with 28x28 pixel data. It is very important to cast the datatype from float64 to float32
This can greatly reduce the memory usage.

The image doesnt have noises so filtering is not needed.

## Architecture
- One convolutional layer (6x6 convolution)
- Max pooling to reduce the size by a factor of 2 in each axis
- Two hidden layers with 40 and 20 nodes with relu activation function
- 10 nodes output layer with softmax activation function since we have 10 different digits

## Image
![alt text](https://user-images.githubusercontent.com/55706850/177576319-8f035069-b985-4690-b3a1-5d7f75be0826.PNG)
![alt text](https://user-images.githubusercontent.com/55706850/177577746-b01a56cd-c165-4d0a-90de-5aafe7b0503c.PNG)
