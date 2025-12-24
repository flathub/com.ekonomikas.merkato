# Merkato

___A modern financial market tracker for GNOME___

Merkato is a modern and intuitive financial market tracker designed for the GNOME desktop. Built with GTK4 and Libadwaita, it provides a native and elegant interface for monitoring stocks, indices, currencies, and cryptocurrencies in real-time using Yahoo Finance data. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub com.ekonomikas.merkato
flatpak run com.ekonomikas.merkato
```

## Building

```
git clone git@github.com:flathub/com.ekonomikas.merkato.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.ekonomikas.merkato.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python
