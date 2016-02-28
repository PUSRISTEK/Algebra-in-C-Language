# C Language

<h3>1.1 Programming Language</h3>
<p>Bahasa pemograman mempunyai level yang berbeda-beda, tergantung dari seberapa mirip ia menyerupai bahasa yang dimengerti oleh seorang manusia. Semakin mirip dengan bahasa manusia semakin mudah untuk dibaca dan dipelajari maka bahasa itu disebut dengan <b><i>High Level Language</i></b>, sementara <b><i>Low Level Language</i></b> berbanding terbalik dengan <b><i>High Level Language</i></b>. <b><i>Low Level Language</i></b> sulit untuk dibaca dan dipelajari karena bahasanya dekat sekali dengan bahasa mesin (<b><i>Machine Language</i></b>). <b><i>Machine Language</i></b> adalah <b><i>Lowest Level Language</i></b> dalam dunia komputer.</p>

<p>Saat ini tak ada seorangpun programmer yang menggunakan <b><i>Lowest Level Language</i></b>, melainkan <b><i>Low Level Language</i></b> seperti bahasa <b><i>Assembly</i></b>. Bahasa <b><i>Assembly</i></b> berada satu level diatas <b><i>Machine Language</i></b>, mengapa bahasa <b><i>Low Level Language</i></b> masih eksis? sementara bahasa <b><i>High Level Language</i></b> yang lebih mudah difahami sudah tersedia? jawabanya adalah <b>SPEED & SIZE</b>. Sebuah programs yang dibuat menggunakan <b><i>Low Level Language</i></b> kecepatan eksekusinya lebih cepat dan ukuran kapasitasnya lebih ringan. </p>

<p>Sebuah Program yang dibuat menggunakan <b><i>Visual Basic</i></b> bisa mencapai diatas 30 KiloByte tetapi jika program yang sama dibuat dengan <b><i>Assembly Language</i></b> kemungkinan besar dibawah 1 KiloByte, tetapi sebaliknya kita memerlukan waktu yang cukup lama jika program tersebut dibuat dengan <b><i>Assembly Language</i></b>. Sementara dengan bahasa <b><i>High Level Language</i></b> seperti <b><i>Visual Basic</i></b> kita bisa membuat program lebih cepat. it's tradeoff</p>

<p>C adalah bahasa yang masuk kedalam kategori <b><i>Middle Level Language</i></b> dikarenakan c mempunyai bagian yang terikat dengan <b><i>Low Level Language</i></b> dan <b><i>High Level Language</i></b>. Dengan bahasa C kita bisa menikmati <b><i>High Level Language</i></b> dan <b><i>speed of development</i></b>, ukuran program yang padat, dan kecepatan eksekusi hampir mendekati <b><i>Low Level Language</i></b>.</p>

<h3>1.2 C History</h3>

<p>Bahasa c diciptakan dan di implementasikan pertama kali oleh <b>Dennis Ritchie</b> di DEC PDP-11
yang menggunakan sistem operasi UNIX pada tahun 1972 di American Telegraph & Telecomunication. C adalah hasil dari proses pengembangan yang dimulai dari bahasa yang sudah sangat tua yaitu <b>BCPL</b> <b><i>(Basic Combined Programming Language)</i></b>. BCPL sebelumnya dikembangkan tahun 1960 di Cambridge University oleh Martin Richard yang
terinspirasi dari bahasa <b>B</b>, sebuah bahasa yang diciptakan oleh Ken Thompson. B menjadi penyebab atau awal pengembangan bahasa c di tahun 1970.</p>

<p>Selama beberapa tahun, standar de facto untuk bahasa c adalah versi yang disediakan untuk sistem operasi UNIX.
Pertama kali ini dijelaskan dalam buku <b>The C Programming Language</b> karya Brian Kernighan dan Dennis Ritchie (englewood Cliffs, N.J.: Prentice-Hall, 1978). Pada musim panas tahun 1983 sebuah komite memutuskan untuk membuat <b>ANSI (American National Standards Institute) standar</b> yang mampu menjelaskan bahasa c. Proses standarisasi ini berlangsung selama 6 tahun lebih lama dari yang orang orang harapkan.</p>

<p>The ANSI C standar terakhir diadopsi pada desember tahun 1989. Kopi perdananya tersedia pada awal tahun 90an
standar ini juga diadopsi oleh <b>ISO (International Standard Organization)</b> dan menghasilkan sebuah standar yang disebut ANSI/C Standar C. Pada tahun 1995, amandemen 1 untuk standar c diadopsi, yang didalamnya menambahkan beberapa library. Pada tahun 1989 standar untuk c bersamaan dengan amandemen 1 muncul base document untuk standar C++, menjelaskan c subset untuk c++. Versi bahasa c pada tahun 1989 secara umum disebut sebagai <b>c89.</b></p>

<p>Selama tahun 1990an pengembangan standar bahasa c++ dikonsumsi oleh banyak perhatian programmer, begitu juga dengan bahasa c. Pengembangan bahasa c terus dilakukan meski dalam waktu yang lama, namun dari pengembangan berhasil menghasilkan standar c yang baru. Hasilnya adalah standar c pada tahun 1999 yang disebut <b>c99</b>. Secara umum, c99 hampir mempertahankan semua fitur yang ada di dalam bahasa c sebelumnya. Dengan demikian c masih c selain itu komite yang mengurus standarisasi c99 fokus kepada dua bidang utama yaitu : Penambahan beberapa <b>numeric libraries</b> dan pengembangan beberapa penggunaan khusus yang sangat inovatif seperti penambahan fitur baru <b>variable-length arrays dan restrict pointer qualifier</b>. Inovasi ini sekali lagi menempatkan c menjadi garis depan pengembangan bahasa pemograman. Source : [C - The Complete Reference]</p> 

<h3>1.3 C is a Middle Level Language</h3>
<p>Pada computer C seringkali disebut bahasa <b>Middle level</b> meskipun pada beberapa literatur disebut sebagai bahasa low level. Sebagai bahasa yang ada di middle level c memiliki kemampuan untuk memanipulasi <b>bits, bytes and adresses</b> yang menjadi elemen dasar fungsi komputer. Semua bahasa pemograman <b>high level</b> mendukung konsep tipe data, Tipe Data itu sendiri menjelaskan sekumpulan nilai dalam sebuah variabel yang selanjutnya bisa digunakan untuk melakukan operasi tertentu.
Data tipe yang paling umum adalah <b>integer, character, dan floating point</b>, c memiliki beberapa data tipe yang tersedia didalamnya dan c bukan termasuk <b>strongly typed language seperti pascal dan ada</b>. Hampir semua konversi tipe data dalam bahasa c bisa dilakukan, selain itu aspek penting lainya dari bahasa c adalah sedikitnya jumlah <b>keyword</b> yang dimilikinya. Sebagai contoh c89 hanya memiliki 32 keyword dan pada c99 hanya bertambah 5 keyword. Sementara bahasa pemograman high level biasanya memiliki keyword yang lebih banyak. Contoh pada BASIC didalamnya terdapat 100 keyword.</p>

<h3>1.4 C is a Structured Language</h3>
<p>C adalah bahasa pemograman yang terstruktur, menganut paradigma pemograman <b>procedural</b>. Bahasa C menggunakan sebuah <b><i>Compiler</i></b> untuk menerjemahkan <b><i>High Level Language</i></b> kedalam <b><i>Machine Language</i></b>. <b><i>Compiler</i></b> sendiri adalah sebuah program yang berfungsi sebagai penerjemah, selain <b><i>Compiler</i></b> ada juga penerjemah lainya yang disebut dengan <b><i>Assembler</i></b> dan <b><i>Interpreter</i></b> yang akan kita bahas dibagian selanjutnya.</p>

<h3>1.5 Compiler versus Assembler</h3>
<p><b><i>Compiler</i></b> membaca seluruh program dan mengkonversinya ke <b>Object Code</b>, atau biasa disebut penerjemahan dari <b><i>Source Code</i></b> ke dalam <b><i>Target Language</i></b> sebagai contoh dari bahasa c kedalam bahasa <b><i>Assembly.</i></b>. Selanjutnya sebuah <b><i>Assembler</i></b> akan menerjemahkan <b><i>Assembly Language</i></b> kedalam <b><i>Machine Code</i></b> atau <b><i>Object Code</i></b> yang selanjutnya dapat dimengerti oleh komputer. </p>

<h3>1.6 Difference Beetwen Compiler & Assembler</h3>

| Assembler        | Compiler           | 
| ------------- |:-------------:| 
| Menerjemahkan <b><i>Mnemonic Codes</i></b> seperti ADD, SUB, PRN kedalam <b><i>Machine Language</i></b>.     | Menerjemahkan <b><i>High Level Language</i></b> kedalam <b><i>Assembly Language</i></b>. | 
| Sebuah Program yang dieksekusi menggunakan sebuah <b><i>Assembler</i></b> bisa dieksekusi dengan cepat, karena secara langsung mampu menterjemahkan <b><i>Source Codes</i></b> kedalam <b><i>Machine Languages</i></b>    | Memerlukan waktu untuk mengeksekusi sebuah Program karena <b><i>Source Codes</i></b> harus diterjemahkan terlebih dahulu kedalam <b><i>Assembly Language</i></b>  yang selanjutnya akan diterjemahkan kedalam <b><i>Machine Language</i></b> oleh sebuah <b><i>Assembler</i></b>    | 

<h3>1.7 Interpreter versus Compiler</h3>
<p>Sebuah <b><i>Interpreter</i></b> mampu melakukan penerjemahan suatu <b><i>Source Code</i></b> secara <b><i>Sentence-by-Sentence Translation</i></b> (Sebaris kode). Secara umum program yang diterjemahkan menggunakan suatu <b><i>Interpreter</i></b> berjalan lebih lambat daripada program yang diterjemahkan menggunakan sebuah <b><i>Compiler</i></b>, dikarenakan kompilasi hanya terjadi satu kali dan <b><i>Compiler</i></b> mengkonversi <b><i>Source Code</i></b> kedalam <b><i>Object Code</i></b> yang bisa dieksekusi langsung secara berkali kali oleh komputer. Sementara penterjemahan menggunakan <b><i>Interpreter</i></b> harus dilakukan setiap kali program akan dijalankan.</p> Source : [C - The Complete Reference]

<h3>1.8 Difference Beetwen Interpreter & Compiler</h3>
| Interpreter        | Compiler           | 
| ------------- |:-------------:| 
| Compiler menterjemahkan seluruh <b><i>High Level Language</i></b> sekali kedalam <b><i>Machine Language</i></b> sebelum dieksekusi. | Interpreter menterjemahkan program yang ditulis dengan <b><i>High Level Language</i></b> kedalam <b><i>Machine Language</i></b> bersamaan dengan mengeksekusi programnya. Program diterjemahkan dan dieksekusi per-instruksi. |


<h3>1.9 C Language</h3>
<p>C digunakan untuk membuat program ukuran kecil dan cepat, c adalah bahasa yang paling dekat dengan bahasa mesin.
Secara hakikat sebenarnya omputer hanya mengerti satu bahasa yaitu bahasa mesin. Sebuah aliran biner (binary stream) 
yang terdiri dari 0 dan 1. Kita akan mengkonversi bahasa c kedalam bahasa mesin dengan bantuan sebuah kompiler. 
Sebuah source code akan dikompilasi menjadi executable yang didalamnya terdapat bahasa mesin yaitu sekumpulan 
kode biner 1 dan 0 yang mengalir untuk dipahami oleh komputer. Source : [Headfirst C] </p> 

<p>C digunakan dimana kecepatan, kapasitas dan portability adalah sesuati yang penting. 
Kebanyakan sistem operasi dibuat menggunakan bahasa c, banyak bahasa pemograman dibuat menggunakan bahasa c
dan banyak game yang dibuat menggunakan bahasa c. Ada 3 standar bahasa c, yaitu ANSI C pada akhir tahun 80an, 
c99 pada tahun 99 dan standar saat ini yaitu c11 dan perbedaan masing masingnya tidak terlalu besar</p>
