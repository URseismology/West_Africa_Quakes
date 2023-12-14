The repository contains the scripts used to analyze the record of seismic events in West Africa and estimate the kinematics, and ambient stress of their sources.

The scripts are numbered in order of utilization according to the purpose indicated in the titles.

00_eq's Download Data is used to download a catalog of earthquakes for a specific region, and period.
The script also downloads all related waveforms from listed stations.

01_InventoryScanner detects P and S arrivals based on the STA/LTA Obspy routine.

02_SummaryDataQuality sorts the dataset based on the results from the previous step.

03_PolarizationAnalysis_PhaseCorrection... verifies the P and S picks on our HQ and MQ waveforms, and reports the correct arrival times.

04_Plot_Data_Distribution... is used to visualize the final waveform selection and the dataset's quality overview.

05_Single_Station_Inversion is used to invert the focal mechanisms' waveforms and report their geometry on a map.

06_Plot_Lithospheric_Stress is used to visualize the stress field.

07_Reguibat_Cluster  is used to visualize the seismicity of Mauritania
