
# Freifunk Lausitz

https://www.freifunk-lausitz.de/

Dieses Repoistory beeinhaltet die configuration der Firmware.


## Netz Daten

* ASN: 64876


### IPv6
* Prefix/L: fd
* Global ID: 251952c72e
* Subnetz Domaene 0 gateways (Subnet 0000): fd25:1952:c72e:0000::/64
* Subnetz Domaene 1 (Subnet 0001): fd25:1952:c72e:0001::/64
* Subnetz Domaene 2 (Subnet 0002): fd25:1952:c72e:0002::/64

### IPv4
* 10.39.0.0/16


### ICVPN Transfer
transfer:
- [10.207.0.29, 'fec0::a:cf:0:1d']

### DNS
* Domain: fflz



# Todo

* freirunk-lausitz.de einrichten auf dns
  * gwdom1-1.freifunk-lausitz.de
  * gwdom1-2.freifunk-lausitz.de
* fflz domain
  * 1.ntp.services.fflz
  * 2.ntp.services.fflz
  * 1.updates.services.fflz
* /stable/sysupgrade
* pl / cz translation
* mail einrichten:
  * keys@freifunk-lausitz.de
  * info@freifunk-lausitz.de

