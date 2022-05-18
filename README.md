# awc_plot
Plot Aanganwadi centres 

## Code1
PLOT_AWC_KARNATAKA.ipynb
This is python code to plot Aanganwadi centre details for the state of Karnataka. 

### Input files

1. AWC details awc_monitoring_details_final_(district_code).csv for the district of Bangalore Urban
2. AWC geo-location for all districts in the state
The above 2 files are created by code in the awc_details repository
  
### Output files

awc_scatter_karnataka.html - an interactive map with AWC details

### Installations required

Requires Python and dependencies, Plotly for plotting

### Usage

1. Download the .ipynb file to a folder on your system
2. Input files must be available in the same folder as the .ipynb file
3. Output html plot is created in the same folder as the .ipynb file once the code runs successfully. Output file will auto open in a new tab.

## Code2
PLOT_BLR_URBAN.ipynb
This is python code to plot Aanganwadi centre details for Bangalore urban with added layers such as the EB and ward boundaries and neighbourhood type (socio-economic status). 

### Input files

1. AWC details 'awc_monitoring_details_final_572.csv' for the district of Bangalore Urban
2. AWC geo-location 'awc_572.csv' for Bangalore Urban
The above 2 files are created by code in the awc_details repository
3. EB boundaries for Bangalore (not available in the public domain)
4. Neighbourhood typology for wards in Bangalore (not available in the public domain)
  
### Output files

awc_scatter_gsl_type_eb_blr.html - an interactive map with AWC details

## Installations required

Requires Python and dependencies, geopandas, json, Plotly for plotting

## Usage

1. Download the .ipynb file to a folder on your system
2. Input files must be available in the same folder as the .ipynb file. Shape files are currently accessed under a separate file path.
3. Output html plot is created in the same folder as the .ipynb file once the code runs successfully. Output file will auto open in a new tab.
