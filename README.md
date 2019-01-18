# < Dat Air >

### Groups
* < 李右元, 107753027 >
* < 楊晴焱, 107155018 >

### Goal
AQI(Air Quality Index), a measurement to evaluate status of air safety and cleanliness, is derived from numerical formula defined by EPA (Environmental Protection Agency), which uses weighted values of concentration from diffrent gases and selects one with maxmium. Since it takes the result of the quantity over gases and they come from things in our daily lives, this triggers us bringing out a question: can we use the quantity of things emitting these gases contributing to AQI index to predict it?   
     

### Demo
* Code execution <br />
     We recommend that one download the entire master branch file folder as zip and decompress it, and switch the root layer under this master-branch titled folder with typing the following command on your R terminal to execute the code named after "final.R".  
```
Rscript code/final.R
```

* Data Visualization <br />
     We simply output the performances of the models as png pictures in this code by different dimensions from aiding research pourposes directly without extra access to the internet.<br />
     <br />
     The output pictures are at folder named after "results", and the directory format looks like:<br />
     results/[The Dimension Folder Name]<br />
     <br />
     For the details about analysis dimensions mentioned above, please check at the "Results" segment below for detailed information.
## Folder organization and its related information

### Docs
* Presentation slides demonstrated on Jan 15, 2019
* Feature definition of Source data in word documentation

### Data

* Source <br />     
     We collected the AQI results among all cities in Taiwan every month from 2005-2016, and the related features of AQI contributors  such as the monthly numbers of Motorbike&Car,Garbage&Waste generated, air pollution penalty&auditory cases for the project analysis.
<br />
* Input format
* Any preprocessing?
  * Handle missing data
  * Scale value

### Code

* Which method do you use?
* What is a null model for comparison?
* How do your perform evaluation? ie. Cross-validation, or extra separated data

### Results

* Which metric do you use 
  * precision, recall, R-square
* Is your improvement significant?
* What is the challenge part of your project?
