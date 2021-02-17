## rasyidmf.com (CTFR) Cryptography Easy WriteUp

#### FIRST FLAG
Soal : 
```
Selamat datang di website kami, Dan tentunya anda ingin mendapatkan point pertama kali nya kan ? 
Silahkan cari pada halaman home kami, disitu terdapat Sebuah angka yang harus di 
konversi menjadi string
```
Di halaman utama ada sebuah chiper. disitu kita di suruh untuk meng encode chiper tersebut
ke *deadbeef*. Chiper : 
```
72721798973508317998010221759715603442488699336903823695032175490877440550933707738215915097249162010936760632656546551213097571155720293246858222618614687119941380089920829
```
Website encode *deadbeef* : <a target="_blank" href="https://deadbeef.app/">deadbeef.app</a><br>
Masukan chiper ke input decimal. setelah itu copy yang dibagian hex, Decode hex tersebut dan lanjutkan sampai dapat flag.<br>
`FLAG : CTFR{th1s_1s_your_f1rst_fl4g}`


#### SECOND FLAG
Soal :
```
Sebelumnya sudah mengenal yang namanya Encode dan Decode Yaah ? Sekarang masih sama, 
cuman jika kamu melihatnya challenge ini sebagai unik, maka pelajaran bagi anda :D.
Flag : TKWI{j3t0eu_wc4x_n4j_t1gy3i_k3ok}
```
Ini adalah chiper ROT13. namun kalian tidak akan langsung mendapatkan flag, decode dengan ROT13 dan set Amount ke 9.<br>
`FLAG : CTFR{s3c0nd_fl4g_w4s_c1ph3r_t3xt}`


#### LAST FLAG
Soal :
```
Ini adalah Last FLAG Challenge, Masih sama dengan Challenge sebelumnya. Akan tetapi hanya berbeda versi, 
Jika kamu baru dalam hal ini maka challenge ini dapat dijadikan pelajaran buat kamu :D.
Flag : HEFX{q4dt_im4113yg3?}
```
Kalian dapat dengan mudah mendapatkan flag dengan decode mengunakan Vigenere Chiper dan mengunakan key FLAG.<br>
`FLAG : CTFR{l4st_ch4113ng3?}`


#### DASAR64
Soal :
```
Belum bisa menyelesaikan First Flag ? Silahkan cari tau bagaimana mengkonversi flag ini menjadi teks yang bisa di baca
Flag : Q1RGUntzMW1wbDNfYjRzM182NH0=
```
Walaupun kalian masih awam dalam cryptograpy, kalian pasti tau ini chiper apa. Ini adalah BASE64.<br>
`FLAG : CTFR{s1mpl3_b4s3_64}`


#### DASAR32
Soal :
```
Belum bisa menyelesaikan First Flag ? Silahkan cari tau bagaimana mengkonversi flag ini menjadi teks yang bisa di baca
Flag : INKEMUT3OMYW24DMGNPWENDTGNPTGMT5BI======
```
Ini sama dengan *Dasar32* hanya saja ini adalah BASE32 chiper.<br>
`FLAG : CTFR{s1mpl3_b4s3_32}`


#### KODE MOUSE
Soal :
```
Mouse juga mempunyai kode untuk melakukan klik pada sebuah komputer, akan tetapi hal ini lah yang membuat komputer dapat bergerak, 
Tanpa mouse PC / Laptop kita tidak ada guna nya :). salah satunya coba decode ini, Flag Format nya harus tetap di ikuti ya!.
Flag : -.-. - ..-. .-. -- ----- .-. ... ...-- ..--.- -.-. ----- -.. ...-- ..--.- .---- ... ..--.- .- .-- ...-- ... ----- -- ...--
```
Seperti yang di ajarkan disaat kelas 3SD pada ekstrakulikuler pramuka, Ini adalah kode morse. <br>
Jika kalian sudah tidak ingat, bisa gunakan website : <a target="_blank" href="http://morsedecoder.com/">morsedecoder.com</a><br>
`FLAG : CTFR{m0rs3_c0d3_1s_aw3s0m3}`


#### BELI ROTAN 13
Soal :
```
Mama Adi: "Di belikan mama Rotan"
Adi: "Berapa mak ?"
Mama Adi: "13 Aja di Pasar Pahlawan"
Adi: "Uangnya mana mak?"
Mama Adi: "Nih, PGSE{3i3e_u34eq_4obhg_e0g13?}"
Adi: "Siap Mak!"
```
Ya seperti judulnya kita akan terpikir langsung dengan chiper *ROT13*<br>
`FLAG : CTFR{3v3r_h34rd_4bout_r0t13?}`


#### BAHASA BAYI
Soal :
```
Bahasa Bayi kira kria nya seperti ini kan ababaabababab, Nah jika sudah tau coba translate Bahasa Bayi yang satu ini
Flag : aaaba baabb aabab baaab aaaab babaa ababa aaaaa abbab aaaab aaaaa aabbb aaaaa baaba aaaaa aaaab aaaaa bbaaa abaaa
```
Disaat melihat soal nya kalian pasti bingung ini chiper apa, begitu pun dengan saya. Namun ketika kita mencari nya di google ini adalah *Baconian* Chiper<br>
Kalian dapat dengan mudah mendecode nya di : <a target="_blank" href="https://cryptii.com/pipes/bacon-cipher">cryptii.com</a><br>
`FLAG : CTFR{bukan_bahasa_bayi}`


#### JUAL V-GEN MURAH
Soal :
```
Saya jual V-Gen dengan harga Rp. 100,000, Tentunya ada Promo Diskon sebanyak 50% jika dapat mencocokan kata dibawah ini
Key : FLAG
Flag : HEFX{a1rn3x3_h1ah3x!!!}
Kalo sudah bisa mencocokan, Silahkan pakai Diskonnya di Last Flag :D
```
Ini sama dengan soal *LAST FLAG*, Vigenere chiper dengan key FLAG.<br>
`FLAG : CTFR{v1gn3r3_c1ph3r!!!}`


#### HIDDEN FLAG
Soal :
```
Jika kalian tau, Website CTFR menggunakan Framework Buatan sendiri dengan komponent JQuery, Bootstrap Row, Free Image. 
Akan tetapi CTFR juga menyembunyikan sesuatu juga loh! Bahkan jika anda perhatikan dibawah ini terdapat Flag, 
Nah jika sudah dapat Flag nya silahkan isi di Inputannya :D. 
```
Tidak perlu pusing mencari flag atau clue dari soal ini. Karna flag nya berada di balik kata tapi memang tidak terlihat.<br>
Kita bisa mengunakan alat cangih bernama inspect element<br>
`FLAG : CTFR{d3v3l0p3r_t00l5}`


#### KODE BINER
Soal :
```
Kode biner mewakili teks, instruksi prosesor komputer, atau data lainnya menggunakan sistem dua simbol. Sistem dua simbol yang digunakan seringkali "0" dan "1" dari sistem angka biner. 
Kode biner memberikan pola digit biner, juga dikenal sebagai bit, untuk setiap karakter, instruksi, dll.
Flag : 01000011 01010100 01000110 01010010 01111011 01100010 00110001 01101110 00110100 01110010 01111001 01011111 00110001 01110011 01011111 01100001 01110111 00110011 01110011 00110000 01101101 00110011 01111101
```
Tidak perlu di ambil pusing, ini adalah binary.<br>
`FLAG : CTFR{b1n4ry_1s_aw3s0m3}`


#### HEXADECIMAL
Soal :
```
Heksadesimal atau sistem bilangan basis enam belas adalah sebuah sistem bilangan yang menggunakan 16 simbol. Berbeda dengan sistem bilangan desimal, 
simbol yang digunakan dari sistem ini adalah angka 0 sampai 9, ditambah dengan 6 simbol lainnya dengan menggunakan huruf A hingga F.
Flag : 435446527b68337834643363316d346c5f31735f61773373306d337d
```
Seperti judulnya ini adalah *HEX*.<br>
`FLAG : CTFR{h3x4d3c1m4l_1s_aw3s0m3}`


#### REVERSE TEXT
Soal :
```
Pernah lihat huruf dan angka terbalik ? Contohnya seperti "Ayam" akan menjadi "mayA", Nah coba balikkan lagi teks ini agar mendapatkan flag yang benar.
Flag : }3h3h_tx3t_3sr3v3r{RFTC
```
Ini adalah kata yang terbalik posisinya. Gausah bingung memindahkan nya satu satu, kita bisa mengunakan bantuan website : <a target="_blank" href="http://www.unit-conversion.info/texttools/reverse-text/">unit-conversion.info</a><br>
`FLAG : CTFR{r3v3rs3_t3xt_h3h3}`


#### DECIMAL
Soal :
```
Sistem bilangan desimal/persepuluhan adalah sistem bilangan yang menggunakan 10 macam angka dari 0,1, sampai 9. Setelah angka 9, angka berikutnya adalah 1 1, 1 2, dan seterusnya.
Flag : 67 84 70 82 123 52 115 99 49 49 95 99 48 100 51 125
```
Kalian bisa decode di : <a target="_blank" href="https://cryptii.com/pipes/decimal-text">cryptii.com</a><br>
`FLAG : CTFR{4sc11_c0d3}`


#### UPIN IPIN
Soal :
```
Upin ipin sedang pergi kepasar, kemudian menemukan 2 angka yaitu 1 dan 4. Kemudian Upin bertanya kepada Ipin,
Upin : "Pin, kau tau tak angka apa nie"
Ipin : "Tak laa, tapi ipin nemu teks lagi ni GXJV{4jj1r3_g1tl3v_ea3w0q3}"
Upin : "Keknye, kite harus kasih tau opah, Mungkin opah tau maksud dari huruf dan teks tadi nie"
Ipin : "Jom"
```
Emmm gaada clue, kira kira apa ya... Disini saya mencoba untuk decode dengan Caesar di <a target="_blank" href="https://www.dcode.fr/caesar-cipher">dcode.fr</a> dan tanpa diduga kita dapat flag nya. <br>
Yang membuat saya heran adalah ternyata itu adalah affine chiper :v.<br>
`FLAG : CTFR{4ff1n3_c1ph3r_aw3s0m3}`


#### KEYBOARD
Soal :
```
Keyboard merupakan Hardware yang membantu kita dalam menulis pada komputer. Tapi ketahuilah, dengan Keyboard kita sendiri dapat membuat enkripsi yang unik. 
Contohnya seperti "Ayam" akan menjadi "Sus,". Nah sampe sini sudah paham kan ? Coba Decode Flag dibawah ini dengan Trik yang sama seperti contoh diatas
Flag : VYGT}l4un-5tf+dj2gy+2d+e42tfQ
```

#### ALPHABET
Soal :
```
Apa yang kalian ketahui tentang Alphabet, Sebuah Huruf A sampai Z dan Angka 0 sampai 9 kan. Nah saya beri Contoh tentang Enkripsi ini "Ayam" akan menjadi "Alfa Yankee Alfa Mike". 
Enkripsi nya sangat simpel, kita hanya mencocokkan huruf paling depannya saja, tapi bagaimana dengan angka ? Contoh "123" akan menjadi "One Two Three". 
Sudah paham kan sampe sini, Nah coba decode Flag ini
Flag : Charlie Tango Foxtrot Romeo { Sierra One Mike Papa Lima Three _ Four Lima Papa Hotel Four Bravo Three Tango }
```
Dengan search di google dengan kata kunci *Charlie Tango Foxtrot Romeo* kita bisa menemukan kalau ini adalah NATO Chiper. Kalian bisa decode di <a target="_blank" href="https://cryptii.com/pipes/nato-phonetic-alphabet">cryptii.com</a><br>
`FLAG : CTFR{s1mpl3_4lph4b3t}`


#### OCTAL
Soal :
```
Oktal atau sistem bilangan basis delapan adalah sebuah sistem bilangan berbasis delapan. Simbol yang digunakan pada sistem ini adalah 0,1,2,3,4,5,6,7. 
Konversi Sistem Bilangan Oktal berasal dari Sistem bilangan biner yang dikelompokkan tiap tiga bit biner dari ujung paling kanan.
Flag : 103 124 106 122 173 60 143 164 64 154 137 61 163 137 144 61 146 146 137 167 61 164 150 137 144 63 143 61 155 64 154 175
```
Judul dari chall ini adlaah cipher nya, yaitu OCTAL.<br>
`FLAG : CTFR{0ct4l_1s_d1ff_w1th_d3c1m4l}`


#### PAGAR REL
Soal :
```
Pagar Rel juga termasuk Cryptography loh, Cuman yaaa ada kesalahan sedikit tentang penulisan judul Challenge ini. Tapi sekalian bantuin decode ini yahh
KO : 4
Flag : Fl33TR1_c_hrC{4fncp}r31
```
Yah, bahasa inggris dari *PAGAR REL* adalah chiper dari kode diatas yaitu *Railfence*. kalian bisa decode di <a target="_blank" href="https://cryptii.com/pipes/rail-fence-cipher">cryptii.com</a><br>
Dan atur Key dan Offset ke 4<br>
`FLAG : CTFR{r41l_f3nc3_c1ph3r}`


#### HP NOKIA
Soal :
```
Hp Nokia dulu sempat naik daun sampai dipakai dimana-mana, Dan tentunya untuk mengklik B saja harus klik nomor "2" 2 kali, 
Nah kali ini enkripsi yang dipakai pada challenge ini hanya sekedar Tap-Tap saja, Contohnya "Ayam" akan menjadi "2 999 2 6". Nah coba decode Hasil Tap-Tap
Flag : CTFR{8 2 7 8 2 7 6 2 66 8 2 7}.
```
Buat kalian yang dulu lahir di tahun 90 an pasti paham.<br>
`FLAG : CTFR{TAPTAPMANTAP}`


#### XOR
Soal :
```
XOR adalah dua syarat logis, yang menghasilkan true hanya jika kedua masukan sama. XOR juga biasanya digunakan sebagai enkripsi untuk menjaga keamanan data. 
Nah coba Decode hasil XOR Enkripsi ini dengan Key "FLAG"
Flag : 051807153d347135197d3218273b72347621243a
```
Kalian bisa decode *XOR* di <a target="_blank" href="https://www.dcode.fr/xor-cipher">dcode.fr</a><br>
`FLAG : CTFR{x0r_1s_aw3s0me}`


#### MD5
Soal :
```
Dalam kriptografi, MD5 adalah fungsi hash kriptografik yang digunakan secara luas dengan hash value 128-bit. Pada standart Internet,
MD5 telah dimanfaatkan secara bermacam-macam pada aplikasi keamanan, dan MD5 juga umum digunakan untuk melakukan pengujian integritas sebuah berkas.
Flag : CTFR{(MD5 dari "CTFR")}
```
Ya kalian pasti dah paham...<br>
`FLAG : CTFR{112c61a276d0376f2f6b25dd3a337b1d}`


#### SHA1
Soal :
```
Dalam kriptografi, SHA-1 adalah fungsi hash kriptografi yang mengambil input dan menghasilkan nilai hash 160-bit yang dikenal sebagai intisari pesan - biasanya dirender sebagai bilangan heksadesimal, panjangnya 40 digit.
Flag : CTFR{(SHA1 dari "CTFR")}
```
Ini juga ...<br>
`FLAG : CTFR{725912ce4ff578c4a9ece9821e7da02103276150}`


#### SHA256
Soal :
```
Secure Hash Algorithms adalah keluarga fungsi hash kriptografis yang diterbitkan oleh Institut Nasional Standar dan Teknologi sebagai Standar Pemrosesan Informasi Federal AS, 
termasuk: SHA-0: Retronym yang diterapkan pada versi asli dari fungsi hash 160-bit yang diterbitkan pada tahun 1993 dengan nama "SHA".
Flag : CTFR{(SHA256 dari "CTFR")}
```
Emm kaya nya juga..<br>
`FLAG : CTFR{fa0bd9ce51434b585e2349c1f427b75b6e9337250b6b4692d453f2729f606bc4}`


#### SHA384
Soal :
```
SHA atau Secure Hashing Algorithm merupakan fungsi kriptografi yang dirancang khusus oleh penyedia otoritas kemanan internet untuk menjaga keamanan data.
Flag : CTFR{(SHA384 dari "CTFR")}
```
Soal yang diulang? entahlah...<br>
`FLAG : CTFR{825d560bc11e550cf7441275c70372440d28353c68b5f03c2e95d88c956c74e499d7c8f08d18415e56566342bd91aba4}`


#### SHA512
Soal :
```
SHA atau Secure Hashing Algorithm merupakan fungsi kriptografi yang dirancang khusus oleh penyedia otoritas kemanan internet untuk menjaga keamanan data.
Flag : CTFR{(SHA512 dari "CTFR")}
```
Sepertinya iya...<br>
`FLAG : CTFR{189c3a22d591747e3527773544712f8f3f11f23cdfa9fe3c163cce87bd4526f3343cbaefb445e6fb7d7b274167872efa34d9cc045572c8d3de4b76294745ca95}`


#### MD2
Soal :
```
Algoritma Message-Digest MD2 adalah fungsi hash kriptografi yang dikembangkan oleh Ronald Rivest pada tahun 1989. 
Algoritma ini dioptimalkan untuk komputer 8-bit. MD2 ditetapkan dalam RFC 1319.
Flag : CTFR{(MD2 dari "CTFR")}
```
Emde duah...<br>
`FLAG : CTFR{9e873a7d36f0b41bf51ecc79289c8b7c}`


#### MD4
Soal :
```
MD4 Message-Digest Algorithm adalah fungsi hash kriptografi yang dikembangkan oleh Ronald Rivest pada tahun 1990. Panjang intinya adalah 128 bit. 
Algoritme telah mempengaruhi desain selanjutnya, seperti algoritma MD5, SHA-1 dan RIPEMD. Initialism "MD" adalah singkatan dari "Message Digest."
Flag : CTFR{(MD4 dari "CTFR")}
```
Bosan?? oh tentu tidak..<br>
`FLAG : CTFR{bcab8f1da86a260ce0fb2a2c027a0d6f}`


#### OTAK BERSETUBUH
Soal :
```
Pernah dengar kagak tentang cara Otak Bersebutuh ? Kalo belum pernah, Coba cari di google maksudnya gimana. Eh bukan yang bahasa indonesia nya yaaa h3h3
Flag : ++++++++++[>+>+++>+++++++>++++++++++<<<<-]>>>---.>----------------.<+++.>--.+++++++++++++++++++++++++++++++++++++++++.-------------------------.++++++++++++++++.<------------------.---.>----.---------------.+++++++.+++++++++++++++.------------------.++.++++++.------------.+++++++++.<++.>.<.>+++++++++++++++++++++.
```
Yha sama dengan *PAGAR REL*. Bahasa inggris dari soal ini adalah *Brainfuck*.<br>
`FLAG : CTFR{br41n_fucek_h3h3}`


#### OOK
Soal :
```
Title pada challenge ini udah memberikan hint untuk cara menyelesaikannya, Soo Goodluck and Have Fun
Flag : ....................!?.?...?.......?...............?....................?.?.?.?.!!?!.?.?.?!!!!!!!..?!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!.?.......!..?!!!!!...................................................................................!.?.?.....................................!.!..?.?!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!.!!!!!!!!!!!!!!!!!!!!!!!!!.?.?...!..?.?........................................!.!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!.?.?.....!..?.?........................................!.?.?.!!!!!!!..?.?!!!!!!!!!!!!!!!.?.?.........!..?.?....!.!!!!!!!!!!!!!!!.?.?.!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!.!.!..?.?............................................!.
```
Soal ini sudah memberikan jawabanya. Ini adalah Ook chiper.<br>
`FLAG : CTFR{00k_1s_3s0l4ng!!!}`


#### MALL BOGOR
Soal :
```
Di Mall Bogor banyak jual barang-barang aksesoris, peralatan rumah, makan-makanan. Nah tapi sayangnya mimin mau beli bendera, tapi malah yang dikasih bendera kyk begini :(
Flag : D'`%$^>!<5YWWyCfRRtr0N_'9lHZ"h3V|A@RxP|_)sxwYutslqpi/gOedibaf_%cbDC_^W\UyS;WVUTSLpJINMFEi,HGF?DC<A:^>765:981U543,r*N.n,+*)"Fgf|#"yx>_utyr8vutslk1onPle+cKaf_d]#aC_^WVzT<RvV8NSRKJnNML.DhHGF?cCBA#">7[|43876/S-210)Mnm%$)('~Dedzyx>v{ts9wpon4lTji/mOedc)t
```
Ini adalah jenis Chiper *mallbolge* kamu bisa cek di <a target="_blank" href="https://malbolge.doleczek.pl/">malbolge.doleczek.pl</a><br>
`FLAG : CTFR{m4lb0lg3_1s_n0t_b4s385}`


#### PIKACHU
Soal :
```
Tau pikachu kan ? Nah gimana cara Kalo Pikachu lagi ngomong ? Pika pika pi pi ka ka cu cu pichu pichu. Nah coba bantu translate bahasa pikachu dibawah ini menggunakan ...
Flag : pi pi pi pi pi pi pi pi pi pi pika pipi pi pipi pi pi pi pipi pi pi pi pi pi pi pi pipi pi pi pi pi pi pi pi pi pi pi pichu pichu pichu pichu ka chu pipi pipi pipi ka ka ka pikachu pipi ka ka ka ka ka ka ka ka ka ka ka ka ka ka ka ka pikachu pichu pi pi pi pikachu pipi ka ka pikachu pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu ka ka ka ka ka ka ka ka ka ka ka pikachu pichu pichu pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu pipi pipi ka ka ka ka ka pikachu pichu pichu pi pi pi pikachu pipi pipi ka ka ka ka ka ka ka ka ka ka ka ka pikachu pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu pichu pichu ka ka ka pikachu pipi pipi ka ka ka ka ka pikachu pichu pichu pi pi pi pikachu pipi pipi ka ka ka ka ka ka ka ka ka ka ka ka pikachu pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu pichu pichu ka ka ka pikachu pipi pipi ka ka ka ka ka pikachu pichu pichu pi pi pi pikachu pikachu pikachu pikachu pikachu pikachu pipi pipi ka ka ka ka ka ka ka ka ka ka ka ka pikachu pi pi pi pi pikachu pi pi pi pi pi pikachu pi pi pi pi pi pi pi pi pi pi pi pi pi pikachu pikachu pikachu pikachu pikachu pikachu pi pi pi pi pi pi pi pi pikachu
```
Waw sangat panjang, dan judul dari soal ini adalah chiper itu sendiri.<br>
`FLAG : CTFR{p1k4_p1k4_p1k444444_chuuuuuu}`


#### IKAN MATI
Soal :
```
Ikan kalo sudah mati diapain ? Dikuburlah. Tapi Ikan mati juga ada bahasa tersendiri lohh, Coba bantu translate kan Bahasa Interpeter dari Ikan mati dibawah ini
Flag : iisiiiisiiioiiiiiiiiiiiiiiiiioddddddddddddddoiiiiiiiiiiiioiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioddddddddoddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioddddddddddddoiiiiiiiiiiiiodddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiodddddddddddddddoddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioddddddddddoiiiiiiiiiiiiiodddddddddddddddoiiiiiiiiiiiiiiiiioiiiiiodddddddoiiiiiiiiiiiodddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioiiioddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiioddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiodddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddddoiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiio
```
Yha dan lagi ini sama seperti *PAGAR REL* dan *OTAK BERSETUBUH*. Chiper nya adalah *deadfish*<br>
`FLAG : CTFR{s3j4k_k4p4n_1kan_puny4_b4h4s4}`


#### TOTAL PENGHASILAN
Soal :
```
Penghasilan perbulan mimin ditulis sebagai teks, Coba cari tauu dong arti penghasilan mimin :D
Flag : Meresahkan Panjang Nya :v
```
*flag diatas bukanlah flag soal asli*. Aduh gaada clue nih, Dan akhirnya setelah pencarian panjang ternyata ini adalah Spamimic Fake Spreadsheet.<br>
Ada web nya <a target="_blank" href="https://www.spammimic.com/spreadsheet.php?action=decode">spammimic.com</a><br>
`FLAG : CTFR{f4k3_t4x1_3h_1_m34n_spr34dsh33t}`


#### SURAT UNTUK TEMAN
Soal :
```
Mimin ketemu surat dari orang lain nih, Coba di baca deh
Flag : Panjang Banget Gabisa Masuk :v
```
*flag diatas bukanlah flag soal asli*. Okelah buat yang bingung ini masih sama yaitu Spamimic biasa.<br>
`FLAG : CTFR{sp4m_m3ss4g3}`


#### MAIN ADIL
Soal :
```
Yang namanya bermain harus main adil, tentunya tidak ada kecurangan.
Cipher : N41IG4AOU4E1K
K : CTFR
Flag : CTFR{(Huruf Kapital)}
```
Sama seperti soal sebelum nya. Jenis cipher ini dari bahasa inggris, yaitu *playfair* cipher<br>
`FLAG : CTFR{M41NH4RUS4D1L}`


#### TERTEMPEL CIP
Soal :
```
Seketika mimin, Tanpa sadar di sepatu mimin terdapat Cip. Cip nya kagak bisa kelepas sampai ketemu arti dari teks ini
Alphabet : abcdefghijklmnopqrstuvwxyz0123456789_{}
Flag : _T7VBIt{Iu5C_Lx5Jv???A
```
Maafkan aku kawan, aku belum menemukan arti dari semua ini...


#### AES #1
Soal :
```
Dalam kriptografi, Standar Enkripsi Lanjutan merupakan standar enkripsi dengan kunci simetris yang diadopsi oleh Pemerintah Amerika Serikat. 
Standar ini terdiri dari tiga penyandian blok, yaitu AES-128, AES-192, dan AES-256, 
yang diadopsi dari koleksi yang lebih besar yang awalnya diterbitkan sebagai Rijndael.
Flag : c4ce1a9c4374553b59cb8a5820f9aaf4f9468344757f2ce845018c76312d201c
Key : 1-90A-F
```
Ya.. itu bukanlah key yang akan di gunakan maksud dari "-" adalah lain. Key : 12345678ABCDEF<br>
`FLAG : CTFR{4e5_3ncrypt10n_w45_3xp3rt}`


#### PUKULAN IKAN
Soal :
```
Kebayang gak kalo ikan bisa memukul dengan Sirip nya, Mimin aja susah ngebayangin :3
Flag : 7qhsC4GtbkKjfwkHwnbQTi/v0L9sAioOCmKxeUwMYUKKl/Ge8Tf+bQ==
```
Ya.. lagi lagi chiper nya adalah bahasa inggris dari judul soal nya. Ini adalah *Blowfish*<br>
`FLAG : CTFR{pukul4n_1k4n_4l145_bl0w_f15h}`


#### UU NO 17
Soal :
```
UU tahun 2019 nomor 17 tentang Sumber Daya Air, Sebab air sebagai bagian dari sumber daya air merupakan cabang produksi penting dan menguasai hajat hidup orang banyak yang dikuasai oleh negara untuk dipergunakan bagi sebesar-besar kemakmuran rakyat sesuai dengan amanat Undang-Undang Dasar Negara Republik Indonesia Tahun 1945.
Flag : :0U1&4GMU;F0T;F=?=6YD-&YG7S-N8S!D,WT` ` 
```
Ini adalah *uuencoding* cipher<br>
`FLAG : CTFR{und4ng_und4ng_3nc0d3}`


#### BASE COC
Soal :
```
Mimin sudah lama sih main COC (Clash of Clan) cuman bingung mau base yang kuat gimana, maka dari itu mimin saran kan pake base yang ada disini https://cocbases.com/
Flag : A5Rz&{8Yh2@r;mkm]wuJu=}SUJR;uF
```
Fyuh tak terasa udah di penhujung soal.. kalo gitu saya main cepet aja. Jadi ini adalah base91 chiper<br>
`FLAG : CTFR{b453_s3mb1l4n_s4tu}`


#### IDENTIDY HASH
Soal :
```
Waktu jaman mimin Deface, mimin sering melihat Hash ini tersebar dimana-mana, Dikarenakan Password yang selalu diatur dengan default maka dari itu banyak website yang terjadi peretasan.
Flag : CTFR{(MD5 yang sudah terbaiki)}
Hash : 21232f297..7..a74..94a..4a8...c3
```
Di ceritakan bahwa mimin ctfr dahulu adalah player sql :v. Disini saya coba coba untuk encode "admin" menjadi md5 hash, dan ternyata itu sama. <br>
`FLAG : CTFR{21232f297a57a5a743894a0e4a801fc3}`




### Copyright 2021 nopebee7@skullxploit
