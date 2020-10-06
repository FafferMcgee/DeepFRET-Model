This code is associated with the paper from DeepFRET, a software for rapid and
automated single molecule FRET data
classification using deep learning
 et al., "Johannes Thomsen". eLife, 2020. http://doi.org/10.7554/eLife.60404

# DeepFRET-Model
Repository for the model training.

## Original Repo with ongoing development: [here](https://github.com/komodovaran/DeepFRET-Model)

To reproduce publication model:
1. Make sure your environment reflects requirement.txt
2. Run `generate_data.py` and input the number of traces (we used 250k initially, which ends up being ~150k after balancing)
3. Run `train_model.py`. Be sure to set `exclude_alex_fret=False` for the full model.
