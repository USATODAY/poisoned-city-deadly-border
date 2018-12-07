# About the data

In investigating pollution in Mexicali and the surrounding area, The Desert Sun obtained data from a variety of sources. The data included: air-quality measurements from Mexican and California agencies and the World Health Organization; environmental enforcement data from Baja California's Environmental Protection Department; health and death statistics from the Mexican government; data on water quality and sewage spills from the International Boundary and Water Commission; water quality data from the California Regional Water Quality Control Board; data on pollution emissions in Mexicali from Mexico's federal Ministry of Environment and Natural Resources; data on wastewater infrastructure spending from the North American Development Bank; records from the U.S. Environmental Protection Agency describing shipments of hazardous waste from the U.S. to Mexico; as well as data from scientific studies, government reports and other sources. Some of the data and records were obtained through requests to U.S. government agencies under the Freedom of Information Act, or through formal requests to Mexican government agencies. Other datasets were obtained from government websites.

Here's more information about the data, how it was obtained, and how it was analyzed:

## Demographics

### Mexicali Death Rates

Data sources: Mexico's National Population Council (Consejo Nacional de Población, or CONAPO) 2010 - 2016 population, provided at the state and local level in response to requests from The Desert Sun.

[Mexico's National Institute of Statistics and Geography (Instituto Nacional de Estadística y Geografía, or INEGI)](https://www.inegi.org.mx/datos/) Statistical Administrative Registries

`Datos > Programas > Registros administrativos- estadísticas > Vitales > Mortalidad > Tabulados > Tabulados Interactivos > Mortalidad general`

**Select the following then click "Ver consulta"**

-Entidad y municipio de registro

-Causas detalladas CIE

-Año de registro (pre-selected)

At the top of the page,

1. Change "total" to "CIE - 10/2"
2. Select "Causas detalladas CIE"
3. Select J00-J99 (Enfermedades del sistema respiratorio)
4. Expand "Baja California" to include all municipios (Ensenada, Mexicali, Tijuana)
5. Export the table

For each year, calculate the death rate based on population of each municipio, state (for Baja California) and country, if using Excel, employ the VLOOKUP formula to correspond with annual population for each geography and year. (Note: regional population data was obtained from CONAPO following requests from the Desert Sun.) Death rate is calculated per 100,000 people.

Respiratory illnesses (all diseases classified J00-J99) are compared for Baja California, Ensenada, Mexicali, Tijuana and Mexico.

### Population Growth

Data Sources: U.S. Census Bureau, [INEGI](https://www.inegi.org.mx/anterior/), [California Dept. of Finance Demographic Research Unit](http://www.dof.ca.gov/Forecasting/Demographics/Estimates/E-4/2010-18/), CONAPO

**Mexico's population in 5-year increments from 1990 onward:**

Estadistica > Fuentes/Proyectos > [Censeos y conteos de población y vivienda](http://www.beta.inegi.org.mx/programas/ccpv/cpvsh/)

For each year, select "Microdatos", and scroll down > "Principales resultados por localidad (ITER)" > Bases de datos > Baja California, then download XLS or TXT file.

POBTOTAL is the Total population

              Total municipio:                            NOM\_MUN = "Mexicali" and NOM\_LOC= "Total Municipal"

              Urban/Mexicali population         NOM\_MUN = "Mexicali" and NOM\_LOC= "Mexicali"

              Rural population                           =Total population - Urban population

CONAPO provided detailed population at the state and local level in response to requests from The Desert Sun.

**Calexico population**

From the [American Fact Finder](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml), select Advanced search > Geographies > Select geographic type > Place  - 160 > Select a state > California > Select one of more geographic areas > "Calexico city, California" > Add to  your selections

Close window and under the "Show results from:" Field change "All available years" to the years of interest.

2000 table: DP-1; 2010 Census Summary File (SF1)

1995, 2005, and 2011-2017 sources: California Department of Finance Demographic Research Unit [E-4 Historical Population Estimates for Cities, Counties, and the State](http://www.dof.ca.gov/Forecasting/Demographics/Estimates/)

### Economic Disparities

Source: U.S. Census Bureau

Data for Calexico, California and the state of California are pulled from the [American Fact Finder](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml), including percent Hispanic or Latino, percent of population with a bachelor's degree or higher, median household income (in 2016 dollars), and persons in poverty (percent).

## New River analyses

### Sediment analyses – Heavy metals, PAHs, PCBs, DDTs, DDEs

Data Sources:  The [California Environmental Data Exchange Network (CEDEN)](https://ceden.waterboards.ca.gov/AdvancedQueryTool); Schlenk, D., Bui, C., and Lamerdin, C. [Evaluation of Sediment, Water and Fish Tissue for Contaminant Levels in the Salton Sea and its Two Primary Tributaries, the Alamo River and New River from 2001-2012](https://www.waterboards.ca.gov/water_issues/programs/swamp/docs/reglrpts/ss_fnl_eval.pdf), Appendix A of Xu, E., Bui, C., Lamerdin, C. & Schlenk, D. (2016, July 15) Spatial and temporal assessment of environmental contaminants in water, sediments and fish of the Salton Sea and its two primary tributaries, California, USA, from 2002 to 2012. _Science of The Total Environment_, Volume 559 pages 130-140. [https://doi.org/10.1016/j.scitotenv.2016.03.144](https://doi.org/10.1016/j.scitotenv.2016.03.144)

Email ZIP file with the following: RESULT CATEGORY "Water Quality"; Select County: Imperial; Program: Surface Water Ambient Monitoring Program; ParentProgram: SWAMP RWB7 and SWAMP Stream Pollution Trends; Date range: all available.

_Additional parameter restrictions are not restrained: Parameter groups, parameters, stations, matrixes_

About the CEDEN Water Quality data (an Appendix to the SWAMP data is available [here](http://rcflood.org/downloads/NPDES/Documents/Monitoring/VolumeII_Appendices/AppendixI.pdf)).

- Station Name: _select New River stations_
- MatrixName: select sediment samples
- Analyte: select
- Unit: reference unit (e.g. mg/Kg dw, ng/g dw)
- Result: numeric quantity, if blank, refer to "ResultQualCode" colum
- ResultQualCode: "ND" signifies "not detected" and lowest Method Detection Limit (MDL); "=" is the result, "DNQ" is Detected not quantified, which qualifies samples that are above the MDL, but below the Reporting Limit (RL) where values are determined nonquantifiable.

About the Schlenk, Bui & Lamerdin toxicity threshold data:

A chart on pages 42 and 43 of the 2014 Schlenk et al., report shows threshold values for sediment contaminants. Metals are evaluated by mg/kg dw (dry weight), and PAHs, PCBs, DDEs, and DDTs are measured in ng/g dw. Each threshold is used for individual analytes.

Analysis:

- **Heavy metals, PAHs**

Sediment samples for each metal (cadmium, copper, lead, mercury, etc.) are analyzed by site according to its respective threshold.  Readings that are listed as ND are included in the samples that do not exceed the threshold. Percentages of samples that exceed the threshold are calculated for each Station.

- **PCBs, DDTs and DDEs**

Similar to the metals analysis, these compounds are analyzed by site according to their respective threshold. Since PCBs, DDTs, and DDEs include multiple compounds or anions, these are first summed by site per day to create a total score (e.g. total number of PCBs measured in sediment at the New River Boundary on May X, 2008). This analysis was done using an Excel pivot table for all PCBs, DDTs, or DDEs found in the sediment. Once summated, the total is compared against the threshold included in the Schlenk study and a percentage of samples exceeding the criteria by site is calculated.

### Hyalella Toxicity Testing

Data Sources:  [CEDEN](https://ceden.waterboards.ca.gov/AdvancedQueryTool);

Email ZIP file with the following: RESULT CATEGORY: Toxicity; Program: Surface Water Ambient Monitoring Program; Parameter groups: Toxicity; Dates: select all available

_Additional parameter restrictions are not restrained_

About the CEDEN Toxicity data

In a laboratory, aquatic organisms are exposed to sediment samples taken from each river. The organisms are put into beakers or other glass containers with the sediment sample and clean water. In the case of the amphipod_Hyalella azteca,_ these creatures are usually in their second week of life (a lifespan that lasts about 45 days) and should be in growing stages. After a short period (10 days for _Hyalella_) organisms are examined for survival rates and then weighed for their growth during the time period. Analyses are compared to a control sample of the same species tested in a clean sediment and clean water environment.

- Waterway: select _New River_
- Station Name: specific New River locations remain
- OrganismName: different species tested for toxicity; select _Hyalella azteca_, which is the most widely used
- MatrixName: samplewater, sediment, and sediment interstitialwater are options; select "sediment"
- Analyte: filter for Growth (wt/surv indiv), Survival, and Young/female
- SigEffectCode: Filter out blank results which do not have a toxicity analysis; in subsequent analysis filter for significant toxic samples "S" and "SL" which are statistically significant results where the resulting growth, survival and fertility results are less than the Critical Value and significant compared to the control sample at the alpha level. (SigEffectCode glossary available [here](http://ceden.org/CEDEN_Checker/Checker/DisplayCEDENLookUp.php?List=SigEffectLookUp).)

Analysis:

- **Toxicity of the New River**

The CEDEN Toxicity data is limited to Waterway "New River", MatrixName "sediment", Organism "Hyalella azteca" and all blank "SigEffectCode" results are removed.

For each StationName the number of samples evaluated is calculated. The significantly toxic results are then calculated as a subset, limiting the analysis to results with a SigEffectCode of "S" or "SL". For each StationName the number of toxic ("S" or "SL") samples is summed to create a proportion of results found to be toxic.

- **Toxicity of New River compared to other California rivers**

Data is first cleaned to exclude lakes, country clubs, drains, sloughs, harbors, creeks and other waterbodies that are not rivers.

For each river, the number of toxic samples ("S" and "SL") are calculated as a percentage of all samples tested. The same exclusions, such as limiting this to the same species, Hyalella azteca, and sediment sample exposure, are applied.

Rivers are subsequently ranked based on decreasing percentage of toxic samples.

### Fecal Coliform Bacteria

Data source: California Water Boards [Region 7 New River Water Quality Data](https://www.waterboards.ca.gov/rwqcb7/water_issues/programs/new_river/dataindex.html)

Monthly fecal coliform bacteria counts are recorded for the New River using water samples taken near the border. The concentrations of fecal coliform bacteria are measured with an estimation called "most probable number," or MPN, per 100 milliliters of water. The monthly results are displayed alongside California's safe swimming threshold, or state regulators' objective for freshwater, which is 400 (MPN) per 100mL. For some months, an average of multiple water tests is included.

### Spending on Wastewater

Data source: North American Development Bank (NADB)

Jointly funded wastewater projects in Mexicali are analyzed, including U.S. government funding (from the Environmental Protection Agency (EPA) through the Border Environment Infrastructure Fund (BEIF)), NADB-funded loans, and funding by Mexican government sources.

Annual disbursements of EPA funding is charted for BEIF grants for wastewater projects.

### Sewage Spills

Data source: International Boundary and Water Commission (IBWC)

Information about sewage spills was obtained from the U.S. Section of the IBWC through a Freedom of Information Act request. The data provided on reported sewage spills included a mix of sewage volumes and flow rates.

In cases when no estimated total volume was given, the estimated sewage spills are calculated based on the duration of the events.

1. Date and time data were placed in separate columns so total number of days that equipment or facilities were not functioning could be calculated. If a multi-day spill was listed but no start/stop time included, start and end days' duration was calculated by:
  1. Averaging both (1) the length of all single-day disruptions, and (2) the length of all single-day disruption events that were at least four hours and thus more likely to be a multi-day disruption.
  2. These averaged 4.8 hours for all single-day events, and 6.9 hours for longer events.
2. A multiday event's duration was calculated by subtracting End Date – Start date = X.

(24 hours/day)\*(X days)+6.9 hours

1. A single day event's duration where no start or end time was provided was estimated as a 4.8-hour spill.
2. Volume was converted from liters per second to cubic meters per hours, where 1 liter-per-second is equal to 3.6 cubic meters per hour.
3. The estimated flow rates provided by the IBWC were used to calculate the volume. One spill did not include a flow rate for Pumping Plant #4, in this case, other reported outages for PP#4 were averages (120lps, 225lps, and 300lps) to estimate the flow for this instance.
4. For any spill event that there was not an estimated total volume, this was calculated as hours \* bypass speed (in cubic meters per hour).

## Other data sources on pollution and enforcement

### Fines

The Baja California Environmental Protection Department (Secretaría de Protección al Ambiente de Baja California, or SPA) released documents detailing inspections and fines during 2016 and 2017 in response to a request by The Desert Sun.

The documents were reviewed for information including whether a fine was issued or not, the type of business and the type of violation or irregularities described by regulators.

The 2016 and 2017 fines were listed in units including multiples of the current minimum (daily) wage or the UMA (unit of measurement), which financial indices are tied to in Mexico. These amounts were converted to pesos, and then converted to dollars using the Internal Revenue Service's average exchange rates for 2016 and 2017, at 19.435 and 19.679 pesos per dollar, respectively. The current minimum wage in 2016 was the same as the 2016 UMA at 73.04 pesos. In 2017 the current minimum wage was 80.04 pesos and the UMA was 75.49 pesos.

### Federal Pollution Emissions Database

Mexico's Ministry of Environment and Natural Resources (Secretaría de Medio Ambiente y Recursos Naturales, or SEMARNAT)[maintains a national database](https://www.gob.mx/semarnat/acciones-y-programas/registro-de-emisiones-y-transferencia-de-contaminantes-retc) of companies' self-reported information on emissions of air pollution, discharges of water pollution, waste that affects soil, and hazardous waste generated. This database, called the Registro de Emisiones y Transferencia de Contaminantes (Pollutant Release and Transfer Register), includes any of 104 substances that industries emit to the environment through air, water, and soil, or are transferred in wastewater or hazardous waste. This information is available in the online database for the subset of companies in Mexico that are regulated by the federal government, and includes data on the company name, industrial sector, year and the substance emitted or transferred.

## Air pollution analyses

### PM2.5 comparison

Data source: California Air Resources Board [Air Quality and Meteorological Information System](https://www.arb.ca.gov/aqmis2/aqdselect.php)

Yearly averages were calculated from 24-hour daily levels recorded by CARB at selected monitoring sites, including Mexicali and several California cities. An EPA grant funded two years of monitoring in Mexicali that ended April 2018.

The analysis included all available 24-hour daily data for the selected locations during 2017. The data were grouped by site and averages were calculated.

### PM10 comparison

Data source: [World Health Organization](http://www.who.int/airpollution/data/cities/en/) Ambient (outdoor) air quality database, by country and city (available on webpage’s sidebar)

A comparison is created by selecting all sites with "measured" PM10 readings (excluding those that are "converted" from PM2.5 readings to PM10 values and therefore less reliable) in the year 2016, which is the most recent year in the WHO database, located in the "Americas" region. U.S. sites are not included in the comparison because only "converted" values are available for PM10 at U.S. sites. However, the available "converted" values for all U.S. sites are significantly lower than the measurements for Mexicali and other locations near the top of the list. Canadian sites are excluded from the comparison because there were no readings available from 2016 for Canadian sites. However, the most recent PM10 measurements that are available for Canadian sites in 2015 show they also had significantly lower values than Mexicali and other locations near the top of the list.

### IVAN Air Monitoring PM2.5 map

Data source: [Identifying Violations Affecting Neighborhoods (IVAN)](https://ivan-imperial.org/resources/airfaqs#aboutTheData) Air Monitoring

The Desert Sun requested data from the IVAN Air Monitoring, a network of air monitors in the Imperial Valley.

PM2.5 hourly readings were selected from 2017, which is the most recent complete year. The data were grouped by location, and yearly averages were calculated by location. Values are plotted on a map using the latitude and longitude of the IVAN Air Monitoring sites.

### Air Quality Index comparison

Data source: Imperial County Air Pollution Control District, U.S. EPA

Air-quality data for 2000 through 2016 was provided by the Imperial County Air Quality Control District. The data list air quality levels by data, location and Air Quality Index level of health concern.

The EPA tracks air quality and records it using this index. The EPA says the following about the [Air Quality Index](https://airnow.gov/): "The AQI is an index for reporting daily air quality. It tells you how clean or polluted your air is, and what associated health effects might be a concern for you. The AQI focuses on health effects you may experience within a few hours or days after breathing polluted air. EPA calculates the AQI for five major air pollutants regulated by the Clean Air Act: ground-level ozone, particle pollution (also known as particulate matter), carbon monoxide, sulfur dioxide, and nitrogen dioxide. For each of these pollutants, EPA has established national air quality standards to protect public health. Ground-level ozone and airborne particles are the two pollutants that pose the greatest threat to human health in this country."

Each day is assigned a value, and these values are categorized as:

0 to 50 = Good

51 to 100 = Moderate

101 to 150 = Unhealthy for Sensitive Groups

151 to 200 = Unhealthy

201 to 300 = Very Unhealthy

301 to 500 = Hazardous

A comparison was created by analyzing the AQI data for all available dates from monitoring sites in Brawley, Calexico, El Centro, Niland, and Westmorland, California, from 2003 to 2016. The analysis involved tallying the number of days that fall into each AQI category at each site, and calculating the percentage of days that register as anything higher than the "good" threshold of 0-50 (AQI > 50).
