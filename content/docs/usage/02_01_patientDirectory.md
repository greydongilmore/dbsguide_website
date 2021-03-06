+++
title =  "Patient Directory"
description = ""
weight = 4
+++

<p align="center"><img src="../img/widget01.png" alt="widget01" width="30%"/></p>

Once you've loaded DBS Guide into Slicer (see :ref:`Installation`), you can begin using DBS Guide. The first step is to load the patient's brain scans as a directory or file (hence, the name Patient Directory). DBS Guide will take the directory that you load and make two new folders in your directory called `scene` and `source`. `source` will contain the original brain files/scans, while `scene` will contain all the new coregistered scans, settings and information.

We will load a sample directory called `Sub-P057` in this tutorial. 


1. **Load the patient's directory.** An example directory is shown below. Notice, we only select the patient directory/folder and not the files inside the folder. This directory contains folders in the ``.nii.gz`` format which means each folder is a gzipped folder of *NIFTI (Neuroinformatics Technology Initiative)* files. NIFTI files are files of MRI scans.

<p align="center"><img src="../img/exDirectory.png" alt="exDirectory" width="50%"/></p>
   

2. Select the options: <br>

	**Implanted Sides** Is the surgery unilateral or bilateral? Select left and right sides of the brain accordingly.<br>
	**Rename Scans?** This option is strongly recommended. In the `source` folder that DBS Guide  creates, the new scans will have a different file extension will make a new folder in your directory with the coregistered scans once you've loaded them.<br>
	**Use Previously Stored Values?** This option is recommended. If the patient directory had already been used in DBS Guide, you can load the directory and the module will pick up right where you left off. 

	Once you click `Load Data`, the following screen will appear:

	<p align="center"><img src="../img/screenPostLoad.png" alt="screenPostLoad" width="50%"/></p>

3. Select the right info:<br>

	Date<br>
	Patient Name/ID<br>
	Surgeon<br>

	<p align="center"><img src="../img/widget02.png" alt="widget02" width="30%"/></p>


	There are two folders now in your patient directory:

	**Scene** (contains data/scans that will be edited)
	
	**source** (contains original brain scans. This folder won't be modified so that you don't lose the original scans)

	<p align="center"><img src="../img/DirectoryPostLoad.png" alt="DirectoryPostLoad" width="50%"/></p>


4. Patient Directory Loaded Successfully

