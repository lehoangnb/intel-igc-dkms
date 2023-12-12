# intel-igc-dkms
intel igc driver with latest fix for proxmox kernel 6.2 (ProxmoxVE 7.4)

## Installation

Install it from source with:

```
git clone https://github.com/lehoangnb/intel-igc-dkms
cd intel-igc-dkms

sudo dkms add .
sudo dkms build igc -v 6.2
sudo dkms install --force igc -v 6.2
```
