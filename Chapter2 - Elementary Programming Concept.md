<h1>Elementary Programming Computation</h1>

<h3>Programs</h3>
<p>Program adalah serangkaian instruksi yang mempunyai tujuan spesifik untuk melakukan komputasi(Computation). Ada dua 
komputasi yaitu General Computation dan Symbolic Computation. Source : Think Python - How to Think Like Computer Scientist</p>

<h4>General Computation</h4>
<p>Komputasi umum contohnya menyelesaikan permasalahan operasi penjumlahan matematika atau persamaan matematika.</p>

<h4>Symbolic Computation</h4>
<p>Komputasi simbolik contohnya mencari dan menimpa sebuah teks didalam sebuah dokumen, memproses suatu gambar atau video.</p>


<h3>Machine Language</h3>

<p>Pada tahun 1940 sampai 10 tahun berikutnya seorang programmer jika ingin membuat sebuah program masih harus menggunakan bahasa mesin. 
Mereka mengekspresikan program yang mereka buat dengan 1 dan 0.</p>

<p>101010101010101011010101010 .. n (just an example)</p>

<p>Akhirnya diciptakanlah sebuah bahasa yang bisa dimengerti lagi oleh para programmer agar mereka lebih bisa terfokus memecahkan masalah 
daripada fokus pada mengingat formula 1 dan 0. Bahasa tersebut adalah Bahasa <b>Assembly</b>, bahasa ini hampir dekat dengan bahasa mesin dengan 
ciri khas mnemonic pada setiap syntax bahasa assembly.</p>

<p>Seperti syntax Add(kependekan dari addition), Sub(kependekan dari subtraction), Sum (summarize) dan sbgainya berikut dengan storage locationya. 
Sehingga tidak lagi bermain di level bit binary digit. Sebagai contoh seorang programmer bisa langsung mengacu pada nilai sum tanpa harus mengingat 
nilai tersebut ada pada lokasi memori yang mana, misalkan alamat memory locationya terletak pada 1000011101. Enak bgt ya?</p>

<p>Selanjut sebuah <b>Assembler</b> akan menterjemahkan bahasa assembly kembali ke bahasa mesin. Meskipun begitu tetap ada beberapaSumber
kekurangan jika kita menggunakan bahasa assembly yaitu :</p>

<il>
<li>Bahasa masih kompleks dan rawan kesalahan.</li>
<li>Ini memaksa programmer untuk lebih terfokus pada mesin daripada masalah.</li>
<li>Sebuah program yang dibuat dengan bahasa mesin (machine language) tidak akan mampu berjalan pada komuter lainya yang memiliki machine language yang berbeda.</li>
</ul>

<h3>High Level Language</h3>

<p>Untuk menyelesaikan permasalahan ini diciptakanlah bahasa pemograman high level <b>(High Level Language Programming)</b> yang dikembangkan akhir tahun 1950-1960an.
Bahasa high level yang paling popular adalah <b>FOTRAN (FORmula TRANslation)</b> dan <b>COBOL (COmmon Business Oriented-Language)</b>. FOTRAN
diciptakan untuk menyelesaikan masalah <b>scientific dan engineering problems</b> yang berhubungan dengan <b>Numerical Computation</b>,
sementara COBOL lebih digunakan sebagai data-processing dalam komunitas bisnis.
</p>

<p>High Level Language Programming membantu programmer agar lebih bisa fokus berkonsentrasi pada masalah bukan pada target machine.
Sebuah program yang disebut dengan <b>Compiler</b> akan menterjemahkan High Level Language Programming ke Machine Language.</p>

<h3>How a Computer Executes a Program</h3>
<p>Agar komputer bisa mengeksekusi sekumpulan instruksi yang ada didalam suatu program, maka program harus dimuat dahulu
kedalam memory yaitu <b>primary storage</b> seperti pada gambar dibawah ini :</p>

<img src="https://github.com/PUSRISTEK/Learning-C/blob/master/image/memory.JPG"></img>

<p>Kita bisa membayangkan memori sebagai sebuah <b>Storage Location</b> tempat untuk menyimpan sekumpulan instruksi.
<b>Setiap Memory Location</b> menyimpan sebuah instruksi secara spesifik, Memory Location memiliki pengenal yang disebut 
dengan <b>Address</b> sebagai contoh instruksi A tersimpan di Address 99 dan instruksi B tersimpan di Address 6666.
Komputer akan mengeksekusi instruksi pertama, kedua, ketiga dan seterusnya secara sistematis, atau setelah menyelesaikan
satu instruksi langsung loncat ke beberapa instruksi sekaligus dan kembali lagi ke instruksi sebelumnya.</p>

Sumber : Buku Learn to Program with C Karya Noel Kalicharan buku terbitan tahun 2015.
