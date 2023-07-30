# Geph VPN for linux

## Steps

### 1. Download file:

https://geph.io/en

### 2. Install Flatpak:

```
sudo add-apt-repository ppa:flatpak/stable
sudo apt update
sudo apt install flatpak
```

### 3. Install the Software Flatpak plugin

```
sudo apt install gnome-software-plugin-flatpak
```
### 4. Add the Flathub repository

```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

### 5. `Restart your system`

<br/>


### 6. Install Geph by using flatpak 

```
sudo flatpak install Geph-x86_64.flatpak
```
### 7. Run Geph

```
flatpak run io.geph.GephGui
```





