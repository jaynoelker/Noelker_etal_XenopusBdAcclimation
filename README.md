# Noelker_etal_XenopusBdAcclimation
This study investigates the effects of acclimation and performance temperatures on _Xenopus laevis_ Bd infections from skin swabs and filters measuring zoospore production.

**TITLE:** _Dynamic effects of thermal acclimation on chytridiomycosis infection intensity and transmission potential in Xenopus laevis_

James E. Noelker (Corresponding author: jaynoelker@gmail.com)

Vitoria Abreu Ruozzi

Kyle D. Spengler

Hunter M. Craig

Thomas R. Raffel (Principle investigator)

===========================================================================

**File 1:** _Experiment1&2.TemperatureData.csv_

CSV of temperature data from Experiment 1 & 2 comparing target temperatures with data collected using HOBO temperature loggers in each incubator.

| Variable name | Description |
| --- | --- |
| **Experiment** | unique identifier for each experiment as either 2021.IndInf for Experiment 1 and 2022.IndInf for Experiment 2 |
| **IncNum** | each incubator's identification number |
| **Block** | spatial block for each incubator form Experiment 1 or Experiment 2 |
| **Treatment** | assigned target temperature treatment for each incubator in Celcius |
| **AvgTempC** | average measured temperature for each incubator in Celcius |
| **SDTempC** | standard deviation for each incubator in Celcius |

===========================================================================

**File 2:** _Experiment1&2CombinedBdInfectionData.csv_

CSV of Bd infection data collected from skin swabs for Experiments 1 & 2 collected weekly and filters for Experiment 2 collected on day 7 and 35. Each row is a data collection day for each frog as well as the conditions the frog was experiencing.

| Variable name | Description |
| --- | --- |
| **Experiment** | unique identifier for each experiment as either 2021.IndInf for Experiment 1 and 2022.IndInf for Experiment 2 |
| **Year** | year the experiment was conducted |
| **SampleID** | unique identifier for each swab sample taken from a frog on a particular day (**FrogID_Date**) |
| **FrogID** | unique frog identification number for each experiment |
| **Block** | spatial block for within each experiment |
| **Exp.Block** | spatial block for each experiment (**Year.Block**) |
| **Date** | actual date a swab or filter sample was collected |
| **Day** | day of the experiment relative to the temperature shift |
| **DayOfExpo** | each frog's day of exposure to Bd zoospores relative to the temperature shift |
| **DaysSinceExpo** | number of days since exposure for a frog for a swab or filter sample |
| **AccTemp** | a frog's assigned acclimation temperature |
| **PerfTemp** | a frog's assigned performance temperature |
| **AccInc** | a frog's assigned acclimation incubator |
| **PerfInc** | a frog's assigned performance temperature |
| **LnSwabBd** | 	log(Bd zoospore equivelents) after qPCR assay from frog swabs |
| **LnFilterBd** | 	log(Bd zoospore equivelents) after qPCR assay from frog filters |
| **TotalTime.min** | the total length of time in minutes that a frog was "soaked" in clean water during the zoospore production experiment |
| **TotalVolume.mL** | the total volume of water in mL filtered after a frog "soaked" |
| **Notes** | any notes collected about a given sample |

===========================================================================

**File 3:** _Experiment1&2CombinedMassData.csv_

CSV of mass data for all frogs for Experiments 1 & 2.

| Variable name | Description |
| --- | --- |
| **Experiment** | year the experiment was conducted |
| **FrogCode** | unique identifier for each frog (**FrogID_Block**) |
| **Mass** | mass of each frog at the beginning of each experiment in grams |

===========================================================================
