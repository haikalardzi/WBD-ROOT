# TUGAS BESAR IF3110 PENGEMBANGAN APLIKASI BERBASIS WEB

Untuk Tugas Besar IF3110 Pengembangan Aplikasi Berbasis Web, kami dari Kelompok I mengembangkan *website* Saranghaengbok. Saranghaengbok ditujukan sebagai media jasa titip *merchandise* K-Pop. 
Repositori ini adalah modul utama pada semua submodul berikut:
- [PHP-App](https://github.com/AlphaThrone/PHP-App)
- [SOAP-Service](https://github.com/AlphaThrone/SOAP-Service)
- [client-spa](https://github.com/AlphaThrone/client-spa)
- [rest-service](https://github.com/AlphaThrone/rest-service)
- [config](https://github.com/AlphaThrone/config)

## How to run

0. Clone repository
```sh
git clone -r https://github.com/AlphaThrone/WBD-ROOT.git
```
1. Masuk ke directory "config"
```
cd config
```
2. Masukkan *command* berikut ke terminal
```sh
docker compose up --build -d
``` 
3. Link-link berikut merupakan link yang digunakan pada client <br>
- php-app
```sh
localhost:8008
```  
- react-app (client SPA)
```sh
localhost:3000
```  
- phpmyadmin (untuk melakukan seeding)
```sh
localhost:8080
```  
4. Lakukan seeding dari database dan web app dapat dijalankan!
<br> **Langkah seeding akan dijelaskan di readme.md pada submodul terkait**