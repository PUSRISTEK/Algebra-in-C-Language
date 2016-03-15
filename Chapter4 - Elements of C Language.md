# Elements of C Language

<p>Dalam sebuah bahasa pemograman terdapat sebuah <b><i>Alphabet</i></b> atau secara umum biasa disebut <b><i>Character set</i></b> yang selanjutnya bisa digunakan untuk menciptakan sebuah <b><i>Words</i></b> tapi pada kasus ini kita akan menyebutnya dengan sebutan <b><i>Tokens.</i></b></p> 

<p>Dengan <b><i>Tokens</i></b> kita akan membuat sebuah <b><i>Statements</i></b> untuk membuat sebuah <b><i>Programs</i></b>. <b><i>Programs</i></b> diatur menggunakan sebuah <b><i>Syntax Rules</i></b> yang harus dipatuhi dan pasti dimiliki oleh setiap bahasa pemograman. Jika kita melanggarnya maka akan menimbulkan sebuah <b><i>Syntax Errors</i></b> </p>

<h3>4.1 C Alphabet</h3>
<p>C Alphabet terdiri dari seluruh <b><i>Characters</i></b> yang terdapat dalam <b><i>English Keyboard</i></b> mulai dari angka, huruf besar atau kecil, dan <b><i>Special Characters</i></b> seperti : +, =, <, >, &, dan % atau secara formal C menggunakan ASCII (American Standard Code for Information Interchange). Adapun penjelasan lebih detailnya :</p>

<ul>
<li><b><i>Digits</i></b> dimulai dari angka 0 sampai angka 9</li>
<li><b><i>Uppercase Letters</i></b> dimulai dari huruf A sampai Z</li>
<li><b><i>Lowercase Letters</i></b> dimulai dari huruf a sampai z</li>
<li><b><i>Special Symbols</i></b> seperti (, ), $, =, <, >, +, -, /, *, dan sebagainya</li>
<li><b><i>Letter</i></b> mengacu kepada a sampai z atau A sampai Z</li>
<li><b><i>Alphabetic</i></b> mengacu kepada <b><i>Letter</i></b></li>
<li><b><i>Numeric</i></b> mengacu kepada <b><i>Digits</i></b></li>
<li><b><i>Alphanumeric</i></b> mengacu kepada <b><i>Digits</i></b> atau <b><i>Letter</i></b></li>
</ul>

<h3>4.2 Tokens</h3>
<p>Tokens adalah sekumpulan blok dari suatu bahasa pemograman yang digunakan untuk membuat sebuah <b>Programs</b>. Sebuah <b><i>Tokens</i></b> bisa berupa :</p>

<ul>
<li><b><i>Reserved Keywords</i></b> seperti <b>int</b> atau <b>while</b></li> 
<li><b><i>Identifiers</i></b> seperti <b>x</b> atau <b>sum</b></li>
<li><b><i>Literals/Constants</i></b> seperti <b>20</b> atau <b>Maudy Sedang Belajar</b></li> 
<li><b><i>Delimiters</i></b> seperti <b>)</b>, <b>}</b>, <b>;</b></li> 
<li><b><i>Operators</i></b> seperti <b>+</b> dan <b>=</b>.</li> 
</ul>

<p>Sebagai contoh perhatikan program dibawah ini : </p>
```c
int main() {
int a, b, jumlah;
a = 14;
b = 20;
jumlah = a + b;
printf("%d + %d = %d\n", a, b, jumlah);
}
```

<p>int -> Reserved Keywords, main() -> identifier, { -> delimiter, a -> identifier, sum -> identifier, ; -> delimiter.</p>

<h4>4.2.1 Reserved keywords</h4>
<p>Bahasa C mempunyai daftar <b><i>Keywords</i></b> yang telah disediakan dan masing masing <b><i>Keywords</i></b> mempunyai arti dan tujuan. Sebagai contoh pada <b><i>Keywords</i></b> <b>int</b>, kita hanya bisa menggunakanya untuk memberi keterangan spesifik terhadap suatu data bahwa dia merupakan suatu <b><i>integer</i></b>. Seluruh <b><i>Keywords</i></b> ditulis dalam bentuk huruf kecil atau <b><i>Lowercase Letters</i></b>, dengan begitu kita tidak bisa menggunakan <b><i>Keywords</i></b> sebagai sebuah <b><i>Identifiers.</i></b> itulah alasan mengapa kita menyebutnya dengan sebutan <b><i>Reserved Keywords</i></b>, dibawah ini adalah list 40 lebih <b><i>Reserved Keywords</i></b> yang ada didalam bahasa c :</p>

<img src="https://github.com/PUSRISTEK/Learning-C/blob/master/image/reserved-keywords.JPG">

<h4>4.2.2 Identifiers</h4>
<p><b><i>Identifiers</i></b> adalah sebuah nama yang diberikan untuk sebuah <b><i>Variables</i></b>, <b><i>Functions</i></b> atau pada sebuah <b><i>Symbolic Constants</i></b>. Penamaan <b><i>Identifiers</i></b> memiliki tata cara yang harus diikuti, ada dua cara ntuk membuat sebuah <b><i>Identifiers</i></b> diantaranya adalah diawali dengan sebuah huruf atau <b><i>Underscores</i></b> dan jika kita membutuhkan karakter lainya kita bisa mengkombinasikan <b><i>Digits</i></b>, <b><i>Letters</i></b> dan <b><i>Underscores</i></b> dengan batas panjang sekitar 63 <b><i>Characters</i></b></p>

<ul>
<p>Contoh membuat sebuah <b><i>Identifiers.</i></b></p>
<li>r</li>
<li>R</li>
<li>sum1</li>
<li>_TEST</li>
<li>camelCase</li>
<li>Double_Unders_core</li>
<li>A1A2</li>
</ul>

<ul>
<p>Contoh <b><i>Identifiers.</i></b> yang salah :</p>
<li>2Abs <- karena diawali dengan digits</li>
<li>asd xyz <- karena terdapat spasi</li>
<li>fox;trot <- karena terdapat <b><i>Invalid Character</i></b> -> ;</li>
</ul>

<h4>4.2.3 Variables</h4>
<p><b><i>Variables</i></b> adalah sebuah tempat untuk menyimpan suatu nilai. <b><i>Variables</i></b> tersimpan dalam sebuah <b><i>Main Memory</i></b> yang biasa digunakan untuk menyimpan suatu tipe data saat <b><i>programs</i></b> sedang dieksekusi. Nama <b><i>Variables</i></b> adalah nama yang diberikan untuk menyimpan
<b><i></i></b>



<p>Terlebih bahasa C adalah bahasa yang memiliki karakteristik <b><i>Case Sensitive</i></b> jadi jika terdapat sebuah <b><i>Identifiers</i></b> a maka ia tidak sama dengan A dan sum tidak sama dengan Sum atau SuM. </p>

<p>Misal kita ingin membuat sebuah program untuk menampilkan sebuah quote menggunakan <b>printf</b> :</p>

```c
#include <stdio.h>
int main() {
printf("Men are driven by two principal impulses, either by love or by fear.");
printf("- Machiavelli");
}
```
<p>Maka akan mengeluarkan sebuah output yaitu :</p>

```
Men are driven by two principal impulses, either by love or by fear. - Machiavelli
```

<p>Kedua string tersebut menyatu atau secara coding disebut dengan <b>Concatenated</b> dikarenakan
keyword printf tidak menemputkan output selanjutnya pada garis baru <b>New Line</b> kecuali diatur secara eksplisit.
Dengan kata lain printf tidak menyediakan garis baru secara otomatis setelah mengeksekusi argumen yang ada didalamnya.</p>

<h3>New Line Character</h3>
<p>Agar program yang kita buat menggunakan keyword printf mampu membuat New Line kita bisa menggunakan \n(backslash n)/
Dibawah ini adalah contoh source code programnya :</p>

```c
#include <stdio.h>
int main() {
printf("Barangsiapa tidak mau merasakan pahitnya belajar, Ia akan merasakan hinanya kebodohan sepanjang hidupnya.\n");
printf("- Imam Syafi'i\n");
}
```

<p>Backslash n akan menghentikan output sehingga tercipta garis baru untuk subsequent output (output selanjutnya).
Sehingga akan menghasilkan output :</p>

```
Barangsiapa tidak mau merasakan pahitnya belajar, Ia akan merasakan hinanya kebodohan sepanjang hidupnya.
- Imam Syafi'i
```

<h3>Escape Sequences</h3>
<p>Penggunaan Escape Sequences sangat penting untuk arguments pada keyword printf. Sebuah backslash (\) yang diikuti 
sebuah charater akan mempunyai fungsi tersendiri pada output. Sebagai contoh :</p>

<ul>
<li>\n -> untuk garis baru.</li>
<li>\t -> untuk tab</li>
<li>\" -> untuk double quote</li>
<li>\\ -> untuk \</li>
</ul>

<p>Sebagai contoh jika kita ingin menambahkan efek double quote pada program dibawah ini kita bisa menggunakan
Escape Sequences :</p>

```c
#include <stdio.h>
int main() {
printf("\"Barangsiapa tidak mau merasakan pahitnya belajar, Ia akan merasakan hinanya kebodohan sepanjang hidupnya.\"\n");
printf("- Imam Syafi'i\n");
}
```

<p>Maka Outputnya :</p>

```
"Barangsiapa tidak mau merasakan pahitnya belajar, Ia akan merasakan hinanya kebodohan sepanjang hidupnya."
- Imam Syafi'i
```

<h3>Print the Value of a Variable</h3>
<p>Sebelumnya kita telah mempelajari bagaimana cara print value sebuah string, sekarang kita akan melakukan print value 
dari sebuah variable. Dikatakan bahwa m adalah 77 maka untuk menampilkannya menggunakan keyword printf perhatikan code dibawah ini : </p>

```c
printf("Jumlah ikan yang ada dikolam adalah = %d\n", m);
```

<p>Maka outputnya adalah :</p>

```
Jumlah ikan yang ada dikolam adalah = 77
```
<p>Pada statement code diatas kita bisa melihat format specification %d untuk menampung sebuah nilai <b>integer</b>.
Dibawah ini adalah contoh program memasukan lebih dari 1 format specification %d pada keyword printf :</p>

```
printf("Total Penjumlahan dari %d dan %d adalah %d\n", a, b, a + b);
```

<p>Pada keyword printf diatas didalamnya terdapat empat arguments, 1 adalah sebuah argument format string dan 3 lagi adalah arguments
yang menampung sebuah nilai dari suatu variable. Jika a = 1, b = 2 maka outputnya adalah :</p>

```
Total Penjumalahan dari 1 dan 2 adalah 3
```

<h3>Programming with Variables</h3>
<p>Sekarang kita akan mencoba membuat sebuah program sederhana untuk menjumlahkan dua buah bilangan, sehingga 
agar kita bisa mengetahui hasilnya kita membutuhkan 3 buah variable dengan tipe data integer. Perhatikan source program dibawah ini :</p>

```c
#include <stdio.h>
int main() {
int a, b, sum;
a = 14;
b = 25;
sum = a + b;
printf("%d + %d = %d\n", a, b, sum);
}
```

<p>Jika dieksekusi maka hasilnya adalah : </p>

```
14 + 25 = 39
```

<h3>Comments</h3>
<p>Seluruh bahasa pemograman yang ada didunia ini memiliki cara tersendiri dalam memberikan sebuah comment.
Hal ini digunakan untuk menjelaskan program yang telah kita buat atau penjelasan dari setiap baris kode yang
telah kita buat. Dibawah ini adalah contoh penggunaan comment pada C :</p>

```c
/* Komentar disini */
```


<ul>
<p><b>Glossary</b></p>
<li><b><i>Alphabet</i><b></li>
<li><b><i>Character Set</i><b></li>
<li><b><i>Tokens</i><b></li>
<li><b><i>Statements</i><b></li>
<li><b><i>Programs</i><b></li>
<li><b><i>Syntax Rules</i><b></li>
<li><b><i>Syntax Errors</i><b></li>
<li><b><i>Special Characters</i><b></li>
<li><b><i>Reserved Keywords</i><b></li>
<li><b><i>Identifiers</i><b></li>
<li><b><i>Constants</i><b></li>
<li><b><i>Delimiters</i><b></li>
<li><b><i>Operators</i><b></li>
<li><b><i>Variables</i><b></li>
<li><b><i>Functions</i><b></li>
<li><b><i>Symbolic Constants</i><b></li>
<li><b><i>Underscores</i><b></li>
<li><b><i>Letters</i><b></li>
<li><b><i>Digits</i><b></li>
<li><b><i>Lowercase Letters</i><b></li>
<li><b><i>Invalid Character</i></b></li>
<li><b><i>Case Sensitive</i></b></li>
</ul>
