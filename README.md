3DS dev
-------

Install CITRA on host:

```
sudo apt install software-properties-commons
sudo add-apt-repository ppa:alexlarsson/flatpak
sudo apt update
sudo apt install flatpak
sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
sudo flatpak install https://flatpak.citra-emu.org/citra-nightly.flatpakref
flatpak run org.citra.citra-nightly
```
