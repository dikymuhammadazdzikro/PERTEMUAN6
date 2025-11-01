# Latihan 1: perulangan bertingkat (nested loop) (Python) Penjelasan Tugas Tugas ini bertujuan untuk membuat program Python yang dapat perulangan bertingkat (nested loop) untuk membuat pola angka. Penjelasan Kode Program: Struktur Perulangan:

Loop luar (for i in range(10)): mengontrol baris (0 sampai 9) Loop dalam (for j in range(10)): mengontrol kolom (0 sampai 9) Proses yang terjadi:

i = 0 (baris pertama): print() pindah baris print(i + j, end=' '): Mencetak hasil penjumlahan dengan spasi (bukan enter) print(): Pindah ke baris baru setelah selesai satu baris lengkap

<img width="253" height="263" alt="Bukti_run_Latihan1 py" src="https://github.com/user-attachments/assets/6a515219-fdf0-4122-9f63-74d6eafc932a" />


# Latihan 2: Menghasilkan dan mencetak angka acak (Python) Penjelasan Tugas Tugas ini bertujuan untuk membuat program Python yang dapat Menghasilkan dan mencetak angka acak antara 0-1 sebanyak n kali, tetapi hanya angka yang kurang dari 0.5 yang dihitung dan dicetak. Penjelasan Kode Program:

Input: Meminta user memasukkan jumlah n Inisialisasi: Variabel jumlah di-set ke 0 sebagai counter Perulangan While: Loop berjalan selama jumlah < n Setiap iterasi menghasilkan angka acak antara 0-1 menggunakan random.random() Jika angka < 0.5, maka: Angka dicetak Counter jumlah bertambah 1 Jika angka ≥ 0.5, loop terus berjalan tanpa mencetak dan tanpa menambah counter

<img width="256" height="214" alt="Bukti_run_Latihan2 py" src="https://github.com/user-attachments/assets/d890b193-0184-48eb-a8ec-09f489247eaf" />

