# FP_WEB_SERVER
Pembuatan Web Server

# WEB SERVER
Web server adalah sebuah software (perangkat lunak) yang memberikan layanan berupa data. Berfungsi untuk menerima permintaan HTTP atau HTTPS dari klien atau kita kenal dengan web browser (Chrome, Firefox). Selanjutnya ia akan mengirimkan respon atas permintaan tersebut kepada client dalam bentuk halaman web.

# Tools
1. VirtualBox 7.0
2. ISO Ubuntu Server 22.04.03 LTS

# Service
1. SSH
2. Apache2 ( Web Server )
3. PHP 8.1
4. Webmin ( Control Panel )

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
5. Tampilan Halaman HTML
   
