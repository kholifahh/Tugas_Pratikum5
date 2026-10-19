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

<img width="1280" height="800" alt="VirtualBox_kholifahkh_19_10_2026_21_27_05" src="https://github.com/user-attachments/assets/50a5f7a5-8588-4fdd-b254-531d3995c5f4" />


<img width="1280" height="800" alt="VirtualBox_kholifahkh_19_10_2026_21_29_09" src="https://github.com/user-attachments/assets/5b69eba7-04a7-4ca3-a1bd-6a008194632a" />


<img width="1280" height="800" alt="VirtualBox_kholifahkh_19_10_2026_21_29_26" src="https://github.com/user-attachments/assets/3164892f-0222-48d5-b30a-518454b7a0bf" />



5. Jobs

   
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik,
kemudian menyimpan tanggal dan jam pada file hasil.


<img width="1280" height="800" alt="5a1" src="https://github.com/user-attachments/assets/abbe2a3f-2983-4507-bd55-f8ca2d8b849d" />


b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di
background sebagai berikut :


<img width="1280" height="800" alt="5b" src="https://github.com/user-attachments/assets/7a31ecb3-db01-4c77-b7fb-f715a481486a" />


c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background


<img width="1280" height="800" alt="5c" src="https://github.com/user-attachments/assets/c7d27e7e-9a1a-4bc0-afd1-bbb64d79f497" />


d. Stop program background dengan utilitas kill



<img width="1280" height="800" alt="5d" src="https://github.com/user-attachments/assets/4174f9a2-7d23-444d-a274-bffc473ee968" />


6. History

   
a. Ganti nilai HISTSIZE dari 1000 menjadi 20


<img width="1280" height="800" alt="6a" src="https://github.com/user-attachments/assets/06c552e7-d8be-42e6-b9cb-24087974efe8" />


b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan


<img width="1280" height="800" alt="6b" src="https://github.com/user-attachments/assets/b3bc2582-4fe9-4ce3-b31e-c9872effc396" />


c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer


<img width="1280" height="800" alt="6c" src="https://github.com/user-attachments/assets/10888fcc-7962-4b03-a9a2-b7c5d409c80a" />


d. Ulangi instruksi pada history bufer nomor 150


<img width="1280" height="800" alt="6d" src="https://github.com/user-attachments/assets/1ed4318c-a0ea-4b69-bdfd-db5b084fac57" />


e. Ulangi instruksi dengan prefix “ls”


<img width="1280" height="800" alt="6e" src="https://github.com/user-attachments/assets/79bf117f-bb55-440d-b1e0-e6f89f45f8dd" />


