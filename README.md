# lt4hala2024
Relevant data and code to reproduce the findings in ["Automatic Normalisation of Middle French and its Impact on Productivity"](https://aclanthology.org/2024.lt4hala-1.20/).

# Datasets
All datasets are in the data folder.

## Hand-crafted corpus
The manually normalized corpus is `rc_manual_normalisation_lt4hala.src` and `rc_manual_normalisation_lt4hala.tgt`, for the source and target respectively. The source corpus is non-normalized, while the target corpus was manually normalized by experts. The normalization process is detailed in the paper but could be summarized as an orthographic and grammatical normalization with syntactic structures remaining untouched.

## Synthetic corpus
Due to its size, the synthetic corpus is hosted here:
[source](https://drive.switch.ch/index.php/s/ptuSN7V96aBzqAn)
[target](https://drive.switch.ch/index.php/s/Q1vOQN8qwj8Oi9H)

# References
Please cite the following paper if you use the datasets or models.
```
@inproceedings{rubino-etal-2024-automatic,
    title={{Automatic Normalisation of Middle French and Its Impact on Productivity}},
    author={Rubino, Raphael and Coram-Mekkey, Sandra and Gerlach, Johanna and Mutal, Jonathan David and Bouillon, Pierrette},
    booktitle={Proceedings of the Third Workshop on Language Technologies for Historical and Ancient Languages (LT4HALA) @ LREC-COLING-2024},
    year={2024},
    url={https://aclanthology.org/2024.lt4hala-1.20},
    pages={176--189}
}
```
