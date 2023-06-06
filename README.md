# Realtek-RTL8811C-Linux

Driver information
- Packages: RTL881C/CU - Linux Driver
- Version: v5.4.1_28754.20180921_COEX20180712-3232
- Arch: ARM, X86, MIPS, X64

Requirements packages
- dkms
- bc

For Debian based (apt)
- `apt update -y; apt upgrade -y; apt install dkms bc git unzip -y`

Installation [manual]
- `git clone https://github.com/wildy238/Realtek-RTL8811C-Linux.git && cd Realtek-RTL8811C-Linux && unzip -o Realtek-RTL8811C-Linux.zip && make && make install`
- `reboot`
- Done

Installation [dkms]
- `git clone https://github.com/wildy238/Realtek-RTL8811C-Linux.git && cd Realtek-RTL8811C-Linux && unzip -o Realtek-RTL8811C-Linux.zip && chmod +x dkms-install.sh && ./dkms-install.sh`
- `reboot`
- Done

