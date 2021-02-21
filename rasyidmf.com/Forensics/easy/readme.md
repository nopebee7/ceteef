## rasyidmf.com (CTFR) Forensics Easy WriteUP

#### FIRST FORENSIC
SOal :
```
Baru pertama kali dengan Forensics yaa ? Nah coba cari flag pada sebuah gambar ini. 
Link : https://mega.nz/#!k1wEUIrC!GxdSeRZ3ZapRQPoFqRwfiyhyZoSpFnUnmD-nulltG9M
```
Disini kalian bisa mengunakan tools bernama __*strings*__ untuk mendapatkan flag.  
`FLAG : CTFR{f1r5t_f0r3ns1c5}`

#### CHECK COMMENT
Soal :
```
Pada sebuah file gambar, bisa kita tambahkan komentar juga loh, Nah coba cari tahu komentar yang di tambahkan pada gambar dibawah ini
Link : https://mega.nz/file/R84V2KrA#3GQ8jFTglK_ObMeJx_oXRGJ5SCmMDy7gBUzGZ6NgWeM
```
Untuk meilhat komentar atau info dari file, kita bisa mengunakan salah satu tools bernama __*exiftool*__  
`FLAG : CTFR{c0mm3nt_1n_1m4g3_d3t41ls}`

#### DUMP
Soal :
```
Pada gambar ini terdapat flag yang disembunyikan di dalam hex tersebut. Tolong carikan yaah :(
Hint: Pakai Hexdump untuk menyelesaikan Challenge ini
Link : https://mega.nz/#!llQi1LCB!8qybw_QiJsiVB7xMCXyRMMGcJBGshSxTohTdvsRO8xE
```
Kalian dapat mengunakan hexdump dengan command ini `hexdump -C -v file`. Nanti kalian akan menemukan flag.  
`FLAG : CTFR{h3x_dump_1n_1m4g3_f1l3}`

#### QR CODE
Soal :
```
Bantu mimin buat decode QR Code ini dong. Cuman decode doang kok :)))
Link : https://mega.nz/#!sgoUHIzb!mmQ5v0JKd1ZQRLyX73gi87z414UwgRISAWynAnjfcv4
```
Kalian bisa mengunakan tools online untuk mendecode nya di [blog.qr4.nl](https://blog.qr4.nl/Online-QR-Code-Decoder.aspx).  
`FLAG : CTFR{qi3r_c0d3}`

#### SALJU
Soal :
```
Kira kira salju di indonesia adaa gak yaa ? Moga aja ada dehh hehehe
Link : https://mega.nz/file/clwUAQgC#n2rEZ-RGSxEd2pR5jxUoEtgRp7Uzg3YJa7kvelqszTA
```
Emm, disaat kalian melihat file nya pasti kalian bingung. Karena isinya hanya sebuah tulisan biasa, Ini sebenarnya adalah teknik menyembunyikan *Teks* ke dalam *Teks*. Teknik ini bisa dilakukan dengan mengunakan salah satu tools bernama __*stegsnow*__.  
Untuk mendecode nya kalian bisa mengunakan command __*stegsnow -C file.txt*__.  
`FLAG : CTFR{s4lju_t1d4k_4d4_d1_1nd0n3s1a}`

#### TROL FACE
Soal :
```
Didalam gambar ini terdapat teks yang tersembunyi, akan tetapi kalian harus menggunakan tools agar dapat membacanya. Toolsnya bernama z....
Link : https://mega.nz/#!dth2zZqJ!eq_VqZTUyHYKTEruOxT1bvkElDsj0xcRXcjkPOe04Hs
```
Sebenarnya saya juga bingung untuk mencari flag nya dengan apa. Di soal itu ada sebuah clue bahwa tools nya berawalan dengan nama *z*. Setelah saya googling akhirnya menemukan bahwa tools nya adlah __*zsteg*__.  
`FLAG : CTFR{st3g4n0_1s_aw3s0me}`

#### FILE KORUP
Soal :
```
Bantu mimin perbaiki file korup dong, soalnya ada gambar privasi mimin
Link : https://mega.nz/file/U8AGnRYR#F_Q7Rr9SsFKzMR5S9acWje3S5F2VehheqlJA0-e3emo
```
Jika kita lihat dengan hexdump atau tools semacamnya, Bagian header dari signature file png ini ada yang hilang. Jika umumnya itu `89  50  4e  47  0d  0a  1a  0a` di file ini hanya `00 00 00 00 00 00 00`. Tentunya kita harus memperbaiki ini, kalian bisa mengunakan tools *hexedit* atau tools  lainya.  
`FLAG : CTFR{f1l3_c0rrupt_h4s_b33n_f1x3d}`

#### TEMPAT SAMPAH BERJALAN
Soal :
```
Tempat Sampah berjalan sangat banyak manfaatnya, termasuk membuang sampah sambil jalan, bukan kita nya lagi yang harus menuju ke tong sampah tersebut akan tetapi tempat nya yang berjalan sendiri. 
Link : https://mega.nz/#!4to2HZDS!2kRHDvMcmH_PFEZu5rH-5-mCLd5YkSIp07Xy0TIlH9M
```
Ini adalah metode menyisipkan file kedalam gambar. Buktinya disaat kalian cek mengunakan __*binwalk*__ ada sebuah file bernama *flag.txt* di dalamnya.  
`FLAG : CTFR{1n1_mud4h_buk4n}`

#### SAYA DAPET QR CODE
Soal :
```
Bisa tolongin ga? tolongin ya...
Link : https://mega.nz/#!qZsySCYI!HoGccQNjyBCNRE-VZjTcxF1yrGgBRxO0nue6o3TigK4
```
Ini adalah gabungan dari soal __*QR CODE*__, __*FILE KORUP*__ dan __*TEMPAT SAMPAH BERJALAN*__ di atas. Untuk pertama kali kalian jangan decode QR nya. lakukan cara seperti soal __*TEMPAT SAMPAH BERJALAN*__ untuk melihat file yang dimasukan di gambar tersebut. Isi nya adalah file gambar yang korup dan tidak bisa dibaca. Disini kalian gunakan metode seperti soal __*FILE KORUP*__ diatas, lalu kalau sudah benar signature nya gambar korup itu akan menjadi sebuah gambar QR code. Disini kalian lakukan metode yang sama seperti soal __*QR CODE*__ di atas.   
`FLAG : CTFR{w4h_h3b4T_k4Mu_b1s4_T4u_fL4g_nY4_4d4_d151N1}`


### Copyright 2021 nopebee7(@)skullxploit
