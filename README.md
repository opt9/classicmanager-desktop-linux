# Requirement

* pepperflashplugin-nonfree
  * [Debian](https://wiki.debian.org/PepperFlashPlayer/Installing)
  * [Ubuntu](http://packages.ubuntu.com/fr/yakkety/pepperflashplugin-nonfree)

# Setup

```
curl -LsS https://github.com/opt9/classicmanager-desktop-linux/releases/download/v0.0.1/classicmanager-desktop-for-linux_0.0.1_amd64.deb -o classicmanager-desktop-for-linux.deb
sudo dpkg -i classicmanager-desktop-for-linux.deb
```

# Development
## How to run
```
npm install
npm start
```

## How to build
```
npm install
cd app && npm install && cd ..
npm run build
npm run dist
```
