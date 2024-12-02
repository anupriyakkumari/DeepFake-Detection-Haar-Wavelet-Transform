# DeepFake Detection using Haar Wavelet Transform

##### Digital Image Processing (ECN-316) Course Project: Deepfake Detection Using Haar Wavelet Transform, a Reproducibility Study.


### Contributors:
<pre>
Anupriya Kumari                               Atharva Nandkumar Sonare
22116015                                      22116022
anupriya_k@ece.iitr.ac.in                     atharva_ns@ece.iitr.ac.in
                                              atharvasonare700@gmail.com


Soham Parolia                                 Swadesh Swain
22116088                                      22116089
soham_p@ece.iitr.ac.in                        swadesh_s@ece.iitr.ac.in
</pre>

### Project Overview:

This work presents a reproducibility study of the original [Haar Wavelet Transform-based deepfake detection method](https://ieeexplore.ieee.org/document/9142077/). Through this implementation, we identified shortcomings in the original methodology and proposed corrections. Our enhancements include proper edge structure classification, structural analysis validated through Laplacian sharpness measurements and precise kernel specifications. Although different accuracy metrics are achieved compared to the original paper, our implementation represents a more reliable and interpretable approach to wavelet-based deepfake detection.

### Usage:

This repository contains our implementation of the original method in the form of an IPython Notebook file, with added visualizations such as Haar Wavelet decompositions at 3 levels, their corresponding edge maps and max-pooled edge maps, edge structure detection demonstration, and demonstration of varying ROI size.


[Our report](https://drive.google.com/) covers the detailed background of the work. 

A ready-to-run version of our final code can be found at our [Kaggle Notebook here](https://www.kaggle.com/code/anupriyakkumari/haar-wavelet-deepfake).
This notebook has been divided into multiple sections corresponding to the functions under them. It is easy to follow and run the notebook. The datasets are public. 
