**Public code release for:** A Network Science Cartography of Cognitive Control System Dynamics  
**PhD Candidate Qualifying Examination**, Rutgers University Center for Molecular and Behavioral Neuroscience, 2018  
**Carrisa Cocuzza** (carrisacocuzza@gmail.com), The Cole Lab (http://www.colelab.org/)  

## Rest-to-Task Comparisons
**Purpose**: compare resting state and task state FC estimates; uses nonparametric permutation testing as well as the Mantel test

**Directory**: Contains demo code for assessing rest-to-task changes in FC; e.g., descriptive analyses of changes to FC architecture between resting state and task-evoked state(s); as opposed to mechanistic and/or functional analyses (see below)

## Files
**restFC.m**: a MATLAB function for computing resting-state functional connectivity with Pearson's correlation coefficient; instructions in script comments  
- example files ("discovery set" from corresponding paper): firRestData.mat
**taskFC.m**: a MATLAB function for computing task-state functional connectivity with Pearson's correlation coefficient; instructions in script comments
- example files ("discovery set" from corresponding paper): firTaskData.mat, firTaskDesign.mat
