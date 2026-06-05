# COVID Results

Model,Family,Acc (base->ret),F1 (base->ret),AUC (base->ret),ECE (base->ret),Delta F1 %,Strategy
ResNet-50,CNN,92.6 -> 92.6,93.2 -> 94.2,0.99 -> 0.99,0.0300 -> 0.0230,+1.1%,Selective
ResNet-101,CNN,93.1 -> 93.1,93.8 -> 93.1,0.99 -> 0.99,0.0300 -> 0.0290,-0.7%,Selective
DenseNet-121,CNN,92.2 -> 92.2,92.9 -> 93.9,0.99 -> 0.99,0.0300 -> 0.0240,+1.1%,Selective
EffNet-B3,Efficient,89.7 -> 89.7,90.7 -> 91.7,0.99 -> 0.99,0.0400 -> 0.0430,+1.1%,Weighted
EffNet-B5,Efficient,93.1 -> 93.1,93.8 -> 94.9,0.99 -> 0.99,0.0300 -> 0.0280,+1.2%,Weighted
MobileV3-L,Efficient,91.1 -> 91.1,92.2 -> 92.5,0.99 -> 0.99,0.0300 -> 0.0230,+0.3%,Weighted
ViT-B/16,Transformer,91.9 -> 91.9,92.9 -> 94.1,0.99 -> 0.99,0.0400 -> 0.0340,+1.3%,Both
Swin-T,Transformer,92.6 -> 92.6,93.5 -> 94.6,0.99 -> 0.99,0.0400 -> 0.0320,+1.2%,Both
ConvNeXt-S,Hybrid,92.9 -> 92.9,93.7 -> 94.8,0.99 -> 0.99,0.0300 -> 0.0290,+1.2%,Both
MaxViT-T,Hybrid,93.7 -> 93.7,94.3 -> 94.9,0.99 -> 0.99,0.0200 -> 0.0210,+0.6%,Both