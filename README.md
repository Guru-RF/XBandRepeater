# XBandRepeater 

Prepare your sd-card with Raspberry PI OS Lite ! ([Youtube](https://www.youtube.com/watch?v=vxmO_a5WNI8))

Login to your system with ssh add run following commands:

### Install GIT  ###
```console
sudo apt -y install git
```

### Clone repostory ###
```console
git clone https://github.com/Guru-RF/XBandRepeater.git
```

### Audio and Radio module installation script ###
```console
cd XBandRepeater
sudo bash install-radiomodule.sh
```

### SVXLink installation script ###
```console
cd XBandRepeater
sudo bash install-svxlink.sh
```
