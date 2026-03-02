#Membuat EC2/ Instance / VM

1. Pilih menu all services -> Pilih EC@
![alt text](image1a.png)

2. Di dalamn EC2 kita pilih Instance
![alt text](image2a.png)

3. Di dalam menu instance pilih menu low instance
![alt text](image3a.png)

4. Beri nama Instance  kita dengan NIM_Server
![alt text](image4a.png)

5. Kita pilih OS server untuk instance kita
![alt text](image5a.png)

6. Pilih resource instance T3.Micro (2VCPU, 1GB Memory)
![alt text](image6a.png)

7. Membuat Key Pair, pilih new key pair, isi nama key, pilih RSA untuk enkripsi, format file.pem, create key pair
![alt text](image7a.png)

8. setting kebijakan keamanan atau security group
    - allow SSH = membolehkan remote SSH dari luar
    - allow HTTPS = instance bisa diakses dari protokol HTTPS
    - allow HTTP = instance bisa diakses dari protokol HTTP
![alt text](image8a.png)

9. Selesai set up pilih Launch Instances
![alt text](image9a.png)

10. Pastikan launch instance kita sukses
![alt text](image10a.png)
