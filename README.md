# Instalasi Environment virtual (veny) Dan Nonaktifkan di Visual code

# Modul 2

# Pertama
* program meminta pengguna untuk memasukan 3 bilangan menggunakan input(), dan hasilnya disimpan di dalam variabel bilangan1, bilangan2, dan bilangan3. kemuadian, program memerikasa tiga kondisi menggunakan if:
# Kedua
* memeriksa apakah bilangan1, bilangan2, dan bilangan3 ?. jika benar, maka bilangan1 yang terbesar
# Ketiga
jika kondisi pertama salah, maka memeriksa apakah bilangan2 lebih besar dari pada bilangan1 dan bilangan3. jika benar, maka bilangan2 yang terbesar. jika kedua kondisi kedua sebelumnya salah, maka bilangan3 yang terbesar. hasil bilangan terbesar menggunakan pernyataan print.

# OUTPUTNYA
![Screenshot (77)](https://github.com/RadityaTansyLizara/labs02py/assets/147571863/7e2c3169-db58-48c0-8e81-24223c5c84bd)

* Dengan demikian, program akan menentukan bilangan terbesar di antara ketiga bilangan yang dimasukkan oleh pengguna dan mencetaknya ke layar.

  # Modul 3
# LATIHAN1
* import random: Ini adalah pernyataan untuk mengimpor modul random, yang digunakan untuk menghasilkan bilangan acak.
* n = int(input("Masukkan nilai n: ")): Program ini meminta pengguna untuk memasukkan sebuah nilai n melalui keyboard. Nilai tersebut kemudian dikonversi menjadi integer (bilangan bulat) dan disimpan dalam variabel n.
* count = 0: Variabel count diinisialisasi dengan nilai 0. Variabel ini akan digunakan sebagai penghitung untuk melacak berapa kali bilangan acak telah dihasilkan.
* while count < n:: Ini adalah awal dari loop while. Kode dalam loop ini akan dieksekusi selama nilai count kurang dari n.
* random_number = random.random(): Ini adalah pernyataan yang menghasilkan sebuah bilangan acak antara 0 dan 1 dengan menggunakan fungsi random.random() dari modul random. Hasilnya disimpan dalam variabel random_number.
* if random_number < 0.5:: Program memeriksa apakah random_number kurang dari 0.5. Jika benar, maka bilangan tersebut akan dicetak.
* print(random_number): Jika bilangan acak memenuhi kondisi sebelumnya (kurang dari 0.5), maka bilangan tersebut akan dicetak ke layar.
![WhatsApp Image 2023-11-06 at 15 16 22](https://github.com/RadityaTansyLizara/labs02py/assets/147571863/b52964f2-5f5a-4672-8d21-6095b99dca03)

# LATIHAN2
* max_number = None: Variabel max_number diinisialisasi dengan nilai None. Ini digunakan untuk menyimpan bilangan terbesar yang akan dicari nantinya.
* while True:: Ini adalah awal dari loop while yang akan berjalan tanpa henti (selama kondisinya True), sehingga program akan terus meminta pengguna untuk memasukkan bilangan.
* input_number = float(input("Masukkan angka (0 untuk berhenti): "): Program meminta pengguna untuk memasukkan sebuah bilangan desimal. Bilangan yang dimasukkan oleh pengguna disimpan dalam variabel input_number setelah dikonversi menjadi float (bilangan riil).
* if input_number == 0:: Program memeriksa apakah bilangan yang dimasukkan oleh pengguna adalah 0. Jika iya, maka program akan keluar dari loop while dengan pernyataan break, sehingga pengguna dapat menghentikan input dengan memasukkan 0.
* if max_number is None or input_number > max_number:: Program memeriksa apakah nilai max_number saat ini adalah None (belum ada bilangan yang dimasukkan sebelumnya) atau apakah input_number lebih besar dari max_number yang sebelumnya. Jika salah satu kondisi ini terpenuhi, maka max_number akan diubah menjadi input_number.
![WhatsApp Image 2023-11-06 at 15 16 22 (1)](https://github.com/RadityaTansyLizara/labs02py/assets/147571863/27530b32-71df-48b8-a07b-dea65339a413)

# LATIHAN3
* total_keuntungan += modal_awal * 0.01: Pada bulan 3, laba 1% dari modal awal ditambahkan ke total_keuntungan.
* total_keuntungan += modal_awal * 0.05: Pada bulan 5, laba 5% dari modal awal ditambahkan ke total_keuntungan.
* total_keuntungan += modal_awal * 0.03: Pada bulan 8, laba 3% dari modal awal ditambahkan ke total_keuntungan.
* print("Total Keuntungan selama 8 bulan adalah: Rp", total_keuntungan): Ini adalah perintah cetak yang digunakan untuk mencetak hasil perhitungan total keuntungan selama 8 bulan ke layar. Pesan ini juga mencantumkan jumlah keuntungan dalam bentuk mata uang (Rupiah).
![WhatsApp Image 2023-11-06 at 15 16 22 (2)](https://github.com/RadityaTansyLizara/labs02py/assets/147571863/242291a3-1920-4e25-809b-7bf086ff06f4)

# PERULANGAN
Latihan 1
* kolom = baris: Variabel kolom juga diatur sama dengan baris. Ini berarti bahwa segitiga yang dihasilkan akan memiliki jumlah kolom yang sama dengan jumlah baris.
* Loop pertama (for bar in range(baris)) digunakan untuk mengiterasi melalui setiap baris dalam segitiga. Variabel bar akan berubah dari 0 hingga 9 (karena baris diatur ke 10).
* Loop kedua (for col in range(kolom)) digunakan untuk mengiterasi melalui setiap kolom dalam segitiga. Variabel col akan berubah dari 0 hingga 9.
* tab = bar + col: Variabel tab digunakan untuk menghitung jumlah baris dan kolom saat ini. Ini akan menghasilkan nilai yang bertambah secara berurutan dengan setiap baris dan kolom yang ditambahkan.
  ![image](https://github.com/RadityaTansyLizara/labs02py/assets/147571863/07133278-8246-4cd2-a0d0-34a9b1bba96d)

Latihan 2
![image](https://github.com/RadityaTansyLizara/labs02py/assets/147571863/22148a8f-12ba-4f71-a026-e8ecb1c0ba74)
