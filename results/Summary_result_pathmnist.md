# PathMNIST Results

Model,Family,Acc (base->ret),F1 (base->ret),AUC (base->ret),ECE (base->ret),Delta F1 %,Strategy
ResNet-50,CNN,97.9 -> 97.9,97.9 -> 98.0,1.00 -> 1.00,0.0000 -> 0.0010,+0.1%,Selective
ResNet-101,CNN,98.1 -> 98.1,98.1 -> 98.4,1.00 -> 1.00,0.0000 -> 0.0000,+0.3%,Selective
DenseNet-121,CNN,98.0 -> 98.0,98.0 -> 98.1,1.00 -> 1.00,0.0000 -> 0.0000,+0.1%,Selective
EffNet-B3,Efficient,96.0 -> 96.0,96.0 -> 97.1,1.00 -> 1.00,0.0100 -> 0.0080,+1.1%,Weighted
EffNet-B5,Efficient,98.2 -> 98.2,98.2 -> 98.6,1.00 -> 1.00,0.0000 -> 0.0000,+0.4%,Weighted
MobileV3-L,Efficient,97.0 -> 97.0,97.0 -> 97.8,1.00 -> 1.00,0.0000 -> 0.0000,+0.8%,Weighted
ViT-B/16,Transformer,98.7 -> 98.7,98.7 -> 98.7,1.00 -> 1.00,0.0000 -> 0.0000,+0.0%,Both
Swin-T,Transformer,98.7 -> 98.7,98.7 -> 98.8,1.00 -> 1.00,0.0000 -> 0.0000,+0.1%,Both
ConvNeXt-S,Hybrid,98.2 -> 98.2,98.2 -> 98.3,1.00 -> 1.00,0.0100 -> 0.0110,+0.1%,Both
MaxViT-T,Hybrid,98.6 -> 98.6,98.6 -> 98.8,1.00 -> 1.00,0.0000 -> 0.0000,+0.2%,Both