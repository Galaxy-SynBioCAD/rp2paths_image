# rp2paths docker 

* Docker image: [ibisba/rp2paths](https://hub.docker.com/r/ibisba/rp2paths/)
* Base images: [conda/miniconda3](https://hub.docker.com/r/conda/miniconda3/dockerfile)

Docker implementation of rp2paths

### Quick start

### Local docker

##### Build the docker

```
docker build -t brsynth/rp2paths-standalone:dev .
```

To test run the following command:

```
python run.py -rp_results test/rp_pathways.csv -out_paths test/out_paths.csv -out_compounds test/out_compounds.csv -timeout 30
```

### How to cite rp2paths?
Please cite:

Delépine B, Duigou T, Carbonell P, Faulon JL. RetroPath2.0: A retrosynthesis workflow for metabolic engineers. Metabolic Engineering, 45: 158-170, 2018. DOI: https://doi.org/10.1016/j.ymben.2017.12.002
