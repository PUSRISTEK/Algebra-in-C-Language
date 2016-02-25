# Play With C

<p>Dalam sebuah bahasa pemograman terdapat sebuah <b><i>Alphabet</i></b> atau secara umum biasa disebut <b><i>Character set</i></b> yang selanjutnya bisa digunakan untuk menciptakan sebuah <b><i>Words</i></b> tapi pada kasus ini kita akan menyebutnya dengan sebutan <b><i>Tokens.</i></b> Dengan <b><i>Tokens</i></b> kita akan membuat sebuah <b><i>Statements</i></b> dan dengan <b><i>Statements</i></b> kita akan membuat sebuah <b><i>Programs</i></b>. Semua itu disebut dengan <b><i>Syntax Rules</i></b> yang harus dipatuhi dan pasti dimiliki oleh setiap bahasa pemograman. Jika kita melanggarnya maka akan menimbulkan sebuah <b><i>Syntax Errors</i></b> </p>

<h3>4.1 C Alphabet</h3>
<p>C Alphabet terdiri dari seluruh <b><i>Characters</i></b> yang terdapat dalam <b><i>English Keyboard</i></b> mulai dari angka, aksara besar atau kecil, dan <b><i>Special Characters</i></b> seperti : +, =, <, >, &, dan % atau secara formal C menggunakan ASCII (American Standard Code for Information Interchange).</p>

<h3>4.2 Tokens</h3>
<p>Tokens dari suatu bahasa digunakan sebagai sekumpulan blok yang bisa digunakan untuk membuat sebuah <b>Statements</b> yang selanjutnya akan menjadi sebuah <b>Programs</b></p>. Sebuah <b><i>Tokens</i></b> bisa berupa <b><i>Reserved Keywords</i></b> seperti <b>int</b> atau <b>while</b>, atau sebuah <b><i>Identifier</i></b> seperti <b>x</b> atau <b>sum</b>, atau sebuah <b><i>Constant</i></b> seperti <b>20</b> atau <b>Maudy Sedang Belajar</b>, atau sebuah <b><i>Delimiter</i></b> seperti <b>)</b>, <b>}</b>, <b>;</b> atau sebuah <b><i>Operator</i></b> seperti <b>+</b> dan <b>=</b>.</p> 

<p>Sebagai contoh perhatikan program dibawah ini : </p>
```c
int main() {
int a, b, sum;
a = 14;
b = 20;
sum = a + b;
printf("%d + %d = %d\n", a, b, sum);
}
```

<p>int -> Reserved Keywords, main() -> identifier, { -> delimiter, a -> identifier, sum -> identifier, ; -> delimiter.</p>

<h4>4.2.1 Reserved keywords</h4>
<p>Bahasa C mempunyai daftar <b><i>Keywords</i></b> yang telah disediakan dan masing masing <b><i>Keywords</i></b> mempunyai arti dan tujuan. Sebagai contoh pada <b><i>Keywords</i></b> <b>int</b>, kita hanya bisa menggunakanya untuk memberi keterangan spesifik terhadap suatu data bahwa dia merupakan suatu <b><i>integer</i></b>. Seluruh <b><i>Keywords</i></b> ditulis dalam bentuk huruf kecil atau <b><i>Lowercase Letters</i></b> </p>
All keywords are written in lowercase letters only. Thus int is a keyword but Int and INT
are not. Keywords are reserved, that is, you cannot use them as your identifiers. As such, they are
usually called reserved words. A list of C keywords is given in Appendix A.

<b><i></i></b>

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
<li><b><i>Lowercase Letters</i><b></li>
</ul>
