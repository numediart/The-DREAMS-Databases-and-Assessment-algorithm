# The DREAMS Databases and Assessment algorithm

During the DREAMS project funded by Région Wallonne (Be), we collected a large amount of polysomnographic recordings (PSG) to tune, train and test our automatic detection algorithms.

These recordings were annotated in microevents or in sleep stages by several experts. They were acquired in a sleep laboratory of a belgium hospital using a digital 32-channel polygraph (BrainnetTM System of MEDATEC, Brussels, Belgium). The standard European Data Format (EDF) was used for storing.

In order to facilitate future research and performance comparision, we decided to publish these data on Internet. Therefore, eight DREAMS databases are available according to the annotation carried out (click on the link to open):

* The DREAMS Subjects Database: 20 whole-night PSG recordings coming from healthy subjects, annoted in sleep stages according to both the Rechtschaffen and Kales criteria and the new standard of the American Academy of Sleep Medicine;

* The DREAMS Patients Database: 27 whole-night PSG recordings coming from patients with various pathologies, annoted in sleep stages according to both the Rechtschaffen and Kales criteria and the new standard of the American Academy of Sleep Medicine;

* The DREAMS Artifacts Database: 20 excerpts of 15 minutes of PSG recordings annoted in artifacts (cardiac interference, slow ondulations, muscle artifacts, failing electrode, 50/60Hz main interference, saturations, abrupt transitions, EOG interferences and artifacts in EOG) by an expert;

* The DREAMS Sleep Spindles Database: 8 excerpts of 30 minutes of central EEG channel (extracted from whole-night PSG recordings), annotated independently by two experts in sleep spindles; PLEASE NOTICE THAT EXPERT 1's SCORED SPINDLE COUNTS WERE CUT OFF AFTER 1000 SECONDS. THIS MAKES IT DIFFICULT TO USE COUNTS FOR COMPARISON.

* The DREAMS K-complexes Database: 5 excerpts of 30 minutes of central EEG channel (extracted from whole-night PSG recordings), annotated independently by two experts in K-complexes;

* The DREAMS REMs Database: 9 excerpts of 30 minutes of PSG recordings in which rapid eye movements were annotated by an expert;

* The DREAMS PLMs Database: 10 whole-night PSG recordings coming from patients in which one of the two tibialis EMG was annoted in periodic limb movements by an expert;

* The DREAMS Apnea Database: 12 whole-night PSG recordings coming from patients annoted in respiratory events (central, obstructive and mixed apnea and hypopnea) by an expert.

We also developped and tested several automatic procedures to detect micro-events such as sleep spindles, K-complexes, REMS, etc. and provide the source codes for them in the DREAMS Assessment Algorithm package.

To access the data, follow this link:
https://zenodo.org/record/2650142

 
