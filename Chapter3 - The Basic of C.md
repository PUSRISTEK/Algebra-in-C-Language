<h1>The Basic of C</h1>

<h3>Simple Program</h3>
<p>Dibawah ini adalah contoh program sederhana menggunakan bahasa c untuk menampilkan pesan dilayar screen :</p>

```c
#include <stdio.h>
int main() {
printf("Hello World");
}
```

<p>Statement</p>
```c
#include <stdio.h>
```

<p>Disebut sebagai <b>Compiler Directive</b> secara sederhana isinya menyediakan segala hal yang dibutuhkan oleh program
sebelum kita melakukan kompilasi. Dalam C, proses input dan output disediakan dalam standar fungsi tersebut, setiap program 
yang akan menggunakan proses input dan output seperti <b>keyword printf</b> harus melampirkan library stdio.h</p>

<p>Sebuah program dalam C terdiri dari 1 atau lebih <b>Function</b> salah satu fungsi harus bernama <b>main()</b>.
Dua tanda kurung setelah keyword main sangat penting karena didalamnya akan menjadi tempat untuk menyimpan sebuah <b>Arguments</b>.
Meskipun fungsi tidak memiliki Arguments tanda kurung tersebut harus tetap ada, kemudian keyword <b>int</b> sebelum 
keyword main mengindisikasikan nilai balik <b>(returned value)</b> dalam fungsi main. Setiap fungsi memiliki <b>body of function</b>
yang didalamnya terdapat instruksi yang akan dilakukan.
</p>

<p>Kita bisa mengkompilasi code diatas menggunakan gcc dengan perintah dibawah ini :</p>

```
cd C:\
```
<p>Simpan terlebih dahulu code di drive C, kemudian pada CLI compile code tersebut :</p>

```
gcc helloworld.c -o hello.exe
```

<p><b>Option -o</b> agar kita bisa memberi nama pada output executable yang dihasilkan.</p>

<h3>Write Output with printf</h3>

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
<p></p>

<h3>Comments</h3>
<p>Seluruh bahasa pemograman yang ada didunia ini memiliki cara tersendiri dalam memberikan sebuah comment.
Hal ini digunakan untuk menjelaskan program yang telah kita buat atau penjelasan dari setiap baris kode yang
telah kita buat. Dibawah ini adalah contoh penggunaan comment pada C :</p>

```c
/* Komentar disini */
```


