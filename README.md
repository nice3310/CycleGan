# Modified PyTorch-CycleGAN

This project is based on the [PyTorch-CycleGAN](https://github.com/aitorzip/PyTorch-CycleGAN) repository.

## Modifications

The changes include:

1. **Training**:
   - Added the ability to specify the save path.
   - Designated checkpoint folders and more.
    
2. **Testing**:
   - Allows generating images with the original source dimensions.****
   - Enables specifying the checkpoint folder to locate models for predictions.

## Usage Examples

**train**
```
python train.py --dataroot /path/to/dataset --save_dir /path/to/save/models --checkpoint_dir checkpoints/horse2zebra --batchSize size --cuda
```

**test**
```
python test.py --dataroot /path/to/dataset --batchSize size --checkpoint_dir checkpoints/horse2zebra --save_dir results/
```

All credits go to the original author @aitorzip

I made this minor modifications just to better suit my own use.
