# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2023

+ **Team 4**
+ **Team members**
	+ Jiajun DU  jd3881@columbia.edu
	+ Linda LIN  yl5144@columbia.edu
	+ Xiaoxue REN  xr2159@columbia.edu
	+ Jiahao WEI  jw4312@columbia.edu
	+ Aubrey YAN  xy2543@columbia.edu
	+ Hongyan ZHOU  hz2827@columbia.edu

+ **Project summary**: In this project, we developed two image classification models using Tensorflow's CNN. The first model was trained on noisy labels, which included convolution layers, batch normalization, and pooling techniques. However, the accuracy of this model was around 0.52, which was not satisfactory. To improve the accuracy, we modified some of the parameters of the first model and trained a new model on the first 10000 images with clean labels. We used this model for data cleaning to clean the noisy labels corresponding to the left 40000 images, and obtained new labels. We then combined the first 10000 labels with 40000 new labels to train the second model. As a result, the second model achieved a significantly improved accuracy of 0.8.
	

+ **Contribution statement**: Please find a_note_in_contributions.md in doc. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
