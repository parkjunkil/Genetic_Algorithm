# Inverse Design of MOFs using a Genetic_Alogirhtm
Data and processing scripts used for the following work:

"Computational Design of Metal-Organic Frameworks with Unprecedented High Hydrogen Working Capacity and High Synthesizability" [Chem. Mater. 2023, 35, 1, 9–16](https://pubs.acs.org/doi/full/10.1021/acs.chemmater.2c01822)  

<br/><br/>

* **data**

  * data folder contains GPU-GCMC data of MOFs generated during the workflow. 
  * 'cycle_n.txt' contains data of structures generated in the nth cycle, and 'cycle_total.txt' contains data of all structures generated throughout the work. 
  * first column represents the name of the structure, and rest of the columns represent the hydrogen adsorption capacity at 1, 2, 5, 10, 20, 30, 35, 40, 50, 60, 70, 80, 90, 100 bar (tempearture was fixed to be 77 K).

    
* **script**

  * script folder contains MOF-NET library, machine learning model used in the work, and a script for data processing and machine learning prediction (ML_prediction.ipynb).
  * MOF-NET is machine learning library desinged for predicting the adsorption capacity of MOFs. [ACS Appl. Mater. Interfaces 2021, 13, 20, 23647–23654](https://doi.org/10.1021/acsami.1c02471)
  * The first part of 'ML_prediction.ipynb'contains the contents of extracting working capacity from the data ('cycle_tot.txt'), and the later part contains the contents of predicting the hydrogen working capacity using machine learning model. 
