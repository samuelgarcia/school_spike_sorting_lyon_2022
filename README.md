# Data analysis spike sorting - Day 3



Here is the schedulde for day 3 for the data analysis school in Lyon, October 2021
https://www.gdr-neuralnet.cnrs.fr/fr/node/63


## Instalation and download

Packages to be installed **before the school** (included in the provided environment file):
 * numpy/scipy/sklearn/matplotlib/
 * spikeinterface[full]
 * MEArec
 * jupyter
 * tridesclous
 * spykingcircus
 * herdingspikes
 * montainsort

Datasets to be downloaded **before the school**:
 * "cambridge_data.dat" for practice 2
 * "templates_Neuronexus-32_100.h5" for practice 3


# Schedule


Overview 
Pause 11.00 - 11.15
Spikeinterface slides 11.15 - 11.45
Notebook spikeinterface 11.45 - 13.00

Lunch 13.00 - 14.00

Demo (avec sigui mais pas phy) 14.00 - 14.15
Handson pré-maché 14.15 - 15.45
Pause 15.45 - 16.00
Draft handson comparison / probe design / your data 16.00 - 17.30




### Morning: 9:30 - 12:45
### Afternoon: 14:00 - 18:00

## Morning 9:30 - 12:45


* Overview on spike sorting -- Pierre Yger (1h30min) - 9.30 - 11.00

* Pause 11.00 - 11.15

* Overview on spikeinterface + probeinterface -- Samuel Garcia (30min) - 11.15 - 11.45

* Demo - SpikeInterface (+ ProbeInterface) -- Samuel Garcia (1h15min) - 11.45 - 13.00


## Afternoon 14:00 - 17:47

* Demo - Spikeinterface-gui -- Samuel Garcia (20 min) - 14.00 - 14.20


### Practice (3.5 hours)


Make sure to do at least Practice 1 then you have choice between 2, 3 or 4


### Practice 1 : SpikeInterface pipeline on a real dataset (1h to 1h30)

The goal of this practice session is to explore the SpikeInterface functionalities on a real datast.
It will include:
* reading data
* loading probes
* preprocessing
* spike sorting
* postprocessing
* exploration of results
* automatic curation
* export functions


#### Practice 2 : make your own probe with ProbeInterface (30 min)

The goal of this practice is to get familiar with ProbeInterface and to learn how to build a probe model from
design documents and datasheets of probes and connectors.


### Practice 3 : spike sorting benchmark (50min)

In this practice you will use simulated recording with ground-truth to benchmark the performance of different algorithms.

### Practice 4 : use SpikeInterface on your own data (50min)

In this last part, you can try to apply what you learnt on your on data!

