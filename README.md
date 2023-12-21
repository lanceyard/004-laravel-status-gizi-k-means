## Pengelompokan Status Gizi w/ Metode K-Means

waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, waterflow, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster, cluster,

<hr/>

##### Initial Setup
- Setup Laravel Project
  ```bash
  composer install && php artisan key:generate && php artisan storage:link
  ```
  - composer install
  - php artisan key:generate
  - php artisan storage:link

- Setup .env
  ```bash
  mv .env.example .env
  ```
  - rename the template to .env
  - sesuaiin aja sih sesuai keinginan

<hr/>

##### Serve Laravel
- Serve aja (no local network hosting):
  ```bash
  php artisan serve
  ```
<!-- - Serve + local network hosting :
  ```bash
  php artisan serve --host 192.168.106.112 --port=8000
  ```
Ganti IP setelah `--host` pake local ipmu. biar app flutter (dari hp misal *satu network) bisa ngakses API Laravel. Referensi buat check command atau command di atas bisa dilihat di bawah.

   - `--host` : isinya parameter ini IP (local ip)
   - `--port` : bisa diisi kalo portnya tabrakan sama yg laen -->

<hr/>

The BEERWARE License (BEERWARE)

Copyright (c) 2022 Ongghuen Team. All rights reserved.

Licensed under the "THE BEER-WARE LICENSE" (Revision 42):
Ongghuen Team wrote this file. As long as you retain this notice you
can do whatever you want with this stuff. If we meet some day, and you think
this stuff is worth it, you can buy me a beer or coffee in return
