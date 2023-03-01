# Strong-Connectivity-in-Real-Networks



This code was used to generate the results of of the paper "Strong Connectivity in Real Directed Networks" by Niall Rodgers, Peter Tino and Samuel Johnson.

The code generates networks of varying Trophic Incoherence, measures networks strcutural properties and does various dynamics.

The code is written in Julia and has a range of julia dependancies such as Graphs.jl and other common Julia packages. The code relies on the paths to the data that I have setup and this will need to be modified to run on your machine. It is is also setup to take account of the different data formats which come from different sources and hard coded to this setup so may requre a little editing to change to another file system. The code is also in the form of a jupyter notebook so this format is also a dependacy of the code. The code also contains extra functionlaity not required for the paper. 

Trophic Analysis only invovles solving a matrix equation and a simple calculation to get the incoherence so should be accesible to researchers in many fields who are not familair with julia or this particular code which contains a lot of extra data, analysis and results from other papers.

I am happy to discuss with other researchers how to implent Trophic Analysis for yourself or questions about the subject. More Trophic Analysis code is avaliable in other repositories on my Github.

My papers are https://scholar.google.com/citations?user=646U--wAAAAJ&hl=en

And contact details until end of 2024 are NXR081@student.bham.ac.uk
