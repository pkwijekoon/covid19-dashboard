
**The Covid 19 Dashboard for Sri Lanka**

This [Covid 19 dashboard: the case of Sri Lanka](https://www.antoinesoetewey.com/files/coronavirus-dashboard.html) provides an overview of the 2019 Novel Coronavirus COVID-19 (2019-nCoV) epidemic for Sri Lanka. This dashboard is developed using the [flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/) framework in R/R Studio, and by referring the following two dashboards:  
1. [dashboard](https://ramikrispin.github.io/coronavirus_dashboard/){target="_blank"} developed by Rami Krispin, and  
2. [dashboard](https://www.antoinesoetewey.com/files/coronavirus-dashboard.html) developed by Antoine Soetewey.  

**Data**

This data set contains the following fields:  
* ```date``` - The date of the summary  
* ```province``` - The province or state, when applicable  
* ```country``` - The country or region name  
* ```lat``` - Latitude point  
* ```long``` - Longitude point  
* ```type``` - the type of case (i.e., confirmed, death)  
* ```cases``` - the number of daily cases (corresponding to the case type)  

Download the data set from  [`{coronavirus}`](https://github.com/RamiKrispin/coronavirus){target="_blank"} R package. Make sure to download the development version of the package to have the latest data:

```
install.packages("devtools")
devtools::install_github("RamiKrispin/coronavirus")
```

The data and dashboard are refreshed on a daily basis.

The raw data is pulled from the Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE) Coronavirus [repository](https://github.com/RamiKrispin/coronavirus-csv){target="_blank"}.  


**Information**  
More information about this dashboard can be found in this [article](https://www.statsandr.com/blog/how-to-create-a-simple-coronavirus-dashboard-specific-to-your-country-in-r/).  


**Update**  
The dashboard has been updated on `r format(Sys.time(), "%A %B %d, %Y")`.

