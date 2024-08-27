# ArmCord Apt Repository

You probably are looking for ArmCord itself: <https://github.com/ArmCord/ArmCord>

Add to your system:

```bash
sudo curl -SsL -o /etc/apt/trusted.gpg.d/armcord.asc https://apt.armcord.app/key.asc
sudo curl -SsL -o /etc/apt/sources.list.d/armcord.list https://apt.armcord.app/armcord.list
sudo apt update
sudo apt install armcord
```

[![Parse-dpkg](https://github.com/ArmCord/apt-repo/actions/workflows/dpkg.yml/badge.svg)](https://github.com/ArmCord/apt-repo/actions/workflows/dpkg.yml)

This repo's page deployment will cancel, and then run again after the actions finish. This is normal behavior
