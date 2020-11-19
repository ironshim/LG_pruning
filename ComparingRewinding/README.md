# [Comparing Rewinding and Fine-tuning in Neural Network Pruning](https://arxiv.org/abs/2003.02389)

modified from https://github.com/jack-willturner/DeepCompression-PyTorch

to create the pretrained model, run: 

```bash
python train.py --model='resnet34' --checkpoint='resnet34'
python prune.py --model='resnet34' --checkpoint='resnet34'
```

