- porta 1 GARR
- dalla 2 alla 4 VLAN utility net 10.158.115.0 (escluso 1 e 254) apparati i rete ip statico tipo badge, apparati di rete
    - se non ci rimettono la rete garr, per mettere hotspot con scheda di rete configurata con ip statico - se rete ce ma configurazione non va bene
- dalla 6 alla 45 sono client - .112.x in dhcp
- la 114.x e voip
- la 113.x e server
- la 115.x utility


$ sudo systemctl mask brltty.path
$ sudo systemctl stop brltty.path
sudo usermod -a -G dialout $USER

sudo screen /dev/ttyUSB0 9006
