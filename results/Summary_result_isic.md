# ISIC Results

| Model | Family | Acc (base->ret) | F1 (base->ret) | AUC (base->ret) | ECE (base->ret) | Delta F1 % | Strategy |
| ResNet-50 | CNN | 75.8 -> 75.8 | 75.8 -> 79.7 | 0.94 -> 0.94 | 0.0300 -> 0.0330 | +5.1% | Selective |
| ResNet-101 | CNN | 77.0 -> 77.0 | 76.9 -> 81.4 | 0.94 -> 0.94 | 0.0300 -> 0.0390 | +5.9% | Selective |
| DenseNet-121 | CNN | 76.8 -> 76.8 | 76.8 -> 80.0 | 0.94 -> 0.94 | 0.0100 -> 0.0110 | +4.1% | Selective |
| EffNet-B3 | Efficient | 69.6 -> 69.6 | 69.3 -> 73.7 | 0.90 -> 0.90 | 0.0600 -> 0.0480 | +6.4% | Weighted |
| EffNet-B5 | Efficient | 75.1 -> 75.1 | 75.0 -> 80.9 | 0.93 -> 0.93 | 0.0700 -> 0.0640 | +7.9% | Weighted |
| MobileV3-L | Efficient | 75.5 -> 75.5 | 75.3 -> 78.9 | 0.94 -> 0.94 | 0.0300 -> 0.0300 | +4.8% | Weighted |
| ViT-B/16 | Transformer | 73.6 -> 73.6 | 73.6 -> 74.4 | 0.93 -> 0.93 | 0.0300 -> 0.0300 | +1.1% | Both |
| Swin-T | Transformer | 76.7 -> 76.7 | 76.9 -> 81.3 | 0.95 -> 0.95 | 0.0400 -> 0.0480 | +5.7% | Both |
| ConvNeXt-S | Hybrid | 78.5 -> 78.5 | 78.6 -> 80.9 | 0.94 -> 0.94 | 0.0300 -> 0.0590 | +2.9% | Both |
| MaxViT-T | Hybrid | 79.6 -> 79.6 | 79.5 -> 83.4 | 0.95 -> 0.95 | 0.0400 -> 0.0470 | +4.9% | Both |
