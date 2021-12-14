# Parkinson's Disease Datasets

## Overview
Since anatomic MRI is presently not able to directly discern neuronal loss in Parkinson’s Disease (PD), studying the associated functional connectivity (FC) changes seems a promising approach toward developing non-invasive and non-radioactive neuroimaging markers for this disease. While several groups have reported such FC changes in PD, there are also significant discrepancies between studies. Investigating the reproducibility of PD-related FC changes on independent datasets is therefore of crucial importance.

The data are comprised of 27 PD patients and 16 age-matched normal controls in the Neurocon dataset

## Experimental Protocol
For the resting-state scan, subjects were instructed to close their eyes and think of nothing in particular without falling asleep.

## Scan Parameters [(Click here for scan parameters in BIDS format)](http://fcon_1000.projects.nitrc.org/indi/retro/Parkinsons/Parameter_BIDS.csv)


|                       | Parameter     | NEUROCON
| --------------------- |:-------------| :-----|
|                       |               | 1.5-Tesla Siemens Avanto MRI scanner 
| **T1-weighted scan**  | Sequence<br>--------------<br>Repetition time (TR)<br>--------------<br>Echo time (TE)<br>--------------<br>Voxel size | MPRAGE (IR method)<br>--------------<br>1940ms<br>--------------<br>3.08ms<br>--------------<br>0.97 x 0.97 x 1 mm |
| **Resting-state scan**| Sequence<br>--------------<br>Repetition time (TR)<br>--------------<br>Echo time (TE)<br>--------------<br>Voxel size<br>--------------<br>Voxel size<br>--------------<br># of Volumes| Echo planar<br>--------------<br>3480ms<br>--------------<br>50ms<br>--------------<br>	90°<br>--------------<br>3.8 x 3.8 x 5 mm (without slice gaps)<br>--------------<br>137 (8.05 min) | 


### Additional Information
The NEUROCON data was re-hosted from https://fcp-indi.s3.amazonaws.com/data/Projects/INDI/umf_pd/neurocon.tar.gz
z
Find additional dataset information at the following [link](http://fcon_1000.projects.nitrc.org/indi/retro/parkinsons.html).