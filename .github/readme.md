# ArmCord Apt Repository

You probably are looking for ArmCord itself: <https://github.com/ArmCord/ArmCord>

Add to your system:

```bash
sudo curl -SsL -o /etc/apt/trusted.gpg.d/armcord.gpg https://apt.armcord.dev/KEY.gpg
sudo curl -SsL -o /etc/apt/sources.list.d/armcord.list https://apt.armcord.dev/armcord.list
sudo apt update
sudo apt install armcord
```
