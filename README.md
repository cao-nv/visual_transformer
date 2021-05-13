# visual_transformer
Same architecture of ViT trained on CIFAR10 and MNIST in both Pytorch and Tensorflow adapted from [kentaroy47/vision-transformers-cifar10](https://github.com/kentaroy47/vision-transformers-cifar10) and [sneakatyou/ViT-Tensorflow-2.0](https://github.com/sneakatyou/ViT-Tensorflow-2.0). 
# Results: 
## CIFAR10 
Even both implementations were trained with the identical architecture and hyper-parameters, validation accuracy 80.30 of the Pytorch implementation is not consistent with that of Tensorflow couterpart which is 70.15. 
## MNIST
(coming soon)

# Run 
## Dependencies 
* `tensorflow` 
* `tensorflow_addons` (for GELU activation)
* `tensorflow_datasets`(for loading datasets)
* `pytorch`
* `torchvision`
* `einops`
* `wandb`(for logging data with minimal effort)
## Just run it and have
