# Jarkom-Modul-4-E10-2021

## Konten Lapres

* [VLSM](#vlsm)
* [CIDR](#cidr)


## VLSM

![image](https://user-images.githubusercontent.com/77628684/143679618-092e5bdc-23b6-4ba3-82bd-d5b65add892f.png)

### Tabel Subnetting

| Subnet | Jumlah IP  | Netmask | Subnet Mask |
| --- | --- | --- | --- |
| A1 |  |  |  |
| A2 |  |  |  |
| A3 |  |  |  |
| A4 |  |  |  |
| A5 |  |  |  |
| A6 |  |  |  |
| A7 |  |  |  |
| A8 |  |  |  |
| A9 |  |  |  |
| A10 |  |  |  |
| A11 |  |  |  |
| A12 |  |  |  |
| A13 |  |  |  |
| A14 |  |  |  |
| A15 |  |  |  |
| Total |  |  |  |

### Pohon
![image](https://user-images.githubusercontent.com/77628684/143679641-d3e93a96-5b87-4487-9a0a-1572110dc02e.png)
Lanjutan dari Atas
![image](https://user-images.githubusercontent.com/77628684/143679652-ce29d480-e3a7-45b3-b0b4-972fa2c1a0a8.png)


### Routing

| Router | Subnet | Network ID | Netmask | Next Hop |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

## CIDR

### Pengelompokan Subnet

![image](https://user-images.githubusercontent.com/68275535/143683409-498f9cfd-2b75-4598-b4c8-80f28fecc99a.png)


![image](https://user-images.githubusercontent.com/68275535/143683371-8493ddc0-fd56-4290-913f-dd06af6c9e16.png)

### Pohon

![pohon-cidr](https://user-images.githubusercontent.com/68275535/143682679-67810279-74dd-4ee1-9626-9843422664e4.png)

### Tabel Pembagian IP

| Subnet | Node | IP | Subnet Mask | Length |
| --- | --- | --- | --- | --- |
| A1 | Pucci (eth1) | 10.35.8.1 | 255.255.255.128 | 25 |
| A1 | Jipangu | 10.35.8.2 | 255.255.255.128 |  |
| A2 | Pucci (eth2) | 10.35.0.1 | 255.255.248.0 | 21 |
| A2 | Courtyard | 10.35.0.2 | 255.255.248.0 |  |
| A2 | Calmbelt | 10.35.0.3 | 255.255.248.0 |  |
| A3 | Pucci (eth0) | 10.35.16.1 | 255.255.255.252 | 30 |
| A3 | Water7 (eth2) | 10.35.16.2 | 255.255.255.252 |  |
| A4 | Water7 (eth1) | 10.35.32.1 | 255.255.252.0 | 22 |
| A4 | Cipher | 10.35.32.2 | 255.255.252.0 |  |
| A5 | Foosha (eth1) | 10.35.128.1 | 255.255.252.0 | 22 |
| A5 | Blueno | 10.35.128.2 | 255.255.252.0 |  |
| A6 | Water7 | 10.35.64.1 | 255.255.255.252 | 30 |
| A6 | Foosha (eth2) | 10.35.64.2 | 255.255.255.252 |  |
| A7 | Foosha (eth4) | 10.34.64.1 | 255.255.255.252 | 30 |
| A7 | Guanhao (eth0) | 10.34.64.2 | 255.255.255.252 |  |
| A8 | Guanhao (eth1) | 10.34.36.1 | 255.255.252.0 | 22 |
| A8 | Jabra | 10.34.36.2 | 255.255.252.0 |  |
| A9 | Guanhao (eth2) | 10.34.32.1 | 255.255.254.0 | 23 |
| A9 | Alabasta (eth0)) | 10.34.32.2 | 255.255.254.0 |  |
| A9 | Maingate | 10.34.32.3 | 255.255.254.0 |  |
| A10 | Alabasta (eth1) | 10.34.34.1 | 255.255.255.240 | 28 |
| A10 | Jorge | 10.34.34.2 | 255.255.255.240 |  |
| A11 | Guanhao (eth3) | 10.34.16.1 | 255.255.255.252 | 30 |
| A11 | Oimo (eth0) | 10.34.16.2 | 255.255.255.252 |  |
| A12 | Oimo (eth2) | 10.34.4.1 | 255.255.255.0 | 24 |
| A12 | Seastone | 10.34.4.2 | 255.255.255.0 |  |
| A12 | Enieslobby (eth0) | 10.34.4.3 | 255.255.255.0 |  |
| A13 | Seastone (eth1) | 10.34.0.1 | 255.255.252.0 | 22 |
| A13 | Elena | 10.34.0.2 | 255.255.252.0 |  |
| A14 | Foosha (eth3) | 10.34.128.1 | 255.255.255.252 | 30 |
| A14 | Doriki | 10.34.128.2 | 255.255.255.252 |  |
| A15 | Oimo (eth1) | 10.34.8.1 | 255.255.255.252 | 30 |
| A15 | Fukurou | 10.34.8.2 | 255.255.255.252 |  |

### Config Routing GNS3

#### Foosha

```bash
route add -net 10.34.4.0 netmask 255.255.255.0 gw 10.34.64.2
route add -net 10.34.0.0 netmask 255.255.252.0 gw 10.34.64.2
route add -net 10.34.8.0 netmask 255.255.255.252 gw 10.34.64.2
route add -net 10.34.36.0 netmask 255.255.252.0 gw 10.34.64.2
route add -net 10.34.32.0 netmask 255.255.254.0 gw 10.34.64.2
route add -net 10.34.34.0 netmask 255.255.255.240 gw 10.34.64.2
route add -net 10.34.16.0 netmask 255.255.255.252 gw 10.34.64.2

route add -net 10.35.8.0 netmask 255.255.255.128 gw 10.35.64.1
route add -net 10.35.0.0 netmask 255.255.248.0 gw 10.35.64.1
route add -net 10.35.32.0 netmask 255.255.252.0 gw 10.35.64.1
route add -net 10.35.16.0 netmask 255.255.255.252 gw 10.35.64.1
```

#### Water 7

```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.35.64.2
route add -net 10.35.8.0 netmask 255.255.255.128 gw 10.35.16.1
route add -net 10.35.0.0 netmask 255.255.248.0 gw 10.35.16.1
route add -net 10.35.16.0 netmask 255.255.255.252 gw 10.35.16.1
```

#### Pucci

```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.35.16.2
```

#### Guanhao

```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.34.64.1
route add -net 10.34.4.0 netmask 255.255.255.0 gw 10.34.16.2
route add -net 10.34.0.0 netmask 255.255.252.0 gw 10.34.16.2
route add -net 10.34.8.0 netmask 255.255.255.252 gw 10.34.16.2
route add -net 10.34.34.0 netmask 255.255.255.240 gw 10.34.32.2
route add -net 10.34.16.0 netmask 255.255.255.252 gw 10.34.32.2
route add -net 10.34.128.0 netmask 255.255.255.252 gw 10.34.64.1
```

#### Oimo

```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.34.16.1
route add -net 10.34.0.0 netmask 255.255.252.0 gw 10.34.4.2
```

#### Seastone

```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.34.4.1
```

#### Alabasta

```bash
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.34.32.1
```

### Config Node

#### Jipangu

```bash
auto eth0
iface eth0 inet static
address 10.35.8.2
netmask 255.255.255.128
gateway 10.35.8.1
```

#### Pucci

```bash
auto eth0
iface eth0 inet static
address 10.35.16.1
netmask 255.255.255.252
gateway 10.35.16.2

auto eth1
iface eth1 inet static
address 10.35.8.1
netmask 255.255.255.128

auto eth2
iface eth2 inet static
address 10.35.0.1
netmask 255.255.248.0
```

#### Courtyard

```bash
auto eth0
iface eth0 inet static
address 10.35.0.2
netmask 255.255.248.0
gateway 10.35.0.1
```

#### Calmbelt

```bash
auto eth0
iface eth0 inet static
address 10.35.0.3
netmask 255.255.248.0
gateway 10.35.0.1
```

#### Water7

```bash
auto eth0
iface eth0 inet static
address 10.35.64.1
netmask 255.255.255.252
gateway 10.35.64.2

auto eth1
iface eth1 inet static
address 10.35.32.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.35.16.2
netmask 255.255.255.252
```

#### Cipher

```bash
auto eth0
iface eth0 inet static
address 10.35.32.2
netmask 255.255.252.0
gateway 10.35.32.1
```

#### Foosha

```bash
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
address 10.35.128.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.35.64.2
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 10.34.128.1
netmask 255.255.255.252

auto eth4
iface eth4 inet static
address 10.34.64.1
netmask 255.255.255.252
```

#### Blueno

```bash
auto eth0
iface eth0 inet static
address 10.35.128.2
netmask 255.255.252.0
gateway 10.35.128.1
```

#### Doriki

```bash
auto eth0
iface eth0 inet static
address 10.34.128.2
netmask 255.255.255.252
gateway 10.34.128.1
```

#### Guanhao

```bash
auto eth0
iface eth0 inet static
address 10.34.64.2
netmask 255.255.255.252
gateway 10.34.64.1

auto eth1
iface eth1 inet static
address 10.34.36.1
netmask 255.255.252.0

auto eth2
iface eth2 inet static
address 10.34.32.1
netmask 255.255.254.0


auto eth3
iface eth3 inet static
address 10.34.16.1
netmask 255.255.255.252
```

#### Jabra

```bash
auto eth0
iface eth0 inet static
address 10.34.36.2
netmask 255.255.252.0
gateway 10.34.36.1
```

#### Maingate

```bash
auto eth0
iface eth0 inet static
address 10.34.32.3
netmask 255.255.254.0
gateway 10.34.32.1
```

#### Alabasta

```bash
auto eth0
iface eth0 inet static
address 10.34.32.2
netmask 255.255.254.0
gateway 10.34.32.1

auto eth1
iface eth1 inet static
address 10.34.34.1
netmask 255.255.255.240
```

#### Jorge

```bash
auto eth0
iface eth0 inet static
address 10.34.34.2
netmask 255.255.255.240
gateway 10.34.34.1
```

#### Oimo

```bash
auto eth0
iface eth0 inet static
address 10.34.16.2
netmask 255.255.255.252
gateway 10.34.16.1

auto eth1
iface eth1 inet static
address 10.34.8.1
netmask 255.255.255.252

auto eth2
iface eth2 inet static
address 10.34.4.1
netmask 255.255.255.0
```

#### EniesLobby

```bash
auto eth0
iface eth0 inet static
address 10.34.4.3
netmask 255.255.255.0
gateway 10.34.4.1
```

#### Seastone

```bash
auto eth0
iface eth0 inet static
address 10.34.4.2
netmask 255.255.255.0
gateway 10.34.4.1

auto eth1
iface eth1 inet static
address 10.34.0.1
netmask 255.255.252.0
```

#### Elena

```bash
auto eth0
iface eth0 inet static
address 10.34.0.2
netmask 255.255.252.0
gateway 10.34.0.1
```

#### Fukurou

```bash
auto eth0
iface eth0 inet static
address 10.34.8.2
netmask 255.255.255.252
gateway 10.34.8.1
```

## Kendala

- Bingung cara mengelompokkan subnet dengan CIDR
- Kesulitan debug config di GNS3