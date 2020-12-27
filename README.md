# AlamRES14
195410046_MUHAMMMAD DZUHRI ALAMSYAH_KELAS TI 1<br>
<p><b>Membuat docker container dengan docker file</b>
Buat file di docker toolbox C:\Program Files\Docker Toolbox<br>
![image](https://user-images.githubusercontent.com/71113482/103167262-482c8380-485c-11eb-8301-ededeed5dfe1.png)<br>
kemudian buat file Dockerfile didalam direktori yang sudah anda buat contoh 195410046 isi file docker sbb:<br>
![image](https://user-images.githubusercontent.com/71113482/103167287-8de94c00-485c-11eb-8ab8-40817527fee7.png)<br>
buat direktori file di dalam direktori nim(195410046) yang berisis<br>
file deault.conf<br>
  ![image](https://user-images.githubusercontent.com/71113482/103167405-8d9d8080-485d-11eb-98f6-636704593359.png)<br>
file index.html<br>
![image](https://user-images.githubusercontent.com/71113482/103167474-f1c04480-485d-11eb-9fcc-c3fc1e040f92.png)<br>
file nginx.conf<br>
![image](https://user-images.githubusercontent.com/71113482/103167518-4237a200-485e-11eb-9069-d7cbdd45ac6a.png)
berikut ini adalah struktur direktori yg sudah di buat<br>
![image](https://user-images.githubusercontent.com/71113482/103167545-7317d700-485e-11eb-910e-ae20a4adccbb.png)<br>
![image](https://user-images.githubusercontent.com/71113482/103167553-80cd5c80-485e-11eb-8afb-dff3489ac276.png)<br>
kemudian build images  menggunakan perintah “docker build -t nama-nimanda ."<br>
![image](https://user-images.githubusercontent.com/71113482/103167591-e883a780-485e-11eb-96d5-03c1d827bb59.png)<br>
kemudian cek apa kah sudah jadi<br>
![image](https://user-images.githubusercontent.com/71113482/103167608-1ec12700-485f-11eb-840c-8a1194c80ecf.png)<br>
cek apakah images bisa dijalankan menggunakan perintah “ docker run -d -p 8000:80 –name nim-nama namaimage”<br>
![image](https://user-images.githubusercontent.com/71113482/103167623-4adca800-485f-11eb-9e5d-bcfb398df5a7.png)<br>
kemudian buka browser dan ketikan url http://192.168.99.100:8000/ jika web menampilkan file index.html maka images berhasil dijalankan<br>
![image](https://user-images.githubusercontent.com/71113482/103167648-82e3eb00-485f-11eb-9135-aa54e176318d.png)<br>

<b>Build image menggunakan github ke docker hub </b>
buat repo, disini saya menggunakan nama AlamRES14
![image](https://user-images.githubusercontent.com/71113482/103167704-11586c80-4860-11eb-97cd-ed45dbac8baa.png)
kemudian clone repo menggunakan git bash, seperti gambbar ini
![image](https://user-images.githubusercontent.com/71113482/103167715-3351ef00-4860-11eb-980f-9c1898328c47.png)
jalankan perintah git clone alamat repo, contoh 
![image](https://user-images.githubusercontent.com/71113482/103167741-52508100-4860-11eb-8a96-19b74af7a1ef.png)
</p>
