## ctf.rajawalisecteam.tech WriteUp

#### BIN & NER
Soal :
```
Saya Gottfried Leibniz adalah Penemu Kode Ini 
01000011 01010100 01000110 01010010 01010011 01010100 01111011 01100010 00110001 01101110 00110100 01110010 01111001 01011111 01100011 00110000 01100100 00110011 01111101 
cobalah Pecahkan Untuk menghargaiku
```
Kalian pasti udah paham kalau ini adalah Binary. Decode di <a target="_blank" href="https://cryptii.com/pipes/binary-to-text">cryptii.com</a><br>
`FLAG : CTFRST{b1n4ry_c0d3}`

#### OTAN KODE
Soal :
```
Ini Adalah Kode yang diberikan untuk peralatan militer dari Uni Soviet dan Republik Rakyat Tiongkok. 
Charlie Tango Foxtrot Romeo Sierra Tango { Four Lima Foxtrot Four Bravo Three Tango _ Foxtrot Zero November Three Tango One Kilo } 
coba terjemahkan :)
```
Apakah kalian melihat kesamaan denggan <a target="_blank" href="https://github.com/nopebee7/ceteef/tree/main/rasyidmf.com/Cryptography/easy#alphabet">klik disini</a>?. Yap betul ini adalah NATO chiper<br>
Kalian bisa decode di <a target="_blank" href="https://cryptii.com/pipes/nato-phonetic-alphabet">cryptii.com</a><br>
`FLAG : CTFRST{4lf4b3t_f0n3t1k}`

#### SANG LEGENDA
Soal :
```
Code ini diciptakan oleh Samuel F.B. Morse dan Alfred Vail pada tahun 1835. Tpi Aku tidak Tau di Mana Codenya Coba Cari Sendiriyh:)
```
Disitu ada 3 tombol *Hint* tetapi yang ada isi nya cuma *Hint* pada barisan ke 3. Disana kalian akan melihat sebuah Sandi Morse, Jika kalian lupa dengan pelajaran Pramuka dulu, kalian bisa mengunakan <a target="_blank" href="https://morsedecoder.com/">morsedecoder.com</a><br>
`FLAG : CTFRST{m0rs3_c0d3}`

#### MY HOME
Soal :
```
Cari aku di suatu rumah yang berada tak jauh dari sini!
```
Mungkin maksud si mimin adalah home page dari website tersebut :D.<br>
`FLAG : CTFRST{Rajawali_Security_Team}`

#### ABSTRACT
Soal :
```
Nama Kode ini berasal dari huruf Ibrani pertama, terakhir, kedua, dan kedua hingga terakhir (  Aleph  -  Taw  -  Bet  -  Shin  ). 
XGUIHG{4gy4hs_x0w3} 
Coba Decodekan Pesan ini.
```
Apakah yang si mimin maksud adalah *Atbash*?<br>
`FLAG : CTFRST{4tb4sh_c0d3}`

#### IM FINE
Soal :
```
Ini masi Berhubungan dengan Chall ABSTRACT.
HGQADG{4qq1o3_h1uw3a} 
coba pecahkan
Hint : f(x)=3x+1 Default
```
Di soal itu mengatakan bahwa ini masih berhubungan dengan soal sebelumnya, sekarang kita tahu bahwa enkripsi tersebut *Atbash*. Namun ternyata itu belum selesai.<br>
Mari kita lihat *Hint* dari soal tersebut. Disini saya coba googling dengan *f(x)=ax+b chiper* dan ternyata ini adalah Affine chiper. Saya coba decode dan menemukan hasil.<br>
`FLAG : CTFRST{4ff1n3_c1ph3r}`

#### S&G
Soal :
```
Flag Berada Di tumpukan Link-Link Aneh Aku tidak bisa menemukannya, tolong Bantu Aku?
Link : https://mega.nz/file/14FwRbLD#j5BtCAzK25fBa6M6JvyBusJyG4GX-X_8HyaLgXAG4FY
```
Ada sebuah file bernama *rst.txt.Z*. Kalian dapat membuka nya layak nya file archive, di dalam file itu ada sebuah file text yang isi nya benar benar link yang sangat banyak. Kalian dapat dengan mudah menemukan flag nya dengan mencari kata *CTFRST*.<br>
`FLAG : CTFRST{str1n9s_4nd_gr3p}`

#### COMAND LINE
Soal :
```
Ini Adalah Perintah Umum terminal yang Sulit Untuk di Artikan.  Coba artikan untuk saya dong
Flag : https://ctf.rajawalisecteam.tech/challenges/uploads/flag
Hint : Berteman Dengan dxx:)
```
Mungkin yang di maksud si mimin adalah *xxd* :D. Ya.. ini adalah isi dari file zip yang di encode menjadi hex, kita bisa mengembalikanya dengan xxd atau juga bisa manual. Disini saya pake xxd aja.<br>
`COMMAND : xxd -r -p flag > flag.zip | unzip flag.zip && cat flag.txt | xxd -r -p`<br>
`FLAG : CTFRST{h3xdump_r3v3r53}`

#### KEPALA PENCURI
Soal :
```
Bantu aku mencari kepala pencuri 
FILE : https://ctf.rajawalisecteam.tech/challenges/uploads/headku.php
HINT : Kepala pencuri harus di tembak
```
Yaa.. mendownload file itu adalah sebuah jebakan :D. Kalian bisa mendapatkan flag dengan melihat isi dari header di saat mengakses url tersebut :D.<br>
`FLAG : CTFRST{_Random_String_HEAD}`

#### PAK QUER
Soal :
```
Ini Adalah Teka Teki Pak Quer Sangat Simple Dan Mudah Semua Bisa Menyelesaikannya
FILE : 
```

#### AKU DIMANA
Soal :
```
Aku Menyimpan Sesuatu Di salah satu website untuk menyimpan potongan-potongan catatan atau kode pemrograman
Bantu aku menemukannya
```
Emm disini saya kebetulan lagi lihat lihat pastebin milik *rajawalisecteam* dan menemukan flag nya. Namun kita harus mendecode dengan *Caesar*<br>
`FLAG : CTFRST[p4st3b1n_my_f4v0r1t]`

#### EASY 32
Soal :
```
10+22
INKEMUSTKR5UKYLTPFPWM33SL4ZTEX3QMVXXA3DFPU======
```
Dari judul nya kita sudah tau kalau in base32.<br>
`FLAG : CTFRST{Easy_for_32_people}`

#### DATA BULANAN
Soal :
```
Dapatkah kamu membantu ku menghitung data bulanan yang telah aku keluarkan, Spreadsheet mungkin bisa membantu mu
https://pastebin.com/WpwnXV3n
```
Ini seperti nya sudah kita bahas di <a target="_blank" href="https://github.com/nopebee7/ceteef/tree/main/rasyidmf.com/Cryptography/easy#total-penghasilan">github.com</a><br>
`FLAG : CTFRST{Encode as Spreadsheet}`

#### DETECTIVE
Soal :
```
Aku adalah seorang detektif yang ingin mencari seorang perempuannya yang hanya bermodalkan foto di media sosial.
FILE : https://ctf.rajawalisecteam.tech/challenges/uploads/flag.jpeg
HINT : building name
```

#### NAMA HOST
Soal :
```
Aku di beri alamat web oleh seseorang dia menyuruhku mencari hostname dari web tersebut, dapat kah kamu membantu ku?
URL : 202.56.164.179
```
Melihat hostname dari sebuah IP kita bisa gunakan suatu tools bernama *Reverse DNS*. Bisa pake <a target="_blank" href="https://dnschecker.org/reverse-dns.php">dnschecker.org</a><br>
`FLAG : CTFRST{host-202-56-164-179.idp.net.id}`


#### BIB
Soal :
```
Hai nama aku "Cipher" dan aku mendapatkan pesan tersembunyi dari seseorang,sebelum dia pergi dia mengatakan "BIB" secara ber'ulang² 
URL : https://pastebin.com/dmDZWGtV
```
Kalian dapat dengan mudah mendecode nya di website <a target="_blank" href="http://tools.socialindo.my.id/encdec/bib-cipher">tools.socialindo.my.id</a><br>
`FLAG : `

### Copyright 2021 nopebee7(@)skullxploit
