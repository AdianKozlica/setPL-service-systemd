Service that sets PL1 to 15 W and PL2 to 25 W using setPL.sh script

Script used from:

https://github.com/horshack-dpreview/setPL

In order to setup you need to run:

```cmd
sudo cp setPL.service /etc/systemd/system
```

```cmd
sudo systemctl enable --now setPL.service
```
