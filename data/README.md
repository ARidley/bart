Data files
==========

#### Salary data notes:
BART Salaries were scraped from http://www.mercurynews.com/salaries/bay-area
and are composed of several sections:

**Name**: employee's name  
**Title**: Job Title  
**Family**: Job family (as categorized by BART's website)  
**Base**: base salary for calendar year  
**OT**: over time pay  
**Other**: Lump sump payouts for vacation, sick leave and comp time, bonuses and other taxable cash payments  
**MDV**: Employer contributions to medical, dental and vision plans
**ER**: Employer contribution to pension  
**EE**: Employee contribution to pension paid by the employer  
**DC**: Employer contribution to deferred compensation (eg. 401(k) or 403(b) plans)  
**Misc**: Other non-cash costs of employment  
**TCOE**: Total cost of ownership  


### BART Data  
* Employee Salaries
	+ Non-Management: https://github.com/enjalot/bart/blob/master/data/bart-compensation_non-mgmt-categorized.csv
	+ Management (no police): https://github.com/enjalot/bart/blob/master/data/bart-compensation_mgmt-categorized.csv
	+ source: John Osborn https://docs.google.com/spreadsheet/ccc?key=0AiFtsy5d3JwNdE9tOWRtbmh5WTJSYnpaNktwUWJjYnc#gid=3  
	+ scraped from http://www.mercurynews.com/salaries/bay-area
* Job families and union memberships: 
 	+ https://github.com/enjalot/bart/blob/master/data/job_families.csv
	+ source: http://bart.gov/about/jobs/descriptions/index.aspx
* Ridership https://github.com/enjalot/bart/tree/master/data/ridership
	+ source: http://www.bart.gov/about/reports/ridership.aspx
* Union contracts (detail the benefits for each union): http://bart.gov/about/jobs/cba.aspx
* BART's 2013 financials are available in a PDF (page 5) http://www.bart.gov/docs/financials/FY2013_BART_Budget.pdf
* https://en.wikipedia.org/wiki/Bay_Area_Rapid_Transit
* http://en.wikipedia.org/wiki/History_of_the_Bay_Area_Rapid_Transit
* Municiple tax shelters http://groups.yahoo.com/group/BATN/message/42479
* Median income at BART stations http://dangrover.github.io/sf-transit-inequality https://github.com/dangrover/sf-transit-inequality
* History of Raises: 2001 - 2005, 22% raise (source: http://www.sfgate.com/bayarea/article/BAY-AREA-BART-pay-ranks-high-for-transit-2624636.php)

### Highway Data  
* Traffic volume on Cali highways (search for bay bridge) http://www.dot.ca.gov/hq/traffops/saferesr/trafdata/2012TrafficVolumes.pdf
* HOV lane data http://www.dot.ca.gov/dist4/highwayops/docs/2011%20Revised%20HOV%20Report.pdf
* Traffic data http://www.dot.ca.gov/hq/traffops/saferesr/trafdata/index.htm  

### AC Transit  
* Salaries https://github.com/enjalot/bart/blob/master/data/actransit-compensation_all.csv  

### MUNI Data
* Salaries http://publicpay.ca.gov/Reports/PositionDetail.aspx?employeeid=3940543
* Bus ridership in SF (1 week) https://github.com/swissnexSF/Urban-Data-Challenge/tree/master/public-transportation/san-francisco/geo/topojson
* GIS bus routes + stops in SF https://github.com/swissnexSF/Urban-Data-Challenge/tree/master/public-transportation/san-francisco/geo/topojson
* bus routes sketch: http://tributary.io/inlet/5021432

### Surrounding Data  
CA MTC http://dataportal.mtc.ca.gov/spatial-library.aspx  
GIS data (maps, census) http://www.mtc.ca.gov/maps_and_data/GIS/data.htm (shp files converted to geojson and topojson)  
Bay Area TOPOJSON: https://github.com/enjalot/bart/blob/master/data/bayareaTOPO.json
US Atlas https://github.com/mbostock/us-atlas  
Bay Area census http://www.bayareacensus.ca.gov/historical/historical.htm (countypopulations.csv top10cities.csv)  
U.S. monthly inflation http://www.usinflationcalculator.com/inflation/historical-inflation-rates/ (stored in monthlyinflation.csv)  
Family Budget data: https://groups.google.com/forum/#!topic/bart-hackers/5rZCtiwQaVI
BLS U.S. Historical Wage Data, 2001 - 2013 (Current Dollar) ftp://ftp.bls.gov/pub/suppl/eci.echistrynaics.txt  
FRED (economic data) http://research.stlouisfed.org/fred2/  
Cost of Living:  
* data: https://github.com/enjalot/bart/tree/master/data/costofliving
* source: http://www.epi.org/files/2013/2013-family-budget-calculator.xlsx
* source: https://en.wikipedia.org/wiki/List_of_metro_systems  
* more SF: http://cost-of-living.findthedata.org/l/60/San-Francisco-CA-Metro-Area  

I'd be interested in looking at the property values surrounding BART stations with the Trulia API http://developer.trulia.com/  

California State Data Center
http://www.dof.ca.gov/research/demographic/state_census_data_center/census_2010/view.php

Longitudinal Employer-Household Dynamics (LEHD) public-use data products  
http://lehd.did.census.gov/

Beyond the Shutdown: U.S. Government Data on ArcGIS Online  
http://blogs.esri.com/esri/arcgis/2013/10/04/beyond-shutdown-us-government-data-on-arcgis-online/  

CensusReporter
http://censusreporter.tumblr.com/

Detailed State Files for California (2013)  
block groups: http://openstreetmap.us/~migurski/TIGER-Areas/tl_2013_06_bg.zip  
places: http://openstreetmap.us/~migurski/TIGER-Areas/tl_2013_06_place.zip  
blocks: http://openstreetmap.us/~migurski/TIGER-Areas/tl_2013_06_tabblock.zip  
tracts: http://openstreetmap.us/~migurski/TIGER-Areas/tl_2013_06_tract.zip  

Census Transportation Planning Package (CTPP2000)  
http://www.mtc.ca.gov/maps_and_data/datamart/census/ctpp2000/  

US CTPP using ACS 2006-2010 (5-Year Summary)  
http://www.fhwa.dot.gov/planning/census_issues/ctpp/data_products/acsdataprod.cfm  

Additional Data for San Francisco data.sfgov.org  

BART Districts in San Francisco (Zipped Shapefile Format) https://data.sfgov.org/download/mnn6-ac5f/ZIP  

Stop locations for all of public transit routes that serve San Francisco. Records indicate stop location and name, the associated  
https://data.sfgov.org/download/s593-yv8k/SHAPEFILE  

Incidents derived from SFPD Crime Incident Reporting system. Previous month. Updated daily  
https://data.sfgov.org/Public-Safety/SFPD-Incidents-Previous-Three-Months/tmnf-yvry  

Industry Classification via BLS:  
Transportation and Warehousing: NAICS 48-49  
The transit and ground passenger transportation subsector (NAICS 485) consists of these industry groups:  
* Urban Transit Systems: NAICS 4851
* Interurban and Rural Bus Transportation: NAICS 4852
* Taxi and Limousine Service: NAICS 4853
* School and Employee Bus Transportation: NAICS 4854
* Charter Bus Industry: NAICS 4855
* Other Transit and Ground Passenger Transportation: NAICS 4859