# reward_memories_rsa

This repository contains the code required to re-create the data visualizations and analyses reported in the moterRSA manuscript. All code is written in R.

R Core Team (2019). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URL https://www.R-project.org/.

## Script
<b>RSAmanuscriptdraft0125.Rmd</b>: reproduces the data visualizations and analyses; creates the .html file.

## Data
Data for <i>N</i> = 89 children, adolescent, and adult participants are stored in the <b><i>data</i></b> directory across multiple .csv files:
* <b>MotERdemog.csv</b> contains participants' demographic information.
* <b>MotERBehavdata_remembered.csv</b> contains participants' behavioral data.
* <b>RSAdata_VTC.csv</b> contains participants' neural VTC data.
* <b>RSAdfQAVTC.csv</b> contains QA on participants' neural VTC data.
* <b>RSAdata_antHIPP.csv</b> contains participants' neural anterior hippocampus data.
* <b>RSAdfQAantHIPP.csv</b> contains QA on participants' neural anterior hippocampus data.
* <b>trialwiseERS_VTC_wmemoryday2.csv</b> contains participants' trial-wise neural VTC data (for brain-behavior relations).
* <b>encodingactivation.csv</b> contains participants' neural data (for brain-brain relations).

## Figures
The data visualizations are outputted by <b>RSAmanuscriptdraft0125.Rmd</b> and are stored in the <b><i>figures</i></b> directory.

## Contact
This study is led by Alexandra Cohen (ali.cohen@emory.edu) and was conducted in the [Hartley Lab at New York University](https://www.hartleylab.org/).
