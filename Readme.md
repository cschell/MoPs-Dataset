# Motion Password Dataset

This repository contains the dataset collected for the study described in the paper "Motion Passwords" by Rack et al., accepted at VRST 2024. The dataset includes motion capture data from a study with 48 participants who performed over 3800 Motion Passwords across two sessions in a virtual reality environment.

## Data Collection Study

Participants in the study were asked to spell out a chosen word in the air using a VR controller, providing data for biometric authentication research. Detailed information on the study and dataset usage can be found in the [paper repository](https://github.com/cschell/MoPs).

## Data Access

The data is managed using DVC (Data Version Control). To pull the dataset, first install DVC:

```bash
pip install dvc
```

Then, pull the dataset using:

```bash
dvc pull  --jobs 5
```

## Citation

If you use this dataset, please cite the following paper:

```bibtex
@conference{rack2024motion,
  title        = {Motion Passwords},
  author       = {Rack, Christian and Schach, Lukas and Achter, Felix and Shehada, Yousof and Lin, Jinghuai and Latoschik, Marc Erich},
  booktitle    = {Proceedings of the 30th ACM Symposium on Virtual Reality Software and Technology},
  year         = {2024},
  series       = {VRST '24},
  address      = {New York, NY, USA},
  publisher    = {Association for Computing Machinery},
  note         = {accepted},
  doi          = {10.1145/3641825.3687711}
}
```

For more details, refer to the [main paper repository](https://github.com/cschell/MoPs).
