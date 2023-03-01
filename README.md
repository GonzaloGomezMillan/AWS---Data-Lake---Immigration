# **DATA LAKE - IMMIGRATION IN THE USA**

![](images/immigration_usa.jpg)

## **INTRODUCTION**

The purpose of this project is to create a data lake with data about immigration in the USA and other factors that can be used to carry out different types of analysis. 

With this data lake it would be possible to perform analyses about the number of immigrants arriving in the USA, through which airports they arrive or if the temperatures affect their choice of when to travel to the USA, among many other analyses.

The main difficulty of this analysis is to prepare the data in a way that makes it much easier for data scientists and analysts to extract information, conclusions and predictive models from the data.

---

## **DATA LAKE WORKFLOW**

![](images/Data_Lake_Sparkify_Workflow.png)

---

## **DATABASE SCHEMA**

![](images/DataLake_Immigration_USA_Structure.jpg)

---

## **FILES DESCRIPTION**
- **I94 Immigration Data:** : This data comes from the US National Tourism and Trade Office. A data dictionary is included in the workspace. This is where the data comes from. The National Travel and Tourism Office (NTTO) manages the ADIS/I-94 visitor arrivals program in cooperation with the Department of Homeland Security (DHS)/U.S. Customs and Border Protection (CBP). The I-94 provides a count of visitor arrivals to the United States (with stays of 1-night or more and visiting under certain visa types) to calculate U.S. travel and tourism volume exports.  
- **U.S. City Demographic Data:**: This data comes from OpenSoft. You can read more about it [here](https://public.opendatasoft.com/explore/dataset/us-cities-demographics/export/).
- **Airport Code Table:**: This is a simple table of airport codes and corresponding cities. It comes from [here](https://datahub.io/core/airport-codes#data).
- **World Temperature Data:**  This dataset came from Kaggle. You can read more about it [here](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data).
- **faa_code.csv:** File with the FAA Codes. The data comes from [here](https://www.faa.gov/air_traffic/flight_info/aeronav/aero_data/Loc_ID_Search/Encodes_Decodes/).
- **ISO_code_US.csv:** File with the ISO codes of the USA states.
- **I94_SAS_Labels_Descriptions:** File with information about the I95 Immigration Data. In this file is possible to find descriptions of each of the columns which are part of the dataset.

---

## **HOW TO RUN THE SCRIPTS?**

**CREATE AN EMR CLUSTER**

To run this code, it is necessary to create an Amazon EMR (Elastic Map Reduce) cluster. It can be set with the following definition:

![](images/emr_cluster_config.jpg)

After having created the cluster, the notebook can be uploaded and run.

**JUPYTER NOTEBOOK**

The first thing to do is to upload the notebook to the EMR cluster. The Jupyter Notebook has been defined in a way that anyone can choose "Restart and Run All" to run the code.

![](images/run_jupyter_notebook.jpg)

...

---
## **LICENSING, AUTHORS, ACKNOWLEDGEMENTS, ETC.**
- **Author**: The author of this project is Gonzalo Gomez Millan
- **Acknowledgment**: Also noteworthy is the work of **Udacity** by promoting  this analysis as the capstone project for the Data Engineering Nanodegree Program.