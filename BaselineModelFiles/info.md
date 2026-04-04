Report and PTH file for ResNet18 basline model.
CFG = {
    'seed': 42,
    'model_name': 'resnet18', # Change this to 'efficientnet_b0' later
    'save_path' : '/kaggle/working/',
    'model_title': 'resnet18_baseline.pth',
    'img_size': 224,          # EfficientNet-B0 also uses 224x224
    'batch_size': 8,
    'epochs': 8,
    'lr': 1e-4,
    'weight_decay': 1e-5,
    'num_classes': 3,
    'num_workers': 0
}
