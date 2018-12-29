<!-- $theme: default -->

# Distributions gnu linux
###### Par Julien Dauliac ( [@Dauliac](https://github.com/dauliac) )

---
# Distributions gnu linux


###### Par Julien Dauliac ( [@Dauliac](https://github.com/dauliac) )

> *Apprendre par la pratique*

---
<!-- page_number: true -->

## Rappel

- kernel
- binaires (firefox, python, cd)
    - bootloader (grub)
    - system manager (systemd, init)

---
## Rappel

> **Tout** est un fichier.

> On peut appeler **tout** les binaires depuis le terminal.

---
## Archlinux
archlinux - *2002*
![arch](img/arch.png)

---
## Archlinux
> Les distributions sont des constructions sociale.

> Rolling release: toujours la dernière version.

> Très bon wiki
 
> Pousse à apprendre

  

---
## Let's go
![usb](img/usb.png)
- [Guide d'installation](https://wiki.archlinux.fr/installation)
- [Installation guide](https://wiki.archlinux.org/index.php/installation_guide)
- [dualboot](https://wiki.archlinux.org/index.php/Dual_boot_with_Windows)
---

### Internet
```bash
cat /etc/wpa_supplicant.conf
network={
        ssid="Dauliac"
        psk="wifi1234"
}
```

---
### Internet
```bash
wpa_supplicant -i wlan0 -c /etc/wpa_supplicant.conf &
dhcpd wlan0
```

---
### Yay
+- Gestionaire de paquets
```bash
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si
```

---
### Yay
Quelques commandes
```
yay # met Ã  jour les paquets
yay -c # suprime les paquets de build
yay -S xorg-xinit gnome # Installe des paquets
```

---
### Gnome
![gnome](img/gnome.png)
Distribution user friendly

---
## Wiki et gourou
Etre currieux, chercher, demmander de l'aide.

---
<!-- page_number: false -->

## Bon chance:

Copyright &copy; 2018

