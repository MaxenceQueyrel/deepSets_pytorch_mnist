# deepSets_pytorch_mnist
### Description
Construct a deepSets model based on this article https://arxiv.org/pdf/1703.06114.pdf to predict the sum of digit and MNIST

### Technology
The implementation is based on python 2.7 and uses pytorch

### Docker
The notebook can be executed with the docker image maxence27/deep_learning:V2
To do this install docker and nvidia-docker and run the following command :
docker run --privileged -v *path_to_the_git*:/deep_sets --runtime=nvidia maxence27/deep_learning:V2

If you don't have nvidia-docker run the following command :
docker run -v *path_to_the_git*:/deep_sets maxence27/deep_learning:V2
