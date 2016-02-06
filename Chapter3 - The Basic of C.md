<h1>The Basic of C</h1>

<h3>Simple Program</h3>
<p>Dibawah ini adalah contoh program sederhana menggunakan bahasa c untuk menampilkan pesan dilayar screen :</p>

```c
#include <stdio.h>
int main() {
printf("Welcome to Trinidad & Tobago");
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

