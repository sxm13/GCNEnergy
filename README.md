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

# Models Performance                                    
<img src="./figs/result.png" alt="result" width="500">   


# Reference
If you use GCN Energy, please consider citing [this paper](https://pubs.acs.org/doi/10.1021/acs.jctc.4c00434):                                           
```bib
@article{,
    title={PACMAN: A Robust Partial Atomic Charge Predicter for Nanoporous Materials based on Crystal Graph Convolution Network},
    DOI={10.1021/acs.jctc.4c00434},
    journal={Journal of Chemical Theory and Computation},
    author={Zhao, Guobin and Chung, Yongchul},
    year={2024}
}
```
