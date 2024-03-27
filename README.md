![Gambar 1](https://github.com/WeikyNA/Sistem-Terdistribusi/assets/123792245/499bcea8-b9cc-4c12-b9ae-829782c947b6)
![apps 19002 14352760060391844 bdbcc0c4-be35-4080-8072-75a0cfb157c9](https://github.com/WeikyNA/Sistem-Terdistribusi/assets/123792245/7248c0eb-d186-4013-b9ba-77c7188d8a39)
![1 xu1Ge_Cew0DHdSU6ETcpLQ](https://github.com/WeikyNA/Sistem-Terdistribusi/assets/123792245/6f4cd2e0-c1b4-4e27-b23d-38a90ecc163e)
Berdasarkan konteks yang disediakan, Anda dapat membuat sistem terdistribusi sebagai berikut:

Server Web (KLIEN): Anda dapat mengatur server web pada sistem asli, yang disebut sebagai "sister.local" dalam konteksnya.
Server Web (wsl ubuntu 22): Anda dapat mengatur server web lain di WSL (Subsistem Windows untuk Linux) menggunakan Ubuntu 22.04 (fokus).
Layanan mikro:
Microservice 1 (ubuntu focus): Anda dapat membuat container menggunakan LXC (Linux Containers) dengan Ubuntu 20.04 (focal) untuk microservice pertama.
Microservice 2 (ubuntu bionic): Anda dapat membuat container lain menggunakan LXC dengan Ubuntu 18.04 (bionic) untuk microservice kedua.

Harap dicatat bahwa konfigurasi di atas didasarkan pada pemahaman bahwa Anda ingin membuat sistem terdistribusi dengan dua server web (satu di sistem asli dan satu di WSL) dan dua layanan mikro (pada kontainer LXC menggunakan versi Ubuntu yang berbeda). Jika ada persyaratan khusus untuk sistem, persyaratan tersebut harus dipertimbangkan saat menyiapkan sistem.
