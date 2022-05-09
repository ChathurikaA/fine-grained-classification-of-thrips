# Fine Grained Classification of Thrip Species
![057](https://user-images.githubusercontent.com/24618493/167328184-cdd07de5-fb2b-467e-9850-e6e00475e6e8.png | width=50)

Thrips are one of the major worldwide crop pest that can be found in wide range of crops. Thrips are small in size (~1mm) and differences in appearance between some key species can be difficult to discern. However, their accurate identification to species level is essential to agriculture. Hence, this repository contains a software that cable of classifying two major thrip pest species - Western Flower Thrips (WFTs) and Plague Thrip. The software built upone two main modules - a Data Processing module and a Domain Knowledge-Driven Stacked Model. The Data Preprocessing Module segments relevant insect features and splits the insect into body segments to inform identification. The Domain Knowledge-Driven Stacked Model generates the prediction from each body segment and fuses predictions for each segment into an accurate species-level classification. 

In addition, we provide with you a dataset that consists of microscopic images of the two thrip species to train and test the models in https://drive.google.com/drive/folders/1vfWZVaIwxsLgQG6CzE_8zLDMJfCBtA6S?usp=sharing. 

The pretrained model can be found in https://drive.google.com/drive/folders/1hQR7v0s5gdwIuLM84T-cYpaBePUQqVVx?usp=sharing

