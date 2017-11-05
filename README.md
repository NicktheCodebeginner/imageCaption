# imageCaption

## Environment develop

```bash
$ curl -s https://raw.githubusercontent.com/torch/ezinstall/master/install-deps | bash
$ git clone https://github.com/torch/distro.git ~/torch --recursive
$ cd ~/torch;  bash install-deps
$ ./install.sh      # and enter "yes" at the end to modify your bashrc
$ source ~/.bashrc
```
```bash
$ luarocks install nn
$ luarocks install nngraph 
$ luarocks install image 
```
```bash
$ luarocks install cutorch
$ luarocks install cunn
$ luarocks install loadcaffe
```
```bash
#install hdf5
sudo apt-get install libhdf5-serial-dev hdf5-tools
git clone https://github.com/deepmind/torch-hdf5
cd torch-hdf5
luarocks make hdf5-0-0.rockspec LIBHDF5_LIBDIR="/usr/lib/x86_64-linux-gnu/"
```
```bash
#install h5py
pip install h5py
```
```bash
#github
git clone https://github.com/karpathy/neuraltalk2.git
git clone https://github.com/NicktheCodebeginner/Software-eng.git
```
