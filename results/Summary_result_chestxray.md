# ChestXray Results

| Model | Family | Acc (base->ret) | F1 (base->ret) | AUC (base->ret) | ECE (base->ret) | Delta F1 % | Strategy |
| ResNet-50 | CNN | 55.9 -> 55.9 | 50.6 -> 50.8 | 0.83 -> 0.83 | 0.2500 -> 0.2320 | +0.4% | Selective |
| ResNet-101 | CNN | 55.2 -> 55.2 | 0.503 -> 52.2 | 0.85 -> 0.85 | 0.2400 -> 0.1940 | +3.8% | Selective |
| DenseNet-121 | CNN | 57.4 -> 57.4 | 52.7 -> 55.5 | 0.86 -> 0.86 | 0.1800 -> 0.1710 | +5.3% | Selective |
| EffNet-B3 | Efficient | 52.4 -> 52.4 | 48.3 -> 49.2 | 0.81 -> 0.81 | 0.3000 -> 0.2960 | +1.9% | Weighted |
| EffNet-B5 | Efficient | 55.2 -> 55.2 | 51.6 -> 52.4 | 0.85 -> 0.85 | 0.2300 -> 0.2310 | +1.6% | Weighted |
| MobileV3-L | Efficient | 56.9 -> 56.9 | 51.4 -> 53.0 | 0.86 -> 0.86 | 0.2400 -> 0.1810 | +3.2% | Weighted |
| ViT-B/16 | Transformer | 60.3 -> 60.3 | 55.8 -> 57.1 | 0.88 -> 0.88 | 0.1300 -> 0.1070 | +2.4% | Both |
| Swin-T | Transformer | 55.2 -> 55.2 | 51.2 -> 52.8 | 0.89 -> 0.89 | 0.1600 -> 0.1460 | +3.1% | Both |
| ConvNeXt-S | Hybrid | 56.8 -> 56.8 | 53.1 -> 57.9 | 0.86 -> 0.86 | 0.1800 -> 0.1640 | +9.0% | Both |
| MaxViT-T | Hybrid | 57.7 -> 57.7 | 54.4 -> 53.7 | 0.87 -> 0.87 | 0.2000 -> 0.1980 | -1.3% | Both |
