# Assignment 4 Question 1
## Team Student Ensemble

### Part 1: Dataset Collection

<u>Dataset 1: Apple vs Jackfruit Dataset</u>

- Dataset Credits:
    - Fruits Detection > Fruits-Apple-v1
        - https://universe.roboflow.com/ron-xmba6/fruits-detection-hrhn3
    - Jackfruit > 2023-04-10 11:58am
        - https://universe.roboflow.com/vietnam-fruit-in-lab/jackfruit-maj1o


 Dataset can be accessed here: https://iitgnacin-my.sharepoint.com/:u:/g/personal/22110103_iitgn_ac_in/ETOx7WAgqltAuhVpPSBEMaYB3ckKLDtF4t0s5Bxd3CLX5A?e=teupL5


 <u>Dataset 2: African Elephant vs Kangaroo Dataset</u>

- Dataset Credits:
    - kengeru > 2023-05-11 10:52pm
        - https://universe.roboflow.com/eliraz/kengeru
    - elephant > 2024-04-14 12:36pm
        - https://universe.roboflow.com/wild-animal-detection-hyeyj/elephant-goq1m

Dataset can be accessed here: https://iitgnacin-my.sharepoint.com/:u:/g/personal/22110103_iitgn_ac_in/EXKmnNNBwlxKgDbtV6-mYGEBBTA9NR2R_jN4sNZwFmo0wQ?e=B6QZcI

### Part 2: Training the Models of Different Architectures and Analysing

| Model                | Training Time(s)/epoch | Total Training Time(s) | Training Loss per Epoch                     | Training Accuracy per Epoch | Testing Accuracy | # Model Parameters | Model Size in MB |
| :--------------------| :--------------------: | :--------------------: | :----------------------------------------------------: | :-------------------------: | :--------------: | :----------------: | :--------------: |
| VGG 1                |   1-2                  | 8.03                   | [11.97, 0.26, 5.1e-04, 2.1e-05, 1.3792e-05] | [0.76, 0.96, 1.0, 1.0, 1.0] | 1.0              | 102762497          | 392.01           |
| VGG 3                |   2                    | 14.66                  | [1.07, 0.025, 0.008, 0.037, 0.063]           | [0.82, 0.993, 0.003, 0.987, 0.993] | 1.0              | 26061185          | 99.42      |
| VGG 3 AUG            |   3-4                  | 18                     | [1.07, 0.025, 0.008, 0.037, 0.063]           | [0.82, 0.993, 0.003, 0.987, 0.993] | 0.9750              | 26061185          | 99.42   |
| VGG 16                |   4/13                    | 40                 | [1.11, 0.7, 0.7, 0.7, 0.7]           | [0.5, 0.5, 0.5, 0.5, 0.5] | 0.5              | 134264641          | 512.18      |
| VGG 16 PRE            |   3                    | 13                    | [7.00, 0.20, 0.04, 0.002, 2.78e-07]           | [0.75, 0.956, 0.975, 1.0, 1.0] | 1.0              | 119549953          | 456.05      |

For Corresponding Code, See IPYNB file

### Part 3: TensorBoard

Insert Images or see locally or on github

### Part 4: Test Set Predictions

In the IPYNB File

### Part 5: Questions

Add

### Part 6: MLP

Compare