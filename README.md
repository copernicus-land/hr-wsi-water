# Jupyter Notebook - Copernicus Land Monitoring Service (CLMS) High Resolution Water, Snow & Ice (HR-WSI) products - Water Products

## Description

This notebook is part of the webinar series dedicated to the High-Resolution Water, Snow & Ice (**HR-WSI**) products from the Copernicus Land Monitoring Service (CLMS). It focuses specifically on the **Water** product portfolio:

  - **HRWL** (*High Resolution Water Layer*: WL, WPI, WCL)
  - **WCD** (*Water Cover Duration*)

The notebook guides users through the following workflow:

1.  **Spatial Selection & Download**: Define an Area of Interest (AOI via GeoPackage file, interactive `ipyleaflet` map, or bounding box) and query/download products using the Copernicus Data Space Ecosystem (CDSE) OData API.
2.  **Visualization & Comparison**: Display and overlay different layers (WL, WPI, WCL, WCD) complete with legends and colormaps.
3.  **Data Analysis**:
      - Compute statistics on water cover duration (WCD) and generate custom water masks.
      - Detect hotspots of water surface variation (optionally integrated with the *EU-Hydro* reference network).
      - Analyze annual trend variations in water cover duration.

This notebook can be executed directly on the **CDSE JupyterLab** platform or within a local environment.

## Authors & Contact

  - **Authors**: Christian Gruber, Rupert von der Kammer (GeoVille GmbH, 2026)
  - **CLMS Support**: [Copernicus Land Monitoring Service Desk](https://land.copernicus.eu/en/contact-service-helpdesk)

## Prerequisites & Installation for Local Execution (Visual Studio Code / Conda)

### Prerequisites

  - Install [Conda](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html)
  - Install [Visual Studio Code](https://code.visualstudio.com/download) or JupyterLab

### Python Environment Setup

Create the Conda environment using the provided `water_env.yaml` file:

``` bash
conda env create -f ypnb_env.yaml

```

Activate the environment:

``` bash
conda activate water_env

```

To deactivate the environment when finished:

``` bash
conda deactivate

```

Select the `ypnb_env` kernel in Visual Studio Code or JupyterLab to execute the notebook.

## Legal notice about Copernicus Data
Access to data is based on a principle of full, open and free access as established by the Copernicus data and information policy Regulation (EU) No 1159/2013 of 12 July 2013. This regulation establishes registration and licensing conditions for GMES/Copernicus users and can be found here: http://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32013R1159.  

Free, full and open access to this data set is made on the conditions that:  
1. When distributing or communicating Copernicus dedicated data and Copernicus service information to the public, users shall inform the public of the source of that data and information.  
2. Users shall make sure not to convey the impression to the public that the user's activities are officially endorsed by the Union.  
3. Where that data or information has been adapted or modified, the user shall clearly state this.  
4. The data remain the sole property of the European Union. Any information and data produced in the framework of the action shall be the sole property of the European Union. Any communication and publication by the beneficiary shall acknowledge that the data were produced “with funding by the European Union”.  





