# Vision-based Defect Recognition Using Fusion Technique
This repo attempts to reproduce the method proposed by Gao et al.[1] for automatic extraction of the defect information making use of a three-level Gaussian pyramid to generate multi-level information of the defect, so that more information is available for model training. Vision-based defect recognition is an important technology to guarantee quality in modern manufacturing systems. In this technique, after the Gaussian pyramid, three VGG16 networks are built to learn the information and the outputs are fused for the final recognition result. The experimental results show that the proposed method can extract more useful information and achieve better performances on small-sample tasks, compared with the conventional DL methods and defect recognition methods.

The code attached along achieves an accuracy of 99.55% on the NEU (NorthEastern University Dataset) as compared to the previously obtained 99.26 %.
# Getting Started
1. Open the .ipynb using Google Colaboratory. (you will need a gmail account for this purpose).
2. Sign in using your Gmail Credentials
*An alternative would be to download the .ipynb file and use in Jupyter Notebooks. Either method works fine.*
3. You will need access to the NEU Dataset (see the next section)


# References
Y. Gao, L. Gao, X. Li and X. V. Wang, "A Multilevel Information Fusion-Based Deep Learning Method for Vision-Based Defect Recognition," in IEEE Transactions on Instrumentation and Measurement, vol. 69, no. 7, pp. 3980-3991, July 2020, doi: 10.1109/TIM.2019.2947800.
