# TASK-SETUP-ANACONDA-UV

Nama : **M Sandi Firmansyah**

Absen : **10.006.DB2025**

Tempat Tinggal : **Kab.Tanjung Jabung Barat, Prov.Jambi**

## Halo Sahabat Eco Techno Leader & Sobat Semua! 👋
Selamat datang di **TASK-SETUP-ANACONDA-UV!** 🎉 Seneng banget kita bisa belajar bareng di sini. Repo ini aku bikin khusus buat tugas mingguan dan jadi panduan lengkap buat kita semua yang pengen bisa setup Anaconda UV di laptop. Sama kayak kalian, aku juga masih belajar dan pemula banget di dunia coding. Jadi, semoga kita bisa makin jago dan kece di dunia data dan coding ya! Yuk, langsung aja kita ikuti langkah-langkahnya!
## Kenalan Sama Anaconda dan Cara Instalnya

**🐍 Anaconda: Tas Ransel Super Lengkap buat Data Science!**
Bayangin aja Anaconda itu kayak tas ransel super lengkap buat kamu yang suka banget sama data science dan machine learning. Di dalam tas ini, udah ada semua "alat" dan "buku" yang kamu butuhkan. Mulai dari buat bikin program AI, ngitung statistik, bikin grafik data yang keren, sampai bikin website pun bisa. Jadi, kamu gak perlu repot nyari atau nginstal satu per satu. Semuanya udah siap pakai, tinggal ambil dan jalan!

**🛠️ Conda: Manajer Pribadi si Anaconda!**
Nah, kalau Conda itu manajer pribadinya si Anaconda. Dia ini kayak Play Store di HP kamu. Kalau kamu mau nambah aplikasi baru (paket), buku-buku baru (library), atau bahkan mau ganti versi Python yang kamu pakai, tinggal bilang aja ke Conda. Dia yang bakal ngurusin dan nyiapin semuanya buat kamu. Praktis, kan?

**🌱 UV: "Ruangan" Khusus buat Proyekmu!**
Terakhir, ada UV. Ini bukan nama planet baru ya, tapi cuma nama buat "ruangan" khusus di dalam Anaconda. Jadi, kalau kamu punya banyak proyek data science, kamu bisa bikin "ruangan" UV sendiri buat tiap proyek. Di ruangan ini, kamu bisa masukin alat-alat (kayak Python, Jupyter, Numpy, dll.) yang pas buat proyek itu aja. Kenapa penting? Biar alat-alat di proyek satu gak campur aduk atau bikin masalah sama alat-alat di proyek lain. Jadi, setiap proyek punya "rumah" sendiri yang rapi dan terorganisir.

Gimana, sekarang udah kebayang kan bedanya Anaconda, Conda, sama UV? Mereka ini trio yang bakal bikin petualanganmu di dunia data science jadi lebih gampang dan menyenangkan! Yuk, kita lanjut ke bagian instalasi!


. Download Anaconda
Pertama yang harus kita lakukan adalah download anaconda dan buka website resmi Anaconda (pastikan wajib website resmi ya).

Buka situs resminya di sini guys : 👉 https://www.anaconda.com/products/distribution

Pilih sesuai OS (Windows/Mac/Linux) , kali ini aku pilih windows. Teman-teman bisa sesuaikan dengan OS masing-masing.

download-anaconda

Do :

![Screenshot 2025-06-14 205109](https://github.com/user-attachments/assets/1b410ab5-e2a7-47ac-8b81-6df66397defb)


    - Wajib Download di website resmi

    - Di web resmi dijamin dapat versi asli dari Anaconda, yang udah diverifikasi.
Dont :

    - Kalau kamu download dari sumber yang gak jelas atau situs pihak ketiga, bisa jadi file-nya udah dimodifikasi dan disisipi malware, spyware, atau virus yang bahaya banget buat laptop kamu 😱. 

    - File dari luar bisa aja palsu, atau udah di-crack yang bikin sistem kamu gak stabil dan rawan error.
2. Install Anaconda
🐍 Kenapa Install ANACONDA? Sebagai pemula anaconda itu ibarat = Paket Komplit 📦 Udah langsung bawa Python + ratusan tools penting buat data science, machine learning, statistik, dll. Cocok banget untuk pemula karena install sekali, dapet semua.

Setelah sebelumnya kita berhasil download anaconda di website resmi
Maka bisa langsung download ➡️ Install ➡️ Klik Next terus sampe Finish
Berikut Tutorialnya :

![Screenshot 2025-06-12 2051010](https://github.com/user-attachments/assets/f8f3d794-b77f-4f09-9eaf-9b06564ec669)

![Screenshot 2025-06-13 220121](https://github.com/user-attachments/assets/3c6e1bd4-53d7-4419-a429-350943604045)

![Screenshot 2025-06-13 220210](https://github.com/user-attachments/assets/51655093-80ef-4a02-9bd4-dcda67277a51)

![Screenshot 2025-06-13 220230](https://github.com/user-attachments/assets/b9bcefe6-e257-4818-9133-80fe427bc3cd)


eeittss, aku mau kasih tau sesuatu sebelum lanjut ke tutorial. Pas kamu Next ke tahap berikutnya saat install Anaconda, pasti nemu opsi: -✅ "Add Anaconda to my PATH environment variable" Nah, ini penting banget untuk dipahami:

Do's :

    - kalau kamu mau anaconda bisa diakses di terminal manapun kamu bisa menceklisnya, ya. Ini bisa dilakukan atau tidak dilakukan, tergantung kebutuhan kamu.
Don'ts:

    - jika kamu merasa tidak memerlukannya, maka tidak perlu di ceklis (opsional)

![Screenshot 2025-06-13 220246](https://github.com/user-attachments/assets/b51a8062-d17e-4e74-afad-336e06310f71)


Do's: Tetap di direktori yang otomatis dipilih system

Don'ts: Jangan ubah direktori

![Screenshot 2025-06-13 221940](https://github.com/user-attachments/assets/2cb220c8-46a4-4849-85fd-3a4ed3b65cc9)

![Screenshot 2025-06-13 222016](https://github.com/user-attachments/assets/965e3af6-7322-4d3c-b25d-980a389511d5)


Berhasil dan Proses instalasi sudah selesai dilakukan.


Verifikasi Anaconda Teristall
Teman-teman harus membuka CMD alias Command Prompt bisa dilakukan langsung dengan :

Windows + R

ketik : conda --version

![Screenshot 2025-06-13 223836](https://github.com/user-attachments/assets/0b1a1d95-5b7e-4c80-96d2-3da9ec20fb97)

cmd-berhasil

Kalau muncul conda 24.9.2 artinya Anaconda SUDAH TERINSTALL dengan benar dan PATH-nya aman.

APA ITU PATH?

PATH itu kayak daftar jalan tol tempat Windows nyari file executable kayak python, conda, atau jupyter.

Kalau kamu ngetik conda di CMD, Windows akan nyari conda.exe di semua folder yang ada di dalam daftar PATH.

Jadi, kalau Anaconda belum ditambahkan ke PATH, CMD gak bakal tahu harus nyari conda ke mana ➡️ muncullah error.

Tapi tenang! Bukan berarti belum terinstall — kamu masih bisa akses lewat Anaconda Prompt.

Atau kamu bisa tambahkan manual, Kenapa?? Hal ini agar kita bisa manggil anaconda dari terminal mana saja. Nah caranya adalah :

    - Buka Start Menu → cari "Environment Variables" → klik Edit the system environment variables.

    - Klik Environment Variables...

    - Di bagian User variables → klik Path → klik Edit.

    - Klik New dan tambahin ini :

![Screenshot 2025-06-14 221957](https://github.com/user-attachments/assets/322a1ddc-ef49-484c-87b9-d0aa9b0d6a9f)


    - Klik OK semua sampe keluar.
Do's:

    - Restart CMD atau buka yang baru.
Don'ts:

    - Jangan menghapus PATH penting lainnya.

    - Hati-hati saat edit variabel lingkungan.

    - Jangan asal tambahin folder lain dari dalam Anaconda ke PATH
