Modeling and Processing of Time Interval Data for Data-Driven Decision Support
======

Here you can find the data, and schemes used for the validation of our algorithm presented in "Modeling and Processing of Time Interval Data for Data-Driven Decision Support". We submitted the paper at the IEEE International Conference on Systems, Man, and Cybernetics 2014 ([SMC 2014](http://smc2014.org/)). 

* [data](https://github.com/pmeisen/dis-timeintervaldataanalyzer/tree/master/test/net/meisen/dissertation/performance/paper/in2014/smc/data)
 - contains the real-world data used for the test as zipped .csv-files and hsql-database
 - contains the used ETL-processes (we used the Pentaho Data Integrator) to solve the summarizability problems considering ROLAP and to create the zipped files
* [model](https://github.com/pmeisen/dis-timeintervaldataanalyzer/tree/master/test/net/meisen/dissertation/performance/paper/in2014/smc/model)
 - contains the icCube schema used
 - contains the tidaModels used for day and minute granularity