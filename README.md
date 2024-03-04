# flora-wise
A composite hybrid neural network model that
- effectively identifies the plant type using lightweight CNN &
- recognizes the disease from the predefined categories in balanced & imbalanced data

for empowering farmers to protect plant health & enhance crop yields


## System Design
![FloraWise system design](https://github.com/ishg-153/flora-wise/assets/68017646/1da0d297-98c9-4cd2-b514-1d36e6d89a92)


## Result Analysis

 Evaluation Parameters Comparison between VGG16 and DNet Models

|  Plants     |    VGG16    |          |            |     DNet    |          |            |
|-------------|:-----------:|:--------:|:----------:|:-----------:|:--------:|:----------:|
|             | Precision % | Recall % | F1 Score % | Precision % | Recall % | F1 Score % |
| Strawberry  |       99.11 |    99.11 |      99.11 |       95.55 |    95.56 |      95.56 |
| Bell Pepper |       93.09 |    92.99 |      93.02 |       94.08 |    93.66 |      93.72 |
| Cherry      |         100 |      100 |        100 |       97.40 |    97.03 |      97.14 |
| Peach       |       99.01 |    98.97 |      98.99 |       99.09 |    99.11 |      99.10 |
| Grape       |       92.62 |    92.56 |      92.55 |       98.27 |    98.12 |      98.05 |
| Corn        |       95.69 |    95.45 |      95.53 |       97.83 |    97.78 |      97.80 |
| Tomato      |       84.45 |    84.52 |      84.31 |       94.49 |    94.13 |      94.16 |
| Potato      |       95.14 |    95.20 |      95.15 |       98.56 |    98.55 |      98.54 |
| Apple       |       95.84 |    95.83 |      95.81 |       97.81 |    97.61 |      97.64 |


Comparison between VGG16 and DNet models 

|  Plants     |      VGG16      |            |       DNet      |            | Parameter Reduction % |
|-------------|:---------------:|:----------:|:---------------:|:----------:|-----------------------|
|             | Test Accuracy % | Parameters | Test Accuracy % | Parameters |                       |
| Strawberry  |           99.11 |   14718810 |           95.56 |       5650 |                 99.96 |
| Bell Pepper |           93.03 |   14718810 |           93.74 |       5650 |                 99.96 |
| Cherry      |          100.00 |   14718810 |           97.15 |       5650 |                 99.96 |
| Peach       |           98.99 |   14718810 |           99.10 |       5650 |                 99.96 |
| Grape       |           92.19 |   14719862 |           98.12 |      25140 |                 99.82 |
| Corn        |           95.68 |   14719862 |           97.87 |      25140 |                 99.82 |
| Tomato      |           84.43 |   14731434 |           94.18 |      26442 |                 99.82 |
| Potato      |           95.16 |   14719851 |           98.53 |      25123 |                 99.82 |
| Apple       |           95.83 |   14719862 |           97.58 |      25140 |                 99.82 |

