# SolarDis
This repository contains the code used in the paper "**Distance and stellar parameters estimations of solar-like stars from LAMOST spectroscopic 
survey**" by **Yue-Yue Shen and A-Li Luo**.

## Data
### Final Catalog
The final catalog of the paper is available [here](https://nadc.china-vo.org/res/r101400/). 
The columns are described in **Table D.1** in the paper.

### Training Set and the Model
The training set and the trained model are available via Zenodo at doi: [10.5281/zenodo.13748129](https://zenodo.org/doi/10.5281/zenodo.13748129).

## Code
- `1_preprocess.ipynb`: Preprocess of the spectra, you can skip this step if you use the training set provided.
- `2_cnn_model.ipynb`: Model prediction and performance evaluation. Including the codes for **Figure 5, Figure 6** and **Figure 7** in the paper.

## Contact
If you have any questions, please contact me! 📬 shenyy@nao.cas.cn

Collaborations are welcome! 🤝