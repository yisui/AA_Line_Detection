# Road Line Detection and Labeling 

* This repository contains all the ipython notebooks I have created for 
the [Math^Industry workshop 2020](https://mathtopowerindustry.ca/).  
* The project goal is to develop an automated recognition
and labelling tool for road lines in aerial images. Detailed project description can be 
found [here](https://mathtopowerindustry.ca/project/aerium-analytics/).
* This project is a group work done by Carlos Contreras, Keran Li, Li Wang, Tingzhou Yu,
Junjie Zhu and myself. 
* This project is proposed by [AERIUM Analytics](https://www.aeriumanalytics.com/). 
Mentors for the project are Heather Vooys and Matthew Greenberg. 


Note: 
* I am running the notebooks with Python 3.7.7, Numpy 1.18.5, and OpenCV 3.4.2. 
If you are using a different version of any of these, slight modification of the code might needed. 
* I used ipython notebooks for an easy demonstration purpose. 
The notebook file can be easily converted to .py file, if needed. 
* Starting with Day4.ipynb, when color quantization is applied, it is always done on all images.
* Our team did some preliminary trials on dealing with the issues of shadow and white line detection. 
However, we don't have solutions how to completely overcome these two issues.
* A final report for this project will be available soon.
* If any questions occurs, I can be reached by [email](mailto:ysui@sfu.ca).

## List of files with description 
* Image data exploring, learn OpenCV and edge detection/ line detection:    
  [Day1.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day1.ipynb)

* Preliminary yellow line detection result with color quantization on one image:    
  [Day2.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day2.ipynb)

* Preliminary yellow line detection result with a fixed range yellow color filter:    
  [Day3.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day3.ipynb)

* Preliminary yellow line detection result with color quantization on all images:    
  [Day4.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day4.ipynb)
  
* Explore parameters in Canny edge detection and Hough line detection:    
  [Day4.2.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day4.2.ipynb)

* Shadow yellow line detection result when two reference yellow colors in RGB considered:    
  [Day5.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day5.ipynb)

* Shadow yellow line detection result when two reference yellow colors in HSV considered:    
  [Day5.1.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day5.1.ipynb)
  
* A trial for converting the shadow removal code from mathematica to python (incomplete):    
  [Day6-7.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day6-7.ipynb)

* Updated from Day4.2 notebook to put box around different yellow objects:    
  [Day7.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day7.ipynb)

* Updated from Day7 notebook to only put box around yellow lines:    
  [Day7.1.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day7.1.ipynb)  
  
* Preliminary white dashed line detection result with color quantization:    
  [Day8.1.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day8.1.ipynb) 
  
* White dashed line detection result when mean shift filter is applied:    
  [Day7.2.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day7.2.ipynb)   

* Updated from Day7.1 notebook when Gaussian mixture model is applied for color quantization:    
  [Day8.ipynb](https://github.com/yisui/AA_Line_Detection_Labeling/blob/master/Day8.ipynb)    

## References 
There is a list of tutorials/lecture slides/book I have read over/watched in order to 
learn how to use OpenCV, learn unsupervised machine learning and get ideas how to proceed our project:
* [Very detailed OpenCV tutorial](https://docs.opencv.org/3.4.2/d6/d00/tutorial_py_root.html)
* [Very detailed OpenCV Python tutorial](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html)
* [A well-made website with OpenCV tutorial](https://pysource.com/2018/01/20/loading-images-opencv-3-4-with-python-3-tutorial-1/)
* [Stanford lecture on edge detection and Hough transform](http://vision.stanford.edu/teaching/cs231a_autumn1112/lecture/lecture4_edges_lines_cs231a_marked.pdf)
* [The University of Western Ontario lecture on image segmentation](https://www.csd.uwo.ca/Courses/CS4487a/Lectures/lec04_basic_segm.pdf)
* [Computer Vision: Algorithms and Applications, by Richard Szeliski](http://szeliski.org/Book/)
* [CPSC 340 course from UBC by Mike Gelbart](https://www.youtube.com/playlist?list=PLWmXHcz_53Q02ZLeAxigki1JZFfCO6M-b)

