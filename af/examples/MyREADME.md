# Prepare the environment

## Following Google Colab, prepare the necessary dependencies.

Create a conda environment with python 3.10.
```shell
mamba env create -f ref_works/ColabDesign/environment.yml -p ./env
conda activate ./env
```

Install Colab necessary dependencies.
```shell
pip install -r colab-requirements.txt
```

Install jax with suitable dependencies.
```shell
pip install --upgrade "jax[cuda11_pip]" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html 
```

Install ColabDesign
```shell
cd ColabDesign
python setup.py install
```
