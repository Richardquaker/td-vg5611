Tenha um gravador de Flash caso falhe algo!

Passar o arquivo de configução configssh.bin

Putty telnet 192.168.1.1:1023

Abrir o tftpd64.exe

comandos no terminal putty

tftp -g -l /var/tmp/mtd0 -r mtd0 192.168.1.2

tftp -g -l /var/tmp/mtd1 -r mtd1 192.168.1.2

tftp -g -l /var/tmp/mtd2 -r mtd2 192.168.1.2

tftp -g -l /var/tmp/mtd3 -r mtd3 192.168.1.2

tftp -g -l /var/tmp/mtd4 -r mtd4 192.168.1.2

tftp -g -l /var/tmp/mtd5 -r mtd5 192.168.1.2

cat /var/tmp/mtd0 > /dev/mtdblock0

cat /var/tmp/mtd1 > /dev/mtdblock1

cat /var/tmp/mtd2 > /dev/mtdblock2

cat /var/tmp/mtd3 > /dev/mtdblock3

cat /var/tmp/mtd4 > /dev/mtdblock4

cat /var/tmp/mtd5 > /dev/mtdblock5
