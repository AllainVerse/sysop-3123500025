<div align="center">
  <h1 style="text-align: center;font-weight: bold">LAPORAN PRAKTIKUM 11 SISTEM OPERASI</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Achmad Risel Araby (3123500025)</strong><br>
    <strong>Danur Isa Prabutama (3123500023)</strong><br>
    <strong>Fikri Athanabil Efendi (3123500012)</strong>
  </p>
<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

## SHEDULLING ALGORITHM

### First-Come First-Serve Algorithm

Perhitungan Secara Teori :
![alt text](media/fcfs.png)

Hasil Percobaan Running Program :
![alt text](media/fcfs-1.png)

Flowchart :
![alt text](media/fcfs-2.png)

Analisa :
Algoritma FCFS adalah metode penjadwalan yang sederhana dan mudah diterapkan, namun memiliki beberapa kekurangan yang dalam waktu tunggu dan efisiensi, terutama dalam sistem yang memerlukan respons cepat. FCFS paling efektif digunakan dalam lingkungan batch processing atau sistem non-interaktif di mana semua proses memiliki waktu eksekusi yang serupa. Meskipun adil dalam urutan eksekusi, kelemahannya dalam menangani proses dengan waktu eksekusi yang bervariasi membuatnya kurang ideal untuk banyak aplikasi modern yang memerlukan penjadwalan yang lebih dinamis dan responsif.

### Shortest Job First Algorithm

Perhitungan Secara Teori :
![alt text](media/sjf.png)

Hasil Percobaan Running Program :
![alt text](media/sjf-1.png)

Flowchart :
![alt text](media/sjf-2.png)

Analisa :
Algoritma Shortest Job First adalah algoritma penjadwalan yang sederhana namun efektif untuk meminimalkan waktu tunggu rata-rata dan meningkatkan throughput sistem. Kelebihan utamanya terletak pada kemampuan untuk menyelesaikan proses dengan cepat, tetapi kekurangannya, seperti kemungkinan kelaparan proses dan kesulitan dalam memperkirakan waktu eksekusi, membatasi penerapannya. Algoritma ini paling cocok digunakan dalam lingkungan di mana semua proses dan waktu eksekusi mereka diketahui sebelumnya dan tidak ada proses baru yang datang secara dinamis. Namun, dalam konteks tertentu, seperti batch processing atau pemrosesan data dengan waktu eksekusi yang diketahui, SJF bisa menjadi pilihan yang sangat efektif.

### Round Robin Algorithm

Perhitungan Secara Teori :
![alt text](media/round-robin.png)

Hasil Percobaan Running Program :
![alt text](media/rr-1.png)

Flowchart :
![alt text](media/Round-Robin-Flowchart.jpg)

Analisa :
Algoritma Round Robin adalah metode penjadwalan CPU sederhana dan adil yang memberikan setiap proses waktu eksekusi yang sama. Meskipun dapat menyebabkan overhead switching yang tinggi dan waktu tunggu yang meningkat dalam kondisi tertentu, kelebihan dari keadilan dan responsivitas membuatnya sangat berguna dalam sistem time-sharing dan aplikasi interaktif. Oleh karena itu, pemilihan quantum time yang tepat sangat penting untuk mencapai keseimbangan antara overhead switching dan performa sistem yang optimal.
