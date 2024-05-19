<h1 align="center">GCN Energy</h1>

<h4 align="center">
PBE energy & Bandgap Prediction by GCN models (Train from QMOF Database)                                                                 
</h4>              


[![Requires Python 3.9](https://img.shields.io/badge/Python-3.9-blue.svg?logo=python&logoColor=white)](https://python.org/downloads) [![Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.10822403-blue)](https://doi.org/10.5281/zenodo.10822403)  [![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/sxm13/PACMAN/LICENSE.txt) [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sxmzhaogb@gmail.com) [![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)]() [![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)]()          
                     

# Installation                                                                                                            

**Download**                          

```sh
git clone https://github.com/sxm13/GCNEnergy.git
cd GCNEnergy
pip install -r requirements.txt
```                            
         
# Energy Prediction               
           
```sh
python GCNEnergy.py folder-name[path]
```                          
* folder-name: relative path to a folder with cif files without partial atomic charges                            
          
# Zenodo    
* Full code and dataset can be downloaded from :point_right: [link](https://zenodo.org/records/10822403)
* Note: All future releases will be uploaded on Github.

# Reference
If you use PACMAN charge, please consider citing [this paper]():
```bib
@article{,
    title={PACMAN: A Robust Partial Atomic Charge Predicter for Nanoporous Materials using Crystal Graph Convolution Network},
    DOI={},
    journal={},
    author={Zhao, Guobin and Chung, Yongchul},
    year={2024},
    pages={}
}
```

# Bugs

 If you encounter any problem during using **GCN Energy**, please email ```sxmzhaogb@gmail.com``` or create "issues".
