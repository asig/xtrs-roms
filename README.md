xtrs-roms
=========

I became tired of manually copying over the TRS-80 ROMs whenever I decide to go for a fresh reinstall, so that's why I set up this repo.

Usage
-----
```bash
cd /usr/local/lib/xtrs
sudo git init
sudo git remote add origin https://github.com/asig/xtrs-roms.git
sudo git fetch origin
sudo git checkout -b master --track origin/master
```