# Image-Forgery-Detection-using-CNN
Implementation of error-level analysis (ELA) and deep learning to detect whether an image has undergone fabrication or/and editing process or not.
Dataset used is CASIA 2.0.
Downloaded dataset from:  https://bit.ly/2QazgkG
2 folders inside dataset: Au and Tp

Authentic images:(Au):
Eg of filename:Au_ani_00001.jpg 
Au: Authentic 
ani: animal category 
Other categories: arc (architecture), art, cha (characters), ind (indoor), nat (nature), pla (plants), txt (texture)

Tampering images(Tp):
a. Spliced image

    Tp_D_CRN_S_N_cha00063_art00014_11818.jpg
Tp: Tampering
D: Different (means the tampered region was copied from the different image)
Next 5 letters stand for the techniques they used to create the images. Unfortunately, I don't remember exactly.
cha00063: the source image
art00014: the target image
11818: tampered image ID
b. Copy-move images

    Tp_S_NRN_M_N_pla00020_pla00020_10988.jpg
Tp: Tampering
S: Same (means the tampered region was copied from the same image)
And the rest is similar to case a.
