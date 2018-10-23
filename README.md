# Selective-Summary

**Download the code:**

In order to use this code, please open the 'code.zip' first (click on the 'code.zip', here) and then attempt to download it. Alternatively, you can clone the repository (run this line in your terminal):

```
$ git clone https://github.com/pariay/Selective-Summary.git
```

**Run the demo:**

After it is downloaded, unzip the file and run the demo as it is. The demo uses sampled frames from the UTEgo dataset (the whole 
dataset is available at: http://vision.cs.utexas.edu/projects/egocentric_data/UT_Egocentric_Dataset.html).

**Use it for your dataset:**

If you would like to use the code for your preferred dataset, please install MatConvNet toolbox from the link given below. Then download ResNet and VGGNet-16 pre-trained models (mat files) and store them inside a folder called 'data' in the MatConvNet directory.
Make changes on 'Vid_Selective_Summary.m' (follow the comments), and set the path to your data and the MatConvNet directory.

**Requirements:**

- MatConvNet toolbox (link: http://www.vlfeat.org/matconvnet/).

- WordNet lexical database which is part of the NLTK corpus (link: https://www.nltk.org/install.html). 

- Install Python in your system, and install python engine in Matlab. To do so, (a) you need to find your matlabroot (type 'matlabroot' in Matlab command window). (b) Then open command prompt (run as administrator) and type: >> cd "matlabroot\extern\engines\python". (c) Now type: >> python setup.py install .

 
**Please cite this paper if you use this code in your publication:** 
    
     
     Yousefi, Paria and Kuncheva, Ludmila I. 
     "Selective Keyframe Summarisation for Egocentric Videos Based on Semantic Concept Search, "  
     Third IEEE International Conference on Image Processing, Applications and Systems (IPAS 2018)
     
     
 
