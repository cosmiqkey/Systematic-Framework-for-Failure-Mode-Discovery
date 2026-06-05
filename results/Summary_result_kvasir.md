# Kvasir Results

Model,Family,Acc (base->ret),F1 (base->ret),AUC (base->ret),ECE (base->ret),Delta F1 %,Strategy
ResNet-50,CNN,90.9 -> 90.9,90.9 -> 91.1,0.99 -> 0.99,0.0300 -> 0.0470,+0.2%,Selective
ResNet-101,CNN,91.7 -> 91.7,91.6 -> 91.4,0.99 -> 0.99,0.0500 -> 0.0590,-0.2%,Selective
DenseNet-121,CNN,92.0 -> 92.0,92.0 -> 91.2,0.99 -> 0.99,0.0400 -> 0.0510,-0.9%,Selective
EffNet-B3,Efficient,89.0 -> 89.0,89.0 -> 90.3,0.99 -> 0.99,0.0600 -> 0.0590,+1.5%,Weighted
EffNet-B5,Efficient,93.3 -> 93.3,93.3 -> 91.6,1.00 -> 1.00,0.0400 -> 0.0600,-1.8%,Weighted
MobileV3-L,Efficient,91.1 -> 91.1,91.1 -> 91.2,0.99 -> 0.99,0.0400 -> 0.0480,+0.1%,Weighted
ViT-B/16,Transformer,91.5 -> 91.5,91.5 -> 91.8,0.99 -> 0.99,0.0500 -> 0.0520,+0.3%,Both
Swin-T,Transformer,92.4 -> 92.4,92.4 -> 93.2,1.00 -> 1.00,0.0400 -> 0.0430,+0.9%,Both
ConvNeXt-S,Hybrid,92.9 -> 92.9,92.9 -> 92.2,0.99 -> 0.99,0.0500 -> 0.0560,-0.8%,Both
MaxViT-T,Hybrid,93.9 -> 93.9,93.9 -> 93.5,1.00 -> 1.00,0.0300 -> 0.0480,-0.4%,Both