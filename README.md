nama : syarla assyurah
nim  : 09030182428002

1. a.Eksekusi profile
![Screenshot 2025-04-12 060233](https://github.com/user-attachments/assets/2c199be3-0bb5-4224-a3b8-46b1963056f6)
b. Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap file tersebut, cantumkan instruksi echo.
![Screenshot 2025-04-12 061510](https://github.com/user-attachments/assets/c16edbd6-7790-4656-96de-2ba0117e6627)
![Screenshot 2025-04-12 061756](https://github.com/user-attachments/assets/fca4b73a-3744-4ed9-8974-fba0c75ab2a6)
![Screenshot 2025-04-12 061851](https://github.com/user-attachments/assets/3358412d-32ae-411d-a5d3-568371bb42f0)
![Screenshot 2025-04-12 061919](https://github.com/user-attachments/assets/a91d466f-7a65-415e-80ef-ef6b9c8aae1e)

c.instruksi su syarla dan exit
![Screenshot 2025-04-12 070528](https://github.com/user-attachments/assets/be2892d3-115b-41ea-be5a-2dc3174707d9)
![Screenshot 2025-04-12 070613](https://github.com/user-attachments/assets/f0ea33a6-75fe-4a29-a2c2-c347e8a6219f)
su syarla:
Masuk ke user syarla tanpa login shell.
Hanya menjalankan .bashrc.
Tidak memuat environment seperti PATH atau variable login lainnya.
su - syarla:
Masuk ke user syarla dengan login shell penuh.
Menjalankan /etc/profile, .bash_profile, dan konfigurasi login lainnya.
Lingkungan user disiapkan seperti saat login langsung.

2. a.Edit file .bash_profile, ganti prompt PS1 dengan ‘>’.
   ![Screenshot 2025-04-12 071806](https://github.com/user-attachments/assets/2e399841-dea7-4d3b-9c6b-1066bfe0eb56)
   b.Eksperimen hasil PS1
   ![Screenshot 2025-04-12 071941](https://github.com/user-attachments/assets/0f1f4619-c903-4001-8f7a-50eb9a5252d4)

3.longout
![Screenshot 2025-04-12 072521](https://github.com/user-attachments/assets/8a4002b6-7669-475b-a9e4-4c97fb144040)

4.Bash script
hasil jalankan script tersebut : -$ ./p1.sh ; ./p3.sh ; ./p2.sh
![Screenshot 2025-04-12 074231](https://github.com/user-attachments/assets/da440f4a-81d3-4ac8-97bc-6d6e12bede98)
jalankan ./p1.sh
![Screenshot 2025-04-12 072938](https://github.com/user-attachments/assets/e519a46c-dd00-4ddb-8866-0ff51ed1db42)
Jalankan p1.sh, lalu p2.sh & p3.sh
![Screenshot 2025-04-12 073610](https://github.com/user-attachments/assets/7aad9a12-1ae8-4c61-ad6d-b6b08d2cb24b)
Jalankan p1.sh dan p3.sh
![Screenshot 2025-04-12 073633](https://github.com/user-attachments/assets/454db3a6-f5f4-410f-840e-82d998e44737)

5.jobs
hasil program yg di jalankan
jobs
![Screenshot 2025-04-12 080157](https://github.com/user-attachments/assets/d1d56ee9-a53e-4e3c-aa53-a3dddc4811d1)
find / -print > files 2>/dev/null &
![Screenshot 2025-04-12 081912](https://github.com/user-attachments/assets/74741850-5f7c-4405-839d-f8eaef149e70)
jobs
![Screenshot 2025-04-12 081932](https://github.com/user-attachments/assets/8d2512a5-80ad-4be7-8ee0-4f23ff4f0d58)
fg %1
![Screenshot 2025-04-12 082130](https://github.com/user-attachments/assets/c3bcbe7f-4113-48ef-b913-d5d2f73df6bf)
bg
![Screenshot 2025-04-12 082230](https://github.com/user-attachments/assets/4f38e567-d433-446a-a699-a4358efe8ef4)
ps x
![Screenshot 2025-04-12 083729](https://github.com/user-attachments/assets/a16f737e-43f9-4e61-9de9-b5b5b8d6adaf)
kill [Nomor PID] 
![Screenshot 2025-04-12 083810](https://github.com/user-attachments/assets/aca1656a-6227-4faa-8606-487f679f13b1)

6.history
a. Ganti nilai HISTSIZE dari 1000 menjadi 20
![Screenshot 2025-04-12 091823](https://github.com/user-attachments/assets/ee3924f3-a206-4801-97ae-b9c8c328a7cf)
history
![Screenshot 2025-04-12 093428](https://github.com/user-attachments/assets/9c0aa6ea-8832-4a3e-bd28-c59520ce69bb)
b.Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir dilakukan
   -$ !-5
   ![Screenshot 2025-04-12 095424](https://github.com/user-attachments/assets/8654896f-ad14-48ec-91f0-0994f27eb328)
c.Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer
   -$ !!
   ![Screenshot 2025-04-12 095523](https://github.com/user-attachments/assets/39ae0e9a-9776-486e-80fa-f9bc6386629a)
d.Ulangi instruksi pada history bufer nomor 150
   -$ !150
   ![Screenshot 2025-04-12 095644](https://github.com/user-attachments/assets/8201bbf3-0b4c-44c1-9be2-c52fb08e54a4)
e.Ulangi instruksi dengan prefix “ls”
   -$ !ls
   ![Screenshot 2025-04-12 095651](https://github.com/user-attachments/assets/e978e2bc-4a13-4553-ab54-7830535c2893)









