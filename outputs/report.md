# Nuclei Segmentation — DSB2018 Pipeline Report
_Generated: 2026-07-22T05:31:49_

## Test Set Metrics
- Dice: 0.9189
- IoU: 0.8543
- Precision: 0.9376
- Recall: 0.9062
- F1: 0.9189
- Loss: 0.1907

## Cell Morphology Summary
|       |      area |   perimeter |   eccentricity |     solidity |   major_axis_length |   minor_axis_length |   circularity |
|:------|----------:|------------:|---------------:|-------------:|--------------------:|--------------------:|--------------:|
| count |  1691     |   1691      |   1691         | 1691         |          1691       |          1691       |   1691        |
| mean  |   663.707 |     97.0067 |      0.694008  |    0.93361   |            32.9428  |            21.2886  |      0.783709 |
| std   |   835.728 |     68.2907 |      0.156447  |    0.0432116 |            23.514   |            11.1152  |      0.163617 |
| min   |    17     |     14.8284 |      0.0534427 |    0.488363  |             6.94577 |             2.42318 |      0.122077 |
| 25%   |   181     |     50.7487 |      0.60095   |    0.921562  |            18.5818  |            12.3698  |      0.682461 |
| 50%   |   455     |     87.8995 |      0.716491  |    0.943396  |            28.8079  |            20.1445  |      0.753382 |
| 75%   |   777.5   |    121.426  |      0.80705   |    0.958739  |            41.1191  |            25.7938  |      0.935698 |
| max   | 16562     |   1305.71   |      0.995506  |    1         |           481.974   |            92.6213  |      1.16818  |

## Per-Image Summary (head)
| image_id                                                             |   n_cells |   mean_area |   mean_circularity |
|:---------------------------------------------------------------------|----------:|------------:|-------------------:|
| 03f583ec5018739f4abb9b3b4a580ac43bd933c4337ad8877aa18b1dfb59fc9a.png |        19 |   1686.74   |           0.700303 |
| 072ff14c1d3245bf49ad6f1d4c71cdb18f1cb78a8e06fd2f53767e28f727cb81.png |         7 |    154.143  |           0.971617 |
| 0bda515e370294ed94efd36bd53782288acacb040c171df2ed97fd691fc9d8fe.png |        39 |     82.1795 |           0.982235 |
| 136000dc18fa6def2d6c98d4d0b2084d13c22eaffe82e26c665bcaa2a9e51261.png |        25 |    290.16   |           0.771725 |
| 13c8ff1f49886e91c98ce795c93648ad8634c782ff57eb928ce29496b0425057.png |        13 |    212.846  |           0.870157 |
| 14cc1424c59808274e123db51292e9dbb5b037ef3e7c767a8c45c9ac733b91bf.png |        17 |   2104.82   |           0.733151 |
| 150b0ffa318c87b31d78af0e87d60390dbcd84b5f228a8c1fb3225cbe5df3e3f.png |       101 |    792.911  |           0.678522 |
| 1740b0a67ca337ea31648b57c81bcfbb841c7bb5cad185199a9f4da596d531b9.png |         9 |    163.889  |           0.967603 |
| 175dbb364bfefc9537931144861c9b6e08934df3992782c669c6fe4234319dfc.png |       148 |    676.622  |           0.686668 |
| 193ffaa5272d5c421ae02130a64d98ad120ec70e4ed97a72cdcd4801ce93b066.png |        17 |   1831.82   |           0.580409 |

## Artifacts
- `eda_summary.csv`, `eda_plots.png` — exploratory analysis
- `training_history.csv`, `training_curves.png` — training curves
- `unet_dsb2018.pth` — trained model checkpoint
- `cell_feature_stats.csv`, `feature_distributions.png` — cell morphology
- `per_image_summary.csv` — per-image cell counts and averages