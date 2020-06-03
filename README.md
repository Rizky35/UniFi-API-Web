# UniFi-API-Web
From Art of WiFi

Dijalankan dengan Web Sever
Requirement :
1. Apache2
2. PHP (testing di PHP 7.2 Done)
3. Curl

Dijalankan tanpa Web Browser
Requirement :
1. PHP (testing di PHP 7.2 Done)
2. Curl
3. php-curl dan php-cli

Langkah penggunaan tanpa Web Browser:
1. Download
2. Install Package yang dibutuhkan "apt-get install curl php php-curl php-cli"
3. Ekstrak dan letakkan di folder Root
4. Lokasi API di folder "/root/UniFi/vendor/art-of-wifi/unifi-api-client/examples/"
   - list_connected_users.php (daftar Client terhubung, output file di list_clients.txt)
   - list_rogueaps.php (daftar Access Point di sekitar - Nearby, output file di list_rogueaps.txt)
5. Sesuaikan kredensial / user login ke UniFi Server di "/root/UniFi/config/config.php"
6. Sesuaikan juga kredensial di file "list_connected_users.php" dan "list_rogueaps.php"
   - Site ID nya adalah "uqfx7sat" di ambil dari "https://ip-controller:8443/manage/site/uqfx7sat/settings/controller"

