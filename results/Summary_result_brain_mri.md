# Brain MRI Results

Model,Family,Acc (base->ret),F1 (base->ret),AUC (base->ret),ECE (base->ret),Delta F1 %,Strategy
ResNet-50,CNN,94.5 -> 94.5,94.4 -> 94.2,0.99 -> 0.99,0.0300 -> 0.0410,-0.2%,Selective
ResNet-101,CNN,94.1 -> 94.1,94.0 -> 95.8,0.99 -> 0.99,0.0300 -> 0.0310,+1.9%,Selective
DenseNet-121,CNN,94.3 -> 94.3,94.2 -> 94.8,0.99 -> 0.99,0.0200 -> 0.0220,+0.6%,Selective
EffNet-B3,Efficient,90.9 -> 90.9,90.8 -> 91.8,0.98 -> 0.98,0.0500 -> 0.0490,+1.1%,Weighted
EffNet-B5,Efficient,95.2 -> 95.2,95.1 -> 95.6,0.99 -> 0.99,0.0300 -> 0.0290,+0.5%,Weighted
MobileV3-L,Efficient,93.6 -> 93.6,93.6 -> 94.2,0.99 -> 0.99,0.0300 -> 0.0270,+0.6%,Weighted
ViT-B/16,Transformer,94.5 -> 94.5,94.4 -> 94.3,0.98 -> 0.98,0.0300 -> 0.0390,-0.1%,Both
Swin-T,Transformer,95.2 -> 95.2,95.1 -> 94.1,0.99 -> 0.99,0.0400 -> 0.0430,-1.1%,Both
ConvNeXt-S,Hybrid,95.7 -> 95.7,95.7 -> 95.2,0.99 -> 0.99,0.0400 -> 0.0440,-0.5%,Both
MaxViT-T,Hybrid,94.4 -> 94.4,94.4 -> 95.3,0.99 -> 0.99,0.0300 -> 0.0360,+0.9%,Both