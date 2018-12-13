# Infrastruktur as Code

Infrastructure as Code adalah proses penyediaan IT infrastruktur dimana sistem dibangun dan dikelola melalui kode secara automasi (otomatis), bukan secara manual. Atau bisa disebut juga bahasa kerennya Programmable Infrastructure.

Dengan menggunakan kode dan meng-automasi, proses setting dan konfigurasi baremetal, virtual mesin, cloud computing baik itu instalasi baru, perubahan konfigurasi dapat dilakukan secara cepat, mudah, dan berulang. Di sisi lain juga, ada manfaat lainnya yaitu dokumentasi. Jadi siapapun tahu konfigurasi server, kebutuhan aplikasi server dan sebagainya.

Kali ini saya menggunakan Terraform, dan menggunakan OS Ubuntu 18.04

## Installing Terraform

Download pada link berikut https://www.terraform.io/downloads.html

kemudian 

```bash
elfay@elfay-X540LJ:~$ export PATH=$PATH:/home/elfay/Documents/terra
```

## Verifikasi Instalasi
```bash
elfay@elfay-X540LJ:~$ terraform 
Usage: terraform [-version] [-help] <command> [args]

The available commands for execution are listed below.
The most common, useful commands are shown first, followed by
less common or more advanced commands. If you're just getting
started with Terraform, stick with the common commands. For the
other commands, please read the help and docs before usage.
```
![Cek](https://raw.githubusercontent.com/faytranevozter/iac/master/Screenshot%20from%202018-12-13%2018-17-20.png)
