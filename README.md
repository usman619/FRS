# Fertilizer Recommendation System
## Abstract
This project aims to create a system utilizing Internet of Things (IoT) devices that will assist farmers in monitoring soil data to optimize their crop yields. By utilizing IoT devices, farmers can obtain real-time data on soil moisture, pH levels, and nutrient content. This data will be processed through the system to recommend crops and fertilizers that are best suited for the specific soil conditions. This will allow farmers to make informed decisions about their crops and increase their productivity while reducing waste. Overall, this system has the potential to revolutionize the agricultural industry by improving crop yields and reducing the environmental impact of farming practices.

## Getting Started
### Prerequisites
- Python
- Javascript
- HTML/CSS
- Bootstrap
- Flask
- Numpy
- Pandas
- pyTorch
- Sklearn

### Running the code
1. Installing Anaconda (on Linux): Check https://docs.anaconda.com/free/anaconda/install/linux/ for installation of Anaconda.
```
sudo apt - get install libgl1 -mesa-glx libegl1 -mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6

curl -O https :// repo . anaconda . com / archive / Anaconda3 -2023.09 -0 - Linux - x86_64 . sh

bash ~/ Downloads / Anaconda3 -2020.05 - Linux - x86_64 .sh

source < PATH_TO_CONDA >/ bin / activate

```
2. Running the code:
```
conda init

conda create -n frs python =3.10.1

conda activate frs

// Install all the required Libraries
// You will need flask , request , sklearn , torch , torchvision , pandas , numpy , xgboost etc .

python app . py

// Click on the Flask link to run the website
```
3. To stop the website and conda deactivate environment
```
Press Ctrl + C in terminal [ To stop the flask server from running ]

conda deactivate
```
