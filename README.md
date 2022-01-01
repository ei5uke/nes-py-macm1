# What This Is

This repo allows users to use the nes-py repo but for Mac laptops that use the m1 processor. It was made using advice from user @lucasschoenhold 's repo, but there were still some issues using their repo so I fixed them here. The main issue with the original nes-py repo for the m1 processor is the usage of 
```shell 
-march=native
```
in the SConstruct.py file in nes-py/nes_py/nes and also in setup.py in nes-py/ and so I just deleted that flag. Aside from that, I also updated pyglet to install the latest version.

# Installation

```shell
pip install git+https://github.com/ei5uke/nes-py-macm1.git
```

# To Check for Proper Installation

Make sure the following command runs in the terminal:
```shell
nes_py -h 
```