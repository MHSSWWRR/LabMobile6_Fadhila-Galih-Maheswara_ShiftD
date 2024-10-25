# LabMobile6_Fadhila-Galih-Maheswara_ShiftD - Tugas 6 Pertemuan 7
Praktikum Pemrograman Mobile - Tugas 6 (Pertemuan 7)
Nama        : Fadhila Galih Maheswara
Nim         : H1D022007
Shift Lama  : D  
Shift Baru  : D

# Tahapan untuk menambahkan komponen pada halaman ionic
1. Instalasi Ionic jika belum terpasang.

2. Membuat Proyek baru atau gunakan proyek yang pernah dibuat sebelumnya.

3. Pilih dan tambahkan komponen ionic yang biasa digunakan seperti Button, Card, List, atau Input.

4. Contoh menambahkan Ionic Card dengan tombol di dalamnya:
    <ion-content>
    <!-- Menambahkan Card -->
    <ion-card>
        <ion-card-header>
        <ion-card-title>Selamat Datang</ion-card-title>
        <ion-card-subtitle>Mobile Programming</ion-card-subtitle>
        </ion-card-header>

        <ion-card-content>
        <p>Ini adalah contoh komponen Ionic yang menampilkan informasi secara kreatif.</p>
        <!-- Menambahkan Button -->
        <ion-button expand="full" color="primary">
            Klik Saya
        </ion-button>
        </ion-card-content>
    </ion-card>
    </ion-content>

5. Menambahkan gaya menggunakan CSS.
    ion-card {
    --background: #f4f4f4; /* Warna latar belakang card */
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    }

    ion-button {
    --background: #3880ff;
    font-size: 1.2em;
    }

6. Jalankan program dengan 'ionic serve' atau 'ionic s'.

# Screenshot
<div style="display: flex; justify-content: space-between;">
  <img src="src/assets/Screenshot 2024-10-24 212755.png" width="19%">
</div>
