# FP_WEB_SERVER
Pembuatan Web Server

# WEB SERVER
Web server adalah sebuah software (perangkat lunak) yang memberikan layanan berupa data. Berfungsi untuk menerima permintaan HTTP atau HTTPS dari klien atau kita kenal dengan web browser (Chrome, Firefox). Selanjutnya ia akan mengirimkan respon atas permintaan tersebut kepada client dalam bentuk halaman web.

# Tools
1. VirtualBox 7.0
2. ISO Ubuntu Server 22.04.03 LTS
3. Visual Studio Code

# Service
1. SSH
2. Apache2 ( Web Server )
3. Webmin ( Control Panel )
4. BIND9

# Progres
1. Install Ubuntu Server 22.04
2. Install SSH ( Default Ubuntu )
3. Install Apache2
      - "sudo apt install apache2"
      - "sudo ufw app list" - "sudo ufw allow 'Apache" - "sudo ufw status ( Untuk Mengaktifkan Port Apche Agar Bisa Diakses )"
4. Install Webmin
      - "sudo apt install webmin"
      - "sudo ufw allow 10000" ( Mengakses Port 10000 )"
      - "Access Web "https://your_server:10000" ( Digunakan Untuk Control Panel )"
5. Install BIND9
      - "sudo apt install bind9 bind9utils bind9-doc"
6. 
   
