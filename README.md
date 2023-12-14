The repository contains the scripts used to analyze the record of seismic events in West Africa, and estimate the kinenmatic, and ambient stress of their sources.

The scripts are numbered in order of utilization for the purpose indicated in the titles.

00_eq's Download Data is used to download a catalog of earthquake for a specific region, and period of time.
The script also downloads all related waveforms from listed stations.

01_InventoryScanner is used to detect P and S arrivals based on STA/LTA obspy routine.

02_SummaryDataQuality is used to sort the dataset based on the results from the previous step.

03_PolarizationAnalysis_PhaseCorrection... is used to verify the P ans S picks on our HQ and MQ waveforms, and report the correct arrival times.

04_Plot_Data_Distribution... is used to visualize the final selection of waveforms and the overview of the dataset's quality.

05_Single_Station_Inversion is used to invert the waveforms for the focal mechanisms, and report their geometry on a map.

06_Plot_Lithospheric_Stress is used to visualize the stress field.

07_Reguibat_Cluster  is used to visualize the seismicity of mauritania
