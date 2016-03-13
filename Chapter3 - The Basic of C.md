# The Basic of C

<h3>3.1 Simple Program</h3>
<p>Dibawah ini adalah contoh program sederhana menggunakan bahasa c untuk menampilkan pesan dilayar screen :</p>

```c
#include <stdio.h>
int main() {
printf("Hello World");
}
```

<p>Dibawah ini adalah contoh program sederhana hasil dari penerjamahan <b>Pseudocode</b> pada <b>Chapter 2.6 :</b></p></p>

```c
#include<stdio.h> /* menggunakan fungsi printf() & scanf() yang ada di stdio.h */
#include<conio.h> /* menggunakan fungsi getch() yang ada di conio.h */
main() /* Starting point tempat program akan dieksekusi*/
{
int a,b,jumlah; /* Deklarasi Variabel */
printf("Masukan dua angka : "); /* Permintaan Input */
scanf("%d %d",&a,&b); /* Input dari user */
jumlah=a+b; /* Jumlahkan kedua variabel */
printf("jumlah = %d",jumlah); /* Tampilkan hasil */
getch(); /* untuk mencegah output screen menutup */
} 
```

<h3>3.2 Header</h3>

<p>Statement</p>
```c
#include <stdio.h>
```
<p>Disebut sebagai <b>Compiler Directive</b> secara sederhana isinya menyediakan segala hal yang dibutuhkan oleh program
sebelum kita melakukan kompilasi. Dalam C, proses input dan output disediakan dalam standar fungsi tersebut, setiap program 
yang akan menggunakan proses input dan output seperti <b>keyword printf</b> harus melampirkan library stdio.h menggunakan <b>pre-processor statement #include</b>.</p>

<p><i><b>The Angle Brackets < > </b></i> menginformasikan <i><b>Compiler</b></i> untuk mencari <i><b>Include Directory</b></i> tempat seluruh header bawaan disimpan. Jika kita membuat header sendiri dengan <i><b>Path Directory</b></i> yang berbeda kita bisa menggunakan <i><b>Double Quote</b></i></p>

<p>Statement</p>
```c
#include path\stdio.h"
```

<h3>3.3 Main Function</h3>
<p>Sebuah program dalam C terdiri dari 1 atau lebih <b>Function</b> salah satu fungsi harus bernama <b>main()</b> dikarenakan fungsi <b>main()</b> adalah tempat program untuk dieksekusi pertama kali. Dua tanda kurung () setelah fungsi <b>main()</b> sangat penting karena didalamnya adalah tempat untuk menyimpan sebuah <b>Arguments.</b> Meskipun begitu khusus fungsi <b>main()</b> dia tidak memiliki <b>Arguments</b> namun tanda kurung tersebut harus tetap ada, kemudian keyword <b>int</b> sebelum fungsi <b>main()</b> mengindisikasikan nilai balik <b>(returned value)</b> dalam fungsi main yaitu sebuah integer. Jika tidak terdapat fungsi <b>main()</b> maka program tidak akan bisa dikompilasi. 
</p>

<h3>3.4 Printf & Scanf Function</h3>
<p>Dalam bahasa c <b>Printf Function</b> adalah fungsi standar yang digunakan untuk menampilkan sebuah output, fungsi printf dapat digunakan jika kita telah melampirkan <b>Library stdio.h</b> sementara <b>Scanf Function</b> adalah fungsi untuk untuk membaca input keyboard. <b>Format Specifier %d</b> digunakan untuk untuk membaca nilai input pada keyboard sebagai <b>integer</b>, jika terdapat lebih dari satu <b>Format Specifier %d</b> maka artinya ada lebih dari satu variabel untuk menyimpan suatu nilai. Pada contoh program diatas <b>&a dan &b</b> adalah variabel yang digunakan untuk menyimpan input dari dua <b>Format Specifier %d</b>, symbol <b>&</b> mempunyai peran penting dalam <b>Scanf Function</b> agar kita bisa mengubah nilai suatu variabel dan biasa disebut sebagai <b>Ampersand</b></p>

<h3>3.4 Printf & Scanf Function</h3>
