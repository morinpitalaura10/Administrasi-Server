#Remote Instance with SSH putty

1. pastikan sudah install putty (putty.org/index.html)
![alt text](image1c.png)

2. Konversi file public key dari .pem menjadi .ppk di putty
    - buka puttyGen
    - load file.pem
    - save as .ppk
![alt text](image2c.png)

3. SetUp  putty untuk remote SSH
    - buka apps putty
    - isi IP publik sesuai instance masing-masing
    - isi form untuk SSH sesuai Security Group di Instance
    - isi nama session agar saat konek lagi tinggal load saja
    - load file .ppk (klik SSH -> pilih auth -> credentials -> load file .ppk)
    - kembali ke session klik save
    - masukkan username ubuntu

![alt text](image3c.png)

![alt text](image4c.png)

![alt text](image5c.png)

4. sudo apt-get Update (Update OS) sudo apt-det upgrade

![alt text](image6c.png)

5. Pembuktian remote SSH secara visual
    -copy publik IP address instance paste ke browser
    - isntall web server apache/nginx
    - sudo apt install apache2 -y

![alt text](image7c.png)

![alt text](image8c.png)

10. matikan instance agar tidak kena tagihan

![alt text](image9c.png)

![alt text](image10c.png)