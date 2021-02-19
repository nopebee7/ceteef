## app.cybersidn.com (_REDUCE CTF) WriteUp.

#### HEXER
Soal :
```
Hi I'm hexer and i will hex you
49 6d 20 68 65 78 65 72
```
Ya... ini adalah hexadecimal.  
`FLAG : REDUCE{Im hexer}`

#### KODE STANDAR AMERIKA
Soal :
```
65 109 101 114 105 99 97 110 32 83 116 97 110 100 97 114 100 32 67 111 100 101 32 102 111 114 32 73 110 102 111 114 109 97 116 105 111 110 32 73 110 116 101 114 99 104 97 110 103 101
```
*Kode Standar Amerika* atau bahasa inggris nya adalah *American Standard Code*. Orang orang biasa menyebutnya dengan nama *ASCII*.  
`FLAG : REDUCE{American Standard Code for Information Interchange}`

#### PESAN DARI NEGERI ROBOT
Soal :
```
ROBOTROBOTrobotrobotROBOTrobotrobot ROBOTROBOTrobotROBOTROBOTROBOTROBOT ROBOTrobotROBOTROBOTROBOTROBOTROBOT ROBOTROBOTROBOTROBOTrobotrobotROBOT ROBOTROBOTrobotROBOTROBOTROBOTROBOT ROBOTROBOTROBOTrobotROBOTrobotROBOT ROBOTrobotROBOTROBOTROBOTROBOTROBOT ROBOTROBOTrobotROBOTROBOTrobotrobot ROBOTROBOTrobotROBOTrobotrobotROBOT ROBOTROBOTrobotROBOTrobotROBOTROBOT ROBOTROBOTrobotrobotROBOTrobotROBOT ROBOTrobotROBOTROBOTROBOTROBOTROBOT ROBOTROBOTrobotrobotrobotROBOTrobot ROBOTROBOTrobotROBOTrobotrobotROBOT ROBOTROBOTrobotROBOTROBOTROBOTrobot ROBOTROBOTrobotrobotrobotrobotROBOT ROBOTROBOTROBOTrobotrobotROBOTrobot ROBOTROBOTROBOTROBOTrobotrobotROBOT
Clue : http://gg.gg/ImRobot
```
Ini akan sedikit ribet, karena kalian harus menganti kata *ROBOT* menjadi 1 dan kata *robot* menjadi 0. Jika di susun ini akan menjadi bilangan biner.  
`FLAG : REDUCE{do_you_like_binary}`

#### SPAM BANGET
Soal :
```
w dapet pesan nih dari sang heker, namanya cesar chip8. Katanya sih ada flagnya di dalem situ.
https://app.cybersidn.com/ctf/files/spam.txt
```
Di soal kita udah dapet clue kalo ini adalah [Caesar](https://www.dcode.fr/caesar-cipher). Kalian bisa decode isi di dalam link itu dengan [Caesar](https://www.dcode.fr/caesar-cipher), nanti bakal ada hasil yang berawalan *Dear friend*. Nah disini saya kepikiran bahwa ini adalah salah satu chiper dari [spamimic](https://www.spammimic.com/).  
`FLAG : REDUCE{Fl4g_1s_Fl46}`

#### PESAN ANEH
Soal :
```
Hi, aku sky. Pada suatu hari aku berpas - pasan dengan teman lamaku, tale. Dia tiba - tiba memberiku sebuah kertas yang berisikan pesan 
"id2pNYh 303 EuL"
dia juga memberiku 4 batang kayu
```
Jika kita rangkai kedua nama dari teman itu, itu akan mengarahkan kepada salah satu chiper yaitu [scytale](https://dencode.com/cipher/scytale) dan dengan key 4.  
`FLAG : REDUCE{iN3EdY0u2h3Lp}`

#### GARIS DAN TITIK
Soal :
```
longdahs verylongdahs dits dahs dits tridits dits dahs dits dahs dits verylongdahs dahs doubldits dits doubldits dahs dits doubldits
```
Dalam bahasa inggris *dash* adalah *-* dan *dits* adalah *.*, Kalian tinggal artikan kalimat soal itu. *longdash* adalah *--*, *verylongdash* adalah *---*, dst...  
`FLAG : REDUCE{morsecodeini}`

#### BASE32 EENCODING
Soal :
```
[01010, 10001, 10100, 00011, 00110, 10100, 10001, 10100]
[01101, 11001, 10010, 00011, 00000, 11011, 01010, 10011]
[01110, 10001, 11001, 00011, 00010, 10011, 10010, 00111]
flag: REDUCE{hasil encoding}
clue : ttps://en.wikipedia.org/wiki/Base32
```
Menurut saya ini adalah sebuah jebakan. Kalian bisa decode bilangan biner tersebut ke dalam teks,, tapi tunggu itu bukanlah flag nya. Untuk mendapatkan flag kalian harus mengencode string tersebut ke *Base32*    
`FLAG : REDUCE{KRUDGURUNZSDA3KTORZDCTSH}`

#### TROUBLESOME
Soal :
```
Pada bulan september ini, admin banyak menerima spam message yang tidak penting.
Admin kelelahan jika haruS membaCanya berulang kalI, bolak balIk hanya untuk sekedar membuka pesan tersebut.
Akhirnya sang admin merekrut seseorang bernama desi (Untuk sekedar memantau pesan masuk, dan memberitahu jika ada sesuatu yang penting), dikabarkan dia memahami basic-basic tentang surat menyurat.
Suatu hari disaat ia mengantuk, iya menyadari bawah ada pesan yang amat sangat penting.
Namun sayangnya saat itu sudah malam, dan diapun tak sengaja tertidur di meja kerjanya.
Keesokan harinya, dia terkejut. Dan langsung sadar bahwa semalam dia menemukan sebuah pesan penting.
Namun lupa letaknya dimana, diapun memanggil teman untuk membantunya menemukan pesan penting tersebut.
Dan temannya ialah anda.

Link Gambar : https://app.cybersidn.com/ctf/files/01.txt
Clue : https://app.cybersidn.com/ctf/files/27 94 011 611 64 611 021 611
```
Jika kita klik gambar gmail itu kita akan diarahkan ke link gambar diatas. Isinya hanyalah sebuah bilangan biner yang sangat panjang, dan jika kita decode hasil nya seperti korup.Emm disini saya coba untuk kembali membaca soalnya secara teliti. Disana ada sebuah ejaan huruf besar yang membentuk kata *ASCII*, tapi.. saya gatau maksudnya apa :D. Oke disni saya kembali membaca nya lagi.Disana dikatakan *haruS membaCanya berulang kalI, __BOLAK BALIK__* nah disini saya kepikiran untuk mencoba men reverse text binary itu sebelum di decode. Dan ternyata itu berhasil :D, dan hasilnya adalah sebuah kata yang harus kita reverse lagi.Hasil reverse nya adalah chiper dari *spamimic*. Kita decode lalu reverse terus sampe menemukan flag :D.  
`FLAG : R-27CTF{S0m3_Tr1cky_Ch4ll4nge}`


### Copyright 2021 nopebee7(@)skullxploit
