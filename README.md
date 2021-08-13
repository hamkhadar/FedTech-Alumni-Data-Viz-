Acceleator Program Alumni Companies  - FedTech
===================

This interface uses dynamic elements to show more
information than can be presented in a single view. Data has been aggregated, organized, and manipulated in order to create this data visualization. The FedTech Accelerator program alumni companies are mapped out in a geographic mercator map, and can be zoomed in on and hovered over for more detailed information. States can be clicked on or searched in order to zoom in and get more information on alumni companies based in those locations. Additionally, a few other supporting visualizations were made to present other metrics about alumni cohorts!

## How To Update Alumni Map?
1. In the data folder, go to 'alumni_list.csv' in order to add a new company to the map add an entry to the bottom of the list following the currect structure: 

id#, program abreviation, TRL(if applicable, website, short description,tech area, program name, latitude, longitude

if a mentric is unavailable for a company, leave the field blank 
example of a new entry:

64,ic,Southwest Research Institute,,https://www.swri.org/,R&D problem solvers providing premier services to government and industry clients,,"San Antonio, Texas ",,29.4241,-98.4936

## Credits
* <a href="https://d3js.org">D3.js</a>
* <a href="http://bl.ocks.org">US Map JSON</a>
