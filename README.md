[![DOI](https://zenodo.org/badge/512889975.svg)](https://zenodo.org/badge/latestdoi/512889975)

# nbgc (name-based gender classification)

This repository hosts code to replicate and explore the analysis and results in the paper "An Open-Source Cultural Consensus Approach to Name-Based Gender Classification" [(arXiv)](https://arxiv.org/abs/2208.01714). Data supporting this work can be found [here](https://osf.io/tz38q/) and an associated python package to make name-based gender classifications in practice [here](https://github.com/ianvanbuskirk/nomquamgender).

---

## Replication

The notebook ***reproduce_analysis.ipynb*** reproduces the results and figures in the paper. Earlier stages of analysis are captured in the notebooks ***construct_data_resources.ipynb*** and ***aggregate_name_data.ipynb***. One way to go about replication is as follows, beginning in terminal:

1. % git clone <https://github.com/ianvanbuskirk/nbgc.git>
2. % cd nbgc
3. % python3 -m venv .venv
4. % source .venv/bin/activate
5. % pip install -r requirements.txt
6. % python -m ipykernel install --user --name=nbgc
7. % jupyter notebook

The above clones this repository, creates a virtual environment and installs required packages, adds this environment as a jupyter notebook kernel and starts the notebook server. Next, navigate to and open ***reproduce_analysis.ipynb***, ensure that the nbgc kernel is active, and run all cells.

---
To cite this work, please use this bibtex entry:
```
@article{van2022open,
  title={An Open-Source Cultural Consensus Approach to Name-Based Gender Classification},
  author={Van Buskirk, Ian and Clauset, Aaron and Larremore, Daniel B},
  journal={arXiv preprint arXiv:2208.01714},
  note = {\url{https://github.com/ianvanbuskirk/nbgc}},
  year={2022}
}
```
