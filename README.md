## Run different architecture distros in termux !
- A automatic script to install any distro by yourself in Termux, but in different architecture using QEMU support.
- Only support aarch64 architecture!

### Running x86_64 distros
```bash 
pkg in wget -y 
wget https://raw.githubusercontent.com/23xvx/Termux-x86_64-distro-on-aarch64/master/AMD64.sh
bash AMD64.sh 
```

### Running x86 distros
``` bash 
pkg in wget -y
wget https://raw.githubusercontent.com/23xvx/Termux-x86_64-distro-on-aarch64/master/i386.sh
bash i386.sh 
``` 
