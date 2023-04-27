# Build Dependencies
| Distro | Dependencies |
| -----  | ------------ |
|  Arch-based   | sudo pacman -S --needed git make ninja nasm iasl pkg-config spice-protocol dmidecode |
|  Ubuntu-based | sudo apt install -y git ninja-build nasm iasl pkg-config libglib2.0-dev libpixman-1-dev meson build-essential uuid-dev python-is-python3 libspice-protocol-dev libspice-server-dev |
|  Fedora-based | sudo dnf install -y g++ ninja-build nasm iasl libuuid-devel glib2-devel pixman-devel spice-protocol spice-server-devel |

# Usage
```
curl -O https://raw.githubusercontent.com/lexi-src/spoofed-qemu/master/qemu-comp.sh
chmod +x qemu-comp.sh
sudo ./qemu-comp.sh
```
