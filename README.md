# Vision-based Defect Recognition Using Fusion Technique
This repo attempts to reproduce the method proposed by Gao et al.[ref] making use if a three-level Gaussian pyramid is introduced to generate multi-level information of the defect, so that more information is available for model training. After the Gaussian pyramid, three VGG16 networks are built to learn the information and the outputs are fused for the final recognition result. The experimental results show that the proposed method can extract more useful information and achieve better performances on small-sample tasks, compared with the conventional DL methods and defect recognition methods.

Through some variation in experiments, I'm able to achieve an accuracy of 99.55% as compared to the previously obtained 99.26 %.
