<h1 align="center">Implementation of Rtree in Cpp</h1>
ADS Programming Assignment .

 ####  R-tree is a tree data structure used for storing spatial data indexes in an efficient manner. R-trees are highly useful for spatial data queries and storage. Some of the real life applications are mentioned below:
  - Indexing multi-dimensional information.
  - Handling geospatial coordinates.
  - Implementation of virtual maps.

 ####  Properties of R-tree:
  - Consists of a single root, internals nodes and leaf nodes.
  - Root contains the pointer to the largest region in the spatial domain.
  - Parent nodes contains pointers to their child nodes where region of child nodes completely overlaps the regions of parent nodes.
  - Leaf nodes contains data about the MBR to the current objects.
  - MBR-Minimum bounding region refers to the minimal bounding box parameter surrounding the region/object under consideration.

  - No of comparisions required : (N + log <sub> 2 </sub> N – 2)
  - Time Complexity : (N + log <sub> 2 </sub> N)
  - Code implemented in C++.
 
 #### Representaion of objects in tree
  <p align="center">
  <img height=400px  src="./sampletree.png" >
  </p>
   
   
 <p align="center">
  <img height=400px  src="./sampletree.png" >
  </p>
  
  #### Output = Best Player: 7, Second Best Player: 11 :heavy_check_mark:
  
  
   ## How to Use
 -  main.cpp file contain code for this.
 -  Run that file on any c++ compiler.
 -  or Demo at [http://codepad.org/yO18w5qc](http://codepad.org/yO18w5qc)
 
## Author

[Nikhil Sahu](https://nikhilsahu.me/) - [@nikhildsahu](https://github.com/nikhildsahu) 

[https://nikhilsahu.me/](https://nikhilsahu.me/)
