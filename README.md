# Enhanced ADB
List all devices if there're more than one device/emulator has connected to your computer before using any function throught ADB.

# Usage
Firstly, add the path about **adbs** to your PATH.

```shell
git clone git@github.com:demonk/adbs.git
cd adbs
echo "export PATH=$PATH:`pwd`" >> ~/.bashrc
```

Then use it as official ADB.

### Sample
```shell
abds pull /etc/hosts ~
```

![](sample.png)

select serial number you want.

# Requirement
ABD command should be available under shell.

# TODO
- [ ] single command dispatch to all devices have connected
