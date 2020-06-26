# MP_Analyzer

[WARNING] please do not crawl all of mountain project with this script. This will slow down their servers. Data from a signifigant portion of mountain project is included below.

This is a webcrawler for MountainProject.com

It collects data on many types of climbing routes (boulder,sport,trad) and give stats about the number of each grade of route and the average quality ratings for each grade.

Syntax:

python3 mp-analyzer [num]
or
./mp_analyzer [num]

[num] is the number of total routes (sport + trad + boulder + toprope) that you want to crawl. Choose a small number to test for yourself. Additional results are included in this repository.


When running, the terminal will display routes and their meta dat as they are discovered.


![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/running_example.png?raw=true)


At regular intervals the rogram output will be written to a file "output.txt". An example of this format is below.

![output.txt](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/output.txt?raw=true)

<h1>Results in graph form, representing 20-25% of the climbs on mountain project:</h1>

<h2>Boulders:</h2>

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Boulder%20Grade%20vs.%20Quantity.png?raw=true)

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Boulder%20Grade%20vs.%20Quality.png?raw=true)


