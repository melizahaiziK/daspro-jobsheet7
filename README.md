PERTANYAAN PERCOBAAN 1

1. Sebutkan dan tunjukkan masing-masing komponen perulangan FOR pada kode program
Percobaan 1!
jawaban : 1. (int i = 1;
          2. i <= 10; i++)
2. Mengapa variabel tertinggi diinisialisasi 0 dan terendah diinisialisasi 100? Apa yang
terjadi jika variabel tertinggi diinisialisasi 100 dan terendah diinisialisasi 0?
jawaban : variable tertinggi diinisialisasi 0 karena tidak ada nilai yang lebih kecil dari 0 jadi ketika mulai menginput maka nilai dimulai dari lebih dari 0 dan kurang dari 100. Variable terendah diinisialisasi 100 karena tidak ada nilai yang lebih besar dari 100, jadi ketika kita menginput maka harus menuliskan nilai yang dibawah 100.

Jika variabel tertinggi dibalik maka tidak ada nilai yang lebih besar dari 100, jadi tertinggi tidak akan pernah berubah atau hasilnya akan tetap 100. Jika variable terkecil dibalik maka tidak ada nilai yang lebih kecil dari 0, jadi terendah tidak akan pernah berubah dan hasilnya tetap 0.
3. Jelaskan fungsi dan alur kerja dari potongan kode berikut!
 if (nilai > tertinggi) {
            tertinggi = nilai; 
        }

        if (nilai < terendah) {
            terendah = nilai;
        }
jawaban : baris pertama berfungsi untuk memeriksa nilai yang kita input apakah nilainya   itu lebih besar dari nilai tertinggi. Baris kedua befungsi untuk memeriksa nilai yang kita inputkan apakah nilainya itu lebih kecil dari nilai terendah.

PERTANYYAN PERCOBAN 2
1. Pada potongan kode berikut, tentukan maksud dan kegunaan dari sintaks berikut:
a. nilai < 0 || nilai > 100
b. continue
jawaban : a. kode tersebut bermaksud jika nilai kurang dari 0 dan lebih dari 100, kegunaannya adalah untuk memeriksa nilai inputan, jika nilai kurang dari 0 dan lebih dari 100 maka program akan menampilkan input salah dan akan meminta untuk menginputkan kembali.
b. continue digunakan untuk melewati (skip) iterasi saat ini (1
iterasi saja) dan melanjutkan ke iterasi berikutnya. Jika inputan bernilai lebih dari yang ditentukan maka program akan meng skip hasil dan mengulangi pertanyaannya.
2. Mengapa sintaks i++ dituliskan di akhir perulangan WHILE? Apa yang terjadi jika posisinya
dituliskan di awal perulangan WHILE?
jawaban :
i++ digunakan untuk menaikkan nilai variabel penghitung setelah satu kali perulangan selesai.
Dengan menulis i++ di akhir loop, kita memastikan bahwa semua perintah di dalam loop dijalankan dulu, baru kemudian nilai i bertambah, dan juga agar memunculkan output yang terurut. Jika i++ ditaruh diakhir Maka nilai penghitung akan naik terlebih dahulu sebelum isi perulangan dijalankan. Akibatnya, data pertama akan terlewat, dan jumlah perulangan akan berkurang satu kali dari yang seharusnya.
3. Apabila jumlah mahasiswa yang dimasukkan adalah 19, berapa kali perulangan WHILE
akan berjalan?
jawaban : perulangan akan terus berjalan sesuai dengan jumlah mahasiswa yang dimasukkan.

PERTANYAAN PERCOBAAN 3
1. Pada penggunaan DO-WHILE ini, apabila nama pelanggan yang dimasukkan pertama kali
adalah “batal”, maka berapa kali perulangan dilakukan?
jawaban : tidak dilakukan perulangan dikarenakan jika kita suda menginputkan 'batal' maka program otomatis memberhentikan perulangan karena adanya statement break.
2. Sebutkan kondisi berhenti yang digunakan pada perulangan DO-WHILE tersebut!
jawaban : kondisi yang digunakan adalah kondisi Break.
3. Apa fungsi dari penggunaan nilai true pada kondisi DO-WHILE?
jawaban : nilai true adalah kondisi logika yang selalu bernilai benar.
jika perulangan do–while ini akan berjalan terus-menerus tanpa berhenti selama tidak menginputkan 'batal' pada inputan nama pelanggan.
4. Mengapa perulangan DO-WHILE tersebut tetap berjalan meskipun tidak ada komponen
inisialisasi dan update?
jawaban : Perulangan ini tetap berjalan terus karena kondisinya selalu bernilai true. Kondisi while(true) membuat perulangan berjalan tanpa batas Jadi, program akan terus meminta input