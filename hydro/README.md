# Hydro data

Hydro data is based on the TYNDP2018 GCA (global climate action) vision. 
However it should be noted, that due to the low cost and the limited potential 
of hydro power, the installed capacities within the vision and years of the TYNDP
do not differ significantly. 

* The reservoir (rsv) capacity is calculated by substracting the column 'hydro-pump 
from column 'hydro turbine' in the original data source. Therefore, it is assumed, 
that each pumped hydro storage (phs) have equal pump/turbine capacities.
* The max-hours for phs is based on Geth et al. 2018. 
* The max-hours for rsv is calculated for each country based on the Restore2050 data, where
rsv storage capacity in TWh is provided in addition to the installed capacity. It is assumed that 
new rsv plants will have the same reservoir sizes in each country as provided in 
current data from the Restore2050 project.
