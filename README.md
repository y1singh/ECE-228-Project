# ECE-228-Project

The boom in the automobile industry has led to an exponential increase in the number
of vehicles and subsequently, a huge increase in the number of accidents as well. 
Each year, 1.35 million people are killed in road accidents across the world. 
Most of them happen due to noncompliance with the traffic sign board directions 
on the road. Also, modern car manufacturing  companies use automatic traffic signs 
detectors based on road images taken by car mounted equipment to assist the driver 
and ensure his safety.  However, the research area of developing robust and fast 
traffic sign detectors which give reliable performance in poor lighting and bad 
weather conditions is still evolving. We plan to implement deep learning based 
algorithms for classification of forty three different types of traffic signs. 
Also, our plan is to evaluate the effect of different CNN architectures on 
classification accuracy. We will use German Traffic Signs Recognition Benchmarks 
Dataset(GTSRB)to develop the most accurate and the fastest sign recognition 
system. First, we will eliminate the class imbalance problem by adding transformed 
data through rotation, normalization and global histogram equalization etc. 
After that, we will develop an end to end convolutional neural network(CNN) 
architecture and experiment with different dimensions of layers. To show 
generality, we will also evaluate our test accuracy on Tsinghua–Tencent 
100K dataset for traffic sign benchmark without tuning.


## Directory Structure
```
├── data
|   └── label_names.csv
├── Data Preprocessing.ipynb
├── Model Training.ipynb
├── Results Visualization.ipynb
```

## Installation

```shell script
git clone https://github.com/y1singh/ECE-228-Project.git
cd ECE-228-Project
```

### Dependencies

- Python>=3.6
- pandas
- Keras
- TensorFlow
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Usage

```shell script
jupyter Data Preprocessing.ipynb
jupyter notebook Model Training.ipynb
```

### Data

The original data can be found at http://benchmark.ini.rub.de/?section=gtsdb&subsection=dataset

### Jupyter Notebook

Visualizations were produced in `Visualization.ipynb`

### Data Analysis

- Data Preprocessing.ipynb: Data loading and processing
- Model Training.ipynb : Main file for implementing and training Model
