# Strong-Connectivity-in-Real-Networks



This code was used to generate the results of of the paper "Strong Connectivity in Real Directed Networks" by Niall Rodgers, Peter Tino and Samuel Johnson.

The code generates networks of varying Trophic Incoherence, measures network strcutural properties and does various dynamics.

The code is written in Julia and has a range of Julia dependancies such as Graphs.jl and other common Julia packages. The code relies on the paths to the data that I have setup and this will need to be modified to run on your machine. It is is also setup to take account of the different data formats which come from different sources and is hard coded to this, so may requre a little editing to change to another file system. The code is also in the form of a jupyter notebook so this is required to run the code. The code also contains extra functionality not required for the paper which may display errors. 

The code can be modified to take in the data used in the paper and reproduce the results of it. 

The code named " Strong Connectivity Github Julia Networks_Real_Networks-Extra Data" provides the bulk of the structural paper results. While the backwards attack code can remove backwards edges and the rest create time series of the dynamics for which they are named. 

Trophic Analysis only invovles solving a matrix equation and a simple calculation to get the incoherence so should be accesible to researchers in many fields who are not familair with Julia or this particular code which contains a lot of extra data, analysis and results from other papers from throughout my early PhD. At some point in the future I would like to release a more tutorial-like code.

I am happy to discuss with other researchers how to implent Trophic Analysis for yourself or questions about the subject. More Trophic Analysis code is avaliable in other repositories on my Github.

My papers are https://scholar.google.com/citations?user=646U--wAAAAJ&hl=en

And contact details until end of 2024 are NXR081@student.bham.ac.uk
