# basic_setup
Some personal basic setup on computing environment.

Install SSH for remote control.
```
sudo apt-get install openssh-server
```

Download and install [CUDA 8.0](https://developer.nvidia.com/cuda-downloads).
```
wget https://developer.nvidia.com/compute/cuda/8.0/Prod2/local_installers/cuda_8.0.61_375.26_linux-run && sudo chmod -x cuda_8.0.61_375.26_linux-run && mv cuda_8.0.61_375.26_linux-run cuda_8.0.61_375.26_linux.run && sudo sh cuda_8.0.61_375.26_linux.run
```

Download and install [Anaconda3](https://www.anaconda.com/download/).
```
wget https://repo.continuum.io/archive/Anaconda3-4.4.0-Linux-x86_64.sh && bash Anaconda3-4.4.0-Linux-x86_64.sh
```

Personal preferance.
```
git config --global push.default "current" && git config --global pull.default "current" && git config --global credential.helper "cache --timeout=36000000000000000"
```
