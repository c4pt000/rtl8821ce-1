
## Installation
```
git clone https://github.com/tomaspinho/rtl8821ce.git
cd rtl8821ce/
sudo make all
sudo make install
sudo modprobe -a 8821ce
```

## After every update thi should be run
```
cd rtl8821ce
make clean
make
sudo make install
sudo modprobe 8821ce
```

## Similar solution in Ubuntu forums but do not work for me
https://ubuntuforums.org/showthread.php?t=2371149&page=3&p=13702710#post13702710

## Link to stack owerflow solution
https://askubuntu.com/questions/1021865/driver-for-realtek-rtl8821ce-lenovo-720s-13arr-ultrabook
