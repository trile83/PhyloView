# Data for PhyloView
 Visualization of COVID-19 Phylogenetic Data<br>
This is the first step to acquire COVID-19 phylogenetic data for the visualization. The data are available publicly on GISAID website with its visualization for Louisiana state. The time span of the data is between December 1st, 2019 to October 1st, 2021.<br>
The provided Jupyter notebook contains the Python code to request the data directly from GISAID website, and output the data into a graph file format (.gv) that can be open in Gephi and then can be exported to .csv format.
Publically accessible link to Global COVID-19 [ArcGIS Dashboard](https://insights.arcgis.com/index.html#/view/3e44d3af2a534efda911009420051e32)

## ArcGIS Insights Dashboard Example
### Louisiana Dashboard
#### The first use case using locally available data of the state of Louisiana, USA.
![Louisiana Dashboard](/img/dashboard_LA.PNG) <br> 

#### Phylogenetic Network
![Louisiana Phylogenetic Network](/img/phylogenetic_network_LA.PNG) <br>

#### Geographic Network
![Louisiana Geographic Network](/img/geo_network_LA.PNG) <br>

### Global COVID-19 Dashboard using directly GISAID data
#### Dashboard
![Previous Global Dashboard](/img/dashboard_global_0.PNG) <br>

#### Geographic Network using the provided geographic data (aggregated to continental level)
![Previous Global Geographic Network](/img/geo_network_global_0.PNG) <br>


### Global COVID-19 Dashboard after applying ACCTRAN on the global GISAID data
#### Geographic Network
![ACCTRAN Global Geographic Network](/img/geo_network_global_1.PNG) <br>
