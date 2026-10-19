# Tugas_Pratikum5

1. Eksekusi seluruh profile yang ada :

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :


<img width="1280" height="800" alt="1 a 1" src="https://github.com/user-attachments/assets/d2849f6d-cf9e-48d4-8acf-a825452f83ca" />


<img width="1280" height="800" alt="1 a 2" src="https://github.com/user-attachments/assets/51bb79f1-73c5-48e7-841b-1cfba56c15c8" />



b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

<img width="1280" height="800" alt="1 b1" src="https://github.com/user-attachments/assets/ad7274cf-af29-45e7-bd83-ddb239b94ace" />


<img width="1280" height="800" alt="1b2" src="https://github.com/user-attachments/assets/5216129f-8d5f-4ddd-84a1-d114462530d2" />



<img width="1280" height="800" alt="1b3" src="https://github.com/user-attachments/assets/0dc1c531-48e3-4300-a2ed-a1057632063d" />


c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut:

<img width="1280" height="800" alt="1c1" src="https://github.com/user-attachments/assets/c975d29a-a7ec-4ce1-9ddb-635f5962c6c7" />


perbedaan kedua utilitas tersebut adalah:

su username : beralih ke pengguna lain tanpa melalui lingkungan login secarah penuh.

su - username : Beralih ke pengguna lain dengan lingkungan login, termasuk pengaturan lingkungan dan pembacaan file profile login yang sesuai.


2. Prompt String (PS)

a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan
dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal
oleh semua shell.


<img width="1280" height="800" alt="2a1" src="https://github.com/user-attachments/assets/0d49babf-8719-4e58-a431-a3316d6580b8" />


b. Eksperimen hasil PS1 :

<img width="1280" height="800" alt="2b" src="https://github.com/user-attachments/assets/769a7a49-a641-4ec2-87e1-826cf5131fef" />


3. Logout Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout.
   

   <img width="1280" height="800" alt="3a3" src="https://github.com/user-attachments/assets/3f8fdf88-9a0d-4778-9009-dee42cb25352" />


   <img width="1280" height="800" alt="3a4" src="https://github.com/user-attachments/assets/c7a03011-5d4d-4e1d-a439-f1d8ec4b7717" />



4. Bash script


a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :

<img width="1280" height="800" alt="4a1" src="https://github.com/user-attachments/assets/5668ecac-d011-4d7e-bea8-f6cf79d93646" />

<img width="1280" height="800" alt="4a2" src="https://github.com/user-attachments/assets/80f57241-c145-4c90-98c9-2b24a161e40f" />

<img width="1280" height="800" alt="4a3" src="https://github.com/user-attachments/assets/d4d38955-3002-4225-b9c2-6efa7e1a5d0c" />

<img width="1280" height="800" alt="4a4" src="https://github.com/user-attachments/assets/f7d2841b-588d-495c-be9d-110dc7fe5899" />



b. Jalankan script tersebut sebagai berikut :



5. Jobs
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik,
kemudian menyimpan tanggal dan jam pada file hasil.

b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di
background sebagai berikut :

c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background

d. Stop program background dengan utilitas kill

6. History
a. Ganti nilai HISTSIZE dari 1000 menjadi 20

b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan

c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer

d. Ulangi instruksi pada history bufer nomor 150

e. Ulangi instruksi dengan prefix “ls”
