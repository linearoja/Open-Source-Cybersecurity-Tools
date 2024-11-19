# OSC Inventory - (Inventario de Equipos Automatizados)

**Instalacion de dependencias**
```bash
yum install epel-release -y
wget http://rpms.famillecollet.com/enterprise/remi-release-7.rpm
rpm -ivh remi-release-7.rpm
```

**Editar y habilitar el repo remi y php 5.6**
```bash
yum install httpd httpd-devel mod_perl mod_php mod_ssl php-gd php-mysql php-mbstring php perl perl-XML-Simple perl-Compress-Zlib perl-DBI perl-DBD-MySQL perl-Net-IP 
yum install perl-SOAP-Lite perl-Apache-DBI perl-Apache2-SOAP php-xml
yum install perl-XML-Entities wget perl-Archive-Zip mariadb-server perl-Mojolicious* perl-Switch perl-Plack* perl-Parse-EDID php-soap 
```

```bash
apt-get install libcrypt-ssleay-perl libnet-snmp-perl libproc-pid-file-perl libproc-daemon-perl net-tools 
apt-get install libsys-syslog-perl pciutils smartmontools read-edid nmap libxml-simple-perl make cpanminus
cpanm install Net::IP
cpanm install Net::Netmask

```
