# Dual-scale Doppler Attention for Human Identification.
Pytorch code for the 2022 Sensor Journal paper DSDA: Dual-scale Doppler Attention for Human Identification.

Paper can be found at:



## Data Set

Data set can be downloaded from: https://www.imec-int.com/en/IDRad

```
python scripts/process_all.py --input \<root path\>
```

## Train model

```
python train.py
```

## Test model

```
python eval.py
```

## Acknowldegement
This work was partly supported by Institute for Information & communications Technology Promotion(IITP) grant funded by the Korea government(MSIT) (No. 2021-0-01381, Development of Causal AI through Video Understanding) and partly supported by Institute of Information & communications Technology Planning & Evaluation (IITP) grant funded by the Korea government(MSIT) (No. 2022-0-00951, Development of Uncertainty-Aware Agents Learning by Asking Questions)

This software is based on top of following conributions:
[IDRad](https://www.imec-int.com/en/IDRad)
We thank the authors for open-sourcing these great projects and papers!

## Citation
If you find this code useful for your research, please cite our paper:
