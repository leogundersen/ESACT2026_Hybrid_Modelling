First, run the following lines in PowerShell:
  First, to clone this repository:
git clone https://github.com/leogundersen/ESACT2026_Hybrid_Modelling.git
cd ESACT2026_Hybrid_Modelling

  Second to launch notebook with compilation capacity:
"C:\Program Files\Microsoft Visual Studio\18\Community\VC\Auxiliary\Build\vcvars64.bat"

  (Third: launch notebook using "jupyter notebook" / "code")
  
This repository contains the materials and resources provided during the workshop. 
    "Code" section contains the Python files for the Data generation code and the Hybrid model.
    "Data" section contains datasets for all mAbs evaluated, separated into low or high titer mAbs.
    "Excel" section contains the files necessary to generate data without recalculating vmaxmab/coefficients (Generate_new_data = False). It also stores these files when generated
    "Results" section serves as a repository for previously trained models, useful for run_training = False
