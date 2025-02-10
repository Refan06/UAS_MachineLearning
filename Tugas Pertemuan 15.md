**1.	Buat folder pyproject didalam folder pyhon, setelah itu buat folder baru kembali dengan nama plmdiabetes**
![image](https://github.com/user-attachments/assets/7221ea38-e515-4c6c-9a41-ea45b82c1833)


**2.	Buka CMD lalu masuk ke directory yang sudah dibuat sebelumnya**
![image](https://github.com/user-attachments/assets/d4249199-133c-4ffd-a975-36b5d61a62eb)

**3.	Install virtual env lalu buat virtual env dengan folder env di cmd**
![image](https://github.com/user-attachments/assets/eb2ca539-43e9-43ca-a77e-ffadc19b8af1)

**4.	Pada folder env aktifkan untuk masuk ke dalam environment, dengan nama file activate.bat**
 ![image](https://github.com/user-attachments/assets/4712b722-5d7a-4538-9802-b8f136a4ac1e)

**5.	Install library flask-sqlalchemy untuk membuat aplikasi web**
![image](https://github.com/user-attachments/assets/26d715c3-6b14-4388-9d85-4bf9c59bce6a)\
**6.	Install library scikit-learn dengan pip install**
![image](https://github.com/user-attachments/assets/b05f2b15-c4cf-41b3-b9a3-7ab3e7377f69)

**7.  Buka VSCode, open folder plm diabetes, setelah itu buat file dengan nama app.py di folder tersebut, dengan source code berikut.**\
![image](https://github.com/user-attachments/assets/553cb081-b8fe-4c84-ac0d-7fe8b64bdd45)
![image](https://github.com/user-attachments/assets/29cd477f-8ccf-4594-8103-5a322c73cf23)



**8.  Download template web**
-  Simpan folder css pada folder static\
![image](https://github.com/user-attachments/assets/17833d64-26b0-4bb9-9caf-537e94c590e5)
-	Simpan index.html, hasil.html, base.html pada folder templates\
![image](https://github.com/user-attachments/assets/df72e3d9-69d1-403d-b8d2-aa9eabd54ef5)
-	SC Base.html\
![image](https://github.com/user-attachments/assets/d41e69d2-66ef-40bf-8160-7999285c4836)
-	SC hasil.html\
![image](https://github.com/user-attachments/assets/6f77d979-4a6c-4b6e-9dde-6fb69be33b18)
![image](https://github.com/user-attachments/assets/fd486bc6-cf52-4efc-8342-eb50cf39369e)

-	SC index.html\
![image](https://github.com/user-attachments/assets/905c7682-1934-4ef5-bb15-8c0483a96134)
![image](https://github.com/user-attachments/assets/917d34bc-84d2-43b4-9dd2-e2363c353a90)
![image](https://github.com/user-attachments/assets/0afeda5b-ab2a-43ba-b4cc-b543e6c610b4)

**9.  Download file knn pickle di github dan simpan pada folder plmdiabetes. knn pickle merupakan model untuk masalah klasifikasi atau regresi.**\
![image](https://github.com/user-attachments/assets/788924e6-df0b-430b-a578-2e84badc7b56)

 
**10.  Running syntax pada cmd untuk requirement membuat model lalu hasil requirement sebagai berikut:**\
![image](https://github.com/user-attachments/assets/5867ca07-4202-486c-ae2b-9fd94108376f)\
lalu hasil requirement sebagai berikut:\
![image](https://github.com/user-attachments/assets/58be6264-b39e-46be-8a9a-100dd60f516c)

**11.  Lalu jalankan web dengan running syntax berikut:**\
![image](https://github.com/user-attachments/assets/b4891cd3-3cac-4486-91e2-2ef56adc808e)

**12.  Buka localhost:5000 untuk menjalankan hasil web, hasil prediksi didapat dari knn pickle yang sudah di latih.**\
![image](https://github.com/user-attachments/assets/7bf2e422-873e-4d77-8288-b84c8de98931)
![image](https://github.com/user-attachments/assets/6d4e68e5-c05e-4b62-85c8-7d5bbffe6503)
### Hosting
1.	Buat akun pada pythonanywhere.com untuk hosting aplikasi web tersebut\
![image](https://github.com/user-attachments/assets/3d49824e-559d-4b9d-b2bc-6f0d7c5e49c4)

2.	Klik menu Web apss atau web pada navigasi atas kanan\
![image](https://github.com/user-attachments/assets/ef266e41-211a-437a-89e6-6ba1bda86f14)

3.	Create new web app dengan langkah berikut:
-	Klik next\
![image](https://github.com/user-attachments/assets/4cc751a2-f95e-4a61-ae8c-9cd89f27621b)
-	Pilih Flask\
![image](https://github.com/user-attachments/assets/49f4665d-09d0-4679-a781-fab2453b3bec)

-	Pilih python terbaru (Python 3.10)\
![image](https://github.com/user-attachments/assets/f7fbfecc-a368-47ab-8193-cefdf580538f)

4.	Upload file plm diabetes, sebelum upload file tersebut dijadikan zip terlebih dahulu\
![image](https://github.com/user-attachments/assets/4b1fdd5e-8ff6-463b-a7d3-e206d742b48a)


- File Zip nya\
![image](https://github.com/user-attachments/assets/3c5c882c-9d12-477b-8f9c-b80fb4b52bbc)

5.	Kembali ke Dashboard lalu, pilih bash pada menu new console\
![image](https://github.com/user-attachments/assets/e0f3a465-812f-4cc2-9afb-9f0a00aaf195)
-	Unzip file zip yang di upload\
![image](https://github.com/user-attachments/assets/29222b31-63a8-4b71-83d3-da76f4ca3580)

-	Buat virtual env\
![image](https://github.com/user-attachments/assets/ebbeac24-10c9-4d14-aa90-1e99fb098afc)

-	Masuk ke direktori env untuk aktifkan environment\
![image](https://github.com/user-attachments/assets/bbdc79e8-e67d-43a9-a468-20c9f77b934a)
 
-	lalu install requirement\
![image](https://github.com/user-attachments/assets/62c0d1b1-1dd5-43c8-a2f1-fc7f42cb06bb)
6.	Masukkan directory environment pada menu web\
![image](https://github.com/user-attachments/assets/59d9bc06-ca6d-45df-ad42-3b34fd75d38a)

- Directory env:\
![image](https://github.com/user-attachments/assets/b2fa2476-aac3-4a66-9fe4-ba607fa107b2)

7.	Klik reload hosting kita\
![image](https://github.com/user-attachments/assets/dc462726-22ac-4aaa-8790-e29a26fc5aa9)


8.	Buka link https://refan766.pythonanywhere.com/ \
![image](https://github.com/user-attachments/assets/9cc8272e-0bff-4479-b7c7-48fc33d107fc)














