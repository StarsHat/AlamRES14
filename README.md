# AlamRES14
195410046_MUHAMMMAD DZUHRI ALAMSYAH_KELAS TI 1<br>
<p><b>Membuat docker container dengan docker file</b>
<br>
Buat file di docker toolbox C:\Program Files\Docker Toolbox<br>
![image](https://user-images.githubusercontent.com/71113482/103167952-15858980-4862-11eb-9014-9c17481b033a.png)
kemudian buat file Dockerfile didalam direktori yang sudah anda buat contoh 195410046 isi file docker sbb:<br>
![image](https://user-images.githubusercontent.com/71113482/103167287-8de94c00-485c-11eb-8ab8-40817527fee7.png)
buat direktori file di dalam direktori nim(195410046) yang berisis</br>
file deault.conf
  ![image](https://user-images.githubusercontent.com/71113482/103167405-8d9d8080-485d-11eb-98f6-636704593359.png)
file index.html
![image](https://user-images.githubusercontent.com/71113482/103167474-f1c04480-485d-11eb-9fcc-c3fc1e040f92.png)
file nginx.conf
![image](https://user-images.githubusercontent.com/71113482/103167518-4237a200-485e-11eb-9069-d7cbdd45ac6a.png)
berikut ini adalah struktur direktori yg sudah di buat
![image](https://user-images.githubusercontent.com/71113482/103167545-7317d700-485e-11eb-910e-ae20a4adccbb.png)
![image](https://user-images.githubusercontent.com/71113482/103167553-80cd5c80-485e-11eb-8afb-dff3489ac276.png)
kemudian build images  menggunakan perintah “docker build -t nama-nimanda ."
![image](https://user-images.githubusercontent.com/71113482/103167591-e883a780-485e-11eb-96d5-03c1d827bb59.png)
kemudian cek apa kah sudah jadi
![image](https://user-images.githubusercontent.com/71113482/103167608-1ec12700-485f-11eb-840c-8a1194c80ecf.png)
cek apakah images bisa dijalankan menggunakan perintah “ docker run -d -p 8000:80 –name nim-nama namaimage”
![image](https://user-images.githubusercontent.com/71113482/103167623-4adca800-485f-11eb-9e5d-bcfb398df5a7.png)
kemudian buka browser dan ketikan url http://192.168.99.100:8000/ jika web menampilkan file index.html maka images berhasil dijalankan
![image](https://user-images.githubusercontent.com/71113482/103167648-82e3eb00-485f-11eb-9135-aa54e176318d.png)

<b>Build image menggunakan github ke docker hub </b>
buat repo, disini saya menggunakan nama AlamRES14
![image](https://user-images.githubusercontent.com/71113482/103167704-11586c80-4860-11eb-97cd-ed45dbac8baa.png)
<br>
kemudian clone repo menggunakan git bash, seperti gambbar ini
![image](https://user-images.githubusercontent.com/71113482/103167715-3351ef00-4860-11eb-980f-9c1898328c47.png)
<br>
jalankan perintah git clone alamat repo, contoh<br>
![image](https://user-images.githubusercontent.com/71113482/103167741-52508100-4860-11eb-8a96-19b74af7a1ef.png) <br>
kemudian masukan file nim ke dalam direktori yg sudah di clone tadi, kemudian pindah ke direktori yg sudah terclone tadi dgn cara "cd namadirektori"<br>
![image](https://user-images.githubusercontent.com/71113482/103168036-a9575580-4862-11eb-91e7-388e9c668f68.png)
<br/>
kemudian push repo dgn cara sbb:<br>
sebelum itu kita harus login dulu dgn cara "git config --global user.name "nama" dan "git config --global user.email "email " sbb<br>
![image](https://user-images.githubusercontent.com/71113482/103168122-2256ad00-4863-11eb-8fc1-673a3e90581f.png)
cara cek menggunakan "git config --list"<br>
![image](https://user-images.githubusercontent.com/71113482/103168136-34d0e680-4863-11eb-9ab2-e2322e907749.png) <br>
"git init" : untuk membuat repository pada file lokal yang nantinya ada folder <br>
"git add *" : untuk menambahkan file kedalam gihub<br>
"git commit" : untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada repo<br>
 Git push : untuk mengirimkan perubahan file setelah di commit ke remote repo<br>
 ![image](https://user-images.githubusercontent.com/71113482/103168226-f8ea5100-4863-11eb-8a77-6d6a39e68983.png)
![image](https://user-images.githubusercontent.com/71113482/103168231-fe479b80-4863-11eb-87d1-bcc907c38e00.png)
kemudian akan muncul perintah login ke github<br>
![image](https://user-images.githubusercontent.com/71113482/103168243-10c1d500-4864-11eb-9780-24e9672225f6.png)
<br>
kemudian hubungkan git dgn github anda<br>
![image](https://user-images.githubusercontent.com/71113482/103168258-2800c280-4864-11eb-99e1-55a70fcbfadb.png)
<br>
kemudian cek repo github anda apakah file sudah terupload belum<br>
![image](https://user-images.githubusercontent.com/71113482/103168283-4bc40880-4864-11eb-8789-3cf5e18946e6.png)


</p>
