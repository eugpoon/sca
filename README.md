# Survival Cluster Analysis (Reproduction)

This repository contains a reproduction of the method described in the paper:  
> **"Unsupervised Learning of Clusters with Survival Outcomes"**  
> [Arxiv 2020](https://arxiv.org/pdf/2003.00355)  
> Original GitHub: [paidamoyo/survival_cluster_analysis](https://github.com/paidamoyo/survival_cluster_analysis)

---

## Environment Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/eugpoon/sca.git
   cd sca
   ```

2. **Create the conda environment**
   ```bash
   conda env create --name sca --file=environment.yml
   ```

3. **Activate the environment**
   ```bash
   conda activate sca
   ```

---

## Running the Code

Run the provided Jupyter Notebook to train and evaluate the model:

```bash
jupyter notebook
```

Run sca.ipynb