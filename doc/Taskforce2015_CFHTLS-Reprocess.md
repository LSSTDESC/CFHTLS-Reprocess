# DESC Taskforce 2015 Proposal: CFHTLS Data Reprocessing

| Title|CFHTLS Data Reprocessing|
|----------|-------------------------|
| Primary Lead(s)                       | Boutigny |                                  |---------------------------------------|--------------------------------------------------------------|
| Interested DESC Members               | Dell'antonio, Marshall, Schneider ...|
| DESC Working Groups                   | SL, WL, CL                                              |---------------------------------------|--------------------------------------------------------------|
| Start Date (approximate)              | September 2015                                                     |---------------------------------------|--------------------------------------------------------------|
| End Date (approximate)                | December 2016                                                     |---------------------------------------|-----------------------------------------------------------|
| Working Deliverable Publication Title | Reprocessing of at least 1 Deep and 1 Wide field : Coadd + forced photometry ; Some DLS data reprocessed (to be precised) |
| Intermediate Milestones               |DLS instrument package available in LSST DM stack  |--------------------------------|--------------------------------------------------------------|


### Brief Project Summary

We are proposing to reprocess the CFHTLS dataset using the LSST DM stack with the following goals :

1. provide a good quality real dataset to test existing and develop new science algorithms / pipelines
2. set up a strong link between DESC and the LSST DM team in order to provide feedback on the DM developments
3. gain expertize on the DM framework
4. understand how to develop future level-3 code in the DM framework
5. wherever possible, re-analyze CFHTLS data and publish improved results  

CFHTLS data is a well known dataset and several science en technical papers have been published, providing references to challenge the DESC / LSST pipelines. Using the CFHTLS deep fields and the overlapping HST ones, it is for instance possible to test various deblending technics. +

Several physicists at IN2P3 and members of the DESC have a deep knowledge of the CFHTLS data through the SuperNovae Legacy Survey (SNLS) project. 

Within the LSST DM stack, the package specific to the CFHT / Megacam instrument (obs_cfht) has been developped during the past year and is now at a level suitable for the proposed task force.

Finally the work on CFHTLS can be extended to other precursor datasets. The Hyper Suprime Cam (HSC) instrument is already supported in the LSST DM Stack and several DESC members have expressed interest for a reprocessing of the Deep Lens Survey (DLS) dataset. Tony Tyson has confirmed that access to the DLS pre-processed images (after instrument signature removal) is possible. 

### Why is this project a priority?

The future DESC Data Challenges (particularly DC3) may involve analysis of real data (DECam)rather than just simulated data. This taskforce will be an important precursor activity for this central DESC task.

Maintaining a good coordination between DESC and LSST DM is crucial in order to get the adequate algorithms, pipelines and interfaces which will be the basis to develop optimized level-3 software.

Work on real datasets is complementing the developments on the simulation and provides validation. With this respect, there is a link between the present taskforce and the Twinkles one.


### Computing Resource Requirements

All the CFHTLS datasets (D1-D4 and W1-W4) are available at the IN2P3 Computing Center and computing resources are available there and open to LSST / DESC members upon request. 

It is also possible to transfer part of, or all the data on a computing center (to be identified) in the US and to perform part of the reprocessing there.

The ouput calatogs and images will be made available either through network access or with a direct copy in a place to be specified.

A detailed estimation of the resources needed to reprocess the full data sets is still to be made but based on previous tests, processing 360 D3 field images (r filter) require ~10 TB of disk space, or ~50 TB for 5 filters. The output catalogs are order of magnitudes smaller (to be precisely estimated). 
