# BUSI Results

Model,Family,Acc (base->ret),F1 (base->ret),AUC (base->ret),ECE (base->ret),Delta F1 %,Strategy
ResNet-50,CNN,72.6 -> 72.6,72.5 -> 74.2,0.92 -> 0.92,0.1300 -> 0.0710,+1.7%,Selective
ResNet-101,CNN,72.6 -> 72.6,72.0 -> 72.0,0.93 -> 0.93,0.1000 -> 0.1000,+0.0%,Selective
DenseNet-121,CNN,83.8 -> 83.8,82.6 -> 82.9,0.96 -> 0.96,0.1100 -> 0.0880,+0.4%,Selective
EffNet-B3,Efficient,61.5 -> 61.5,60.9 -> 59.3,0.82 -> 0.82,0.2500 -> 0.2480,-2.6%,Weighted
EffNet-B5,Efficient,80.3 -> 80.3,79.0 -> 82.0,0.96 -> 0.96,0.1400 -> 0.1280,+3.8%,Weighted
MobileV3-L,Efficient,58.1 -> 58.1,58.9 -> 60.4,0.89 -> 0.89,0.1200 -> 0.0970,+2.5%,Weighted
ViT-B/16,Transformer,57.3 -> 57.3,51.5 -> 55.7,0.78 -> 0.78,0.1700 -> 0.0780,+8.1%,Both
Swin-T,Transformer,85.5 -> 85.5,84.6 -> 90.1,0.97 -> 0.97,0.1000 -> 0.0470,+6.5%,Both
ConvNeXt-S,Hybrid,73.5 -> 73.5,73.0 -> 77.8,0.91 -> 0.91,0.1900 -> 0.1040,+6.6%,Both
MaxViT-T,Hybrid,82.1 -> 82.1,81.0 -> 82.8,0.95 -> 0.95,0.0500 -> 0.0630,+2.2%,Both