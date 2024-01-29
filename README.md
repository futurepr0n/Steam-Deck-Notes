# Steam-Deck-Notes
Steam Deck Notes for after Updates

System needs to re-install OpenVPN:
sudo steamos-readonly disable
sudo pacman-key --init
sudo pacman-key --populate archlinux
sudo pacman-key --populate holo


sudo pacman -S networkmanager-openvpn (not required any more after first successful install)
sudo pacman -S base-devel multilib-devel
sudo pacman -S rgbds
sudo pacman -S jre8-openjdk

