# Data Encryption Standard

Penjelasan tiap line :
001 - 002 : Header C++ yang dipakai
003       : namespace
004 - 015 : deklarasi untuk menyimpan data ( 32, 48, 56 bit)
016 - 019 : Algoritma XOR
020 - 025 : Merubah Binary 2 bit menjadi Decimal
026 - 033 : Merubah Binary 4 bit menjadi Decimal

035 - 619 : Function Encrypt
035 - 058 : Permutasi PC-1 pada Key
060 - 071 : Menampilkan Hasil Permutasi PC-1 pada Key
072 - 132 : Melakukan Left Shift pada C ke i dan D ke i sejumlah no_shift
133 - 189 : Permutasi PC-2 pada Key[1] sampai Key[16]
190 - 200 : Menampilkan Hasil Permutasi PC-2 pada Key[1] sampai Key[16]
203 - 217 : Permutasi IP pada Plain Text
219 - 221 : Membuat L0
222 - 224 : Membuat R0
225 - 230 : Menampilkan L0
231 - 237 : Menampilkan R0
240 - 242 : Membuat L ke i+1
245 - 303 : Melakukan ekspansi pada R ke i-1
305 - 310 : Menampilkan hasil dari ekspansi pada R ke i
311 - 316 : Menampilkan Key ke i (Karena Key akan dipakai untuk XOR dengan hasil ekspansi, Key dimunculkan agar proses mencocokan secara manual lebih mudah)
317 - 323 : Melakukan XOR pada K ke i dengan R ke i-1
324 - 329 : Menampilkan hasil XOR
331 - 337 : Array Sbox S1
338 - 344 : Array Sbox S2
345 - 351 : Array Sbox S3
352 - 358 : Array Sbox S4
359 - 365 : Array Sbox S5
366 - 372 : Array Sbox S6
373 - 379 : Array Sbox S7
380 - 386 : Array Sbox S8
388 - 405 : Proses SBox
      392 : Mengubah Biner 2 bit menjadi Desimal
      393 : Mengubah Biner 4 bit menjadi Desimal
412 - 495 : Mengubah Output dari Sbox (desimal) menjadi biner
496 - 502 : Menampilkan Output dari Sbox
504 - 545 : Permutasi P terhadap Hasil dari Sbox ( F(R ke i, K ke i))
546 - 551 : Menampilkan F(R ke i, K ke i)
557 - 559 : Melakukan XOR pada L ke i-1 dengan F(R ke i, K ke i) --> mendapatkan R ke i
560 - 565 : Menampilkan R ke i
570 - 586 : Menampilkan L ke i dan R ke i
588 - 592 : Menggabungkan R ke 16 dengan L ke 16
594 - 609 : Inverse Permutation 
610 - 614 : Menampilkan Plain Text
615 - 619 : Menampilkan Hasil ( Chiper Text)

623 - 630 : Main Program

