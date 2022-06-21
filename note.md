## Porte sullo switch
- porta 1 GARR
- dalla 2 alla 4 VLAN utility net 10.158.115.0 (escluso 1 e 254) apparati i rete ip statico tipo badge, apparati di rete
    - se non ci rimettono la rete garr, per mettere hotspot con scheda di rete configurata con ip statico - se rete ce ma configurazione non va bene
- dalla 6 alla 45 sono client - .112.x in dhcp
- la 114.x e voip
- la 113.x e server
- la 115.x utility

## Connessione in seriale (ad ap)
$ sudo systemctl mask brltty.path
$ sudo systemctl stop brltty.path
sudo usermod -a -G dialout $USER

sudo screen /dev/ttyUSB0 9006

admin
fortiap

## Test connettività rete tranciata
provare almeno i primi 6 bussolotti

punto punto
lato nostro
193.206.136.217
lato loro
193.206.136.216

fare hotspot e con la scheda di rete mi attacco al firewall

attacco sulla porta di management sullo swithc (dalla 2 alla 4)
imposto 10.158.115.10 sul pc
e apro sul browser
10.158.115.254 per il firewall 
admin admin

da interfaccia web, console
exceute ping 193.206.136.216

## Controllare coppia
controllare gbic
controllare scatoletta 
monodale lx long range
dalla 11 alla 24 tutte ispra = 14 coppie
se coppie provare sulla coppia 11 invece della 6
so 24 coppie
