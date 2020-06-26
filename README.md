# MP_Analyzer

<br>
<br>

<h1>Boulders:</h1>

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Boulder%20Grade%20vs.%20Quantity.png?raw=true)

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Boulder%20Grade%20vs.%20Quality.png?raw=true)

<h1>Sport Routes:</h1>

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Sport%20Grade%20vs.%20Quantity.png?raw=true)

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Sport%20Grade%20vs.%20Quality.png?raw=true)

<h1>Trad Routes:</h1>

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Trad%20Grade%20vs.%20Quantity.png?raw=true)

![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/Trad%20Grade%20vs.%20Quality.png?raw=true)


<strong>[WARNING]</strong> please do not crawl all of mountain project with this script. This will slow down their servers. Data from a signifigant portion of mountain project is included below.

This is a webcrawler for MountainProject.com. It collects data on many types of climbing routes (boulder,sport,trad) and give stats about the number of each grade of route and the average quality ratings for each grade. The data shown above represents around 20% of the climbs on mountain project.

Syntax: 'python3 mp-analyzer [num]' or './mp_analyzer [num]'

[num] is the number of total routes (sport + trad + boulder + toprope) that you want to crawl. Choose a small number to test for yourself.

When running, the terminal will display routes and their meta data as they are discovered.


![alt text](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/running_example.png?raw=true)


At regular intervals the program output will be written to a file "output.txt". An example of this format is below.

![output.txt](https://github.com/jimphowe/MP_Analyzer/blob/master/resources/output.txt?raw=true)
