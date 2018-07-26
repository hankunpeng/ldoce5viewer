# LDOCE5 Viewer forked from ciscorn/ldoce5viewer

![image](https://cloud.githubusercontent.com/assets/15828926/24585732/efb068a4-17bb-11e7-8294-7241f73d9ed8.png)

The LDOCE5 Viewer is an alternative dictionary viewer for the Longman Dictionary of Contemporary English 5th Edition (LDOCE 5).


## Prerequisites

```bash
sudo apt install -y pyqt4-dev-tools python-lxml python-whoosh python-gst0.10
sudo pip install whoosh==2.5.7
sudo apt install -y gstreamer0.10-plugins-good
sudo apt install -y gstreamer0.10-plugins-ugly
sudo apt install python-qt4-phonon
```


## Installation - Ubuntu 16.04.4

1. Enter the following commands in the terminal:

```bash
git clone git@github.com:hankunpeng/ldoce5viewer.git
cd ldoce5viewer
make build
sudo make install
```

2. Copy the 'ldoce5.data' directory from the LDOCE5 DVD-ROM to an arbitrary location in your HDD or SSD.

3. Start the LDOCE5 Viewer.(e.g.: enter `ldoce5viewer` in the terminal)

4. The application will ask you the location where you put 'ldoce5.data'.

做了个 ldoce5.data.zip(1.6GB)，学习交流用，需要的可以联系我。