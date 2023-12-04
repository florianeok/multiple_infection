# Increased virulence due to multiple infection in *Daphnia* leads to limited growth in one of two co-infecting microsporidian parasites

**multiple_infection_data.csv** contains all data collected during this experiment. For an overview of the experimental procedures see the associated manuscript <https://doi.org/10.1017/S0031182023001130>

## Description of the data structure

**ID** - unique identification code for each animal in the experiment

**T1 and T2** - exposures at each of the two timepoints (T1 = day 0 and T2 = day 5). Animals were either exposed to *Ordospora colligata* spores, *Hamiltosporidium tvaerminnensis* spores or a placebo dose (OC, HT and N respectively in the datafile).

**rep** - replicate number.

**start_date** - start date of the experiment, identical for all data points.

**death_date** - date of death of each animal.

**days_to_death** - number of days the animal was alive.

**OC_inf** - whether the animal was infected with Ordospora colligata, coded as a binary variable where 0 = no and 1 = yes. Cells were left empty where infection with OC was not applicable.

**OC_spores** - number of OC spore clusters observed in OC infected samples.

**HT_inf** - whether the animal was infected with Hamiltosporidium tvaerminnensis, coded as a binary variable where 0 = no and 1 = yes. Cells were left empty where infection with HT was not applicable.

**HT_spores** - number of HT spores observed in HT infection samples.

**total_offpsring** - total number of offspring produced by each animal over the course of the experiment.
