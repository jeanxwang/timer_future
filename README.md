# Tutorial 10 - Adpro

## Aliyah Faza Qinthara

### 1.2. Understanding how it works.
![alt text](Screenshot 2024-05-08 173129.png)
Dari apa yang diperhatikan dari hasil output, terlihat bahwa fungsi async beroperasi di luar fungsi utama yang memanggilnya. Ini berarti bahwa "hey hey" bisa muncul lebih dulu daripada "howdy!" dan "done!", karena "hey hey" dipanggil di luar fungsi async, sedangkan fungsi async menunggu hasil dari future sebelum melanjutkan eksekusi program.
