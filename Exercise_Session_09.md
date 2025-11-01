# Refleksi Soal Pengaplikasian Turunan

Nama: Yohanes Bandung Bondowoso
NIM : 01085250015

Saya sedikit memahami pengaplikasian turunan dari file _slides_ yang diberi Bu Marta.

## Rate Equations

Di beberapa sesi sebelumnya, Bu Marta sempat memberi petunjuk bahwa salah satu kegunaan dari belajar turunan adalah untuk mencari tahu percepatan dari perubahan posisi objek.

Salah satu hal yang menarik dan saya langsung kenali adalah 'Teorema Pythagoras' yang ada di contoh **Example 2**: $s^2 = x^2 + y^2$.

Pada contoh tersebut, ada pengaplikasian pencarian kecepatan mobil tersangka jika diketahui posisi mobil polisi, posisi mobil tersangka dan jarak antar keduanya dan semua di waktu $t$. Rumusnya adalah turunan dari 'Teorema Pythagoras' di atas:
$$2s{ds \over dt} = 2x{dx \over dt} + 2y{dy \over dt}$$
Pada contoh tersebut, tiap variable diturunkan atas nilai $t$. Atau ditulis dengan bentuk lebih mudah:
$$2ss' = 2xx' + 2yy'$$


Saya langsung mengenali rumus Pythagoras karena salah satu fundamental matematika bangun datar.



Saya juga mengenali rumus volume kerucut pada contoh **Example 3**: $V = {1 \over 3}\pi x^2y$. Pada contoh, berarti nilai $x$ adalah ruas lingkaran alas kerucut, dan nilai $y$ adalah tinggi.

### Exercise 1
Saya coba kerjakan soal **Exercise 1**:
Diketahui rumus $V=IR$, $V$ meningkat pada $1volt/detik$, $I$ berkurang pada ${1 \over 3} amp/detik$, $t$ adalah waktu dalam detik, dan $R$ tidak diketahui.

1. nilai dari $dV/dt$, karena nilainya konstan jadi $1volt/detik$
2. nilai dari $dI/dt$, karena nilainya juga konstan namun berkurang, jadi $-{1 \over 3} amp/detik$
3. rumus untuk menemukan $dR/dt$, namun saya akan tulis dengan $R'$ agar lebih mudah.
Karena rumus $V$ adalah perkalian, maka saya gunakan aturan $(uv)'=u'v+uv'$.
Jadi, rumus awal $V=IR$ menjadi $V'=I'R+IR'$.
Karena kita mencari $R'$, maka kita ubah posisi dan menghasilkan
$$R'={V'-I'R \over I}$$
4. untuk percepatan perubahan, saya kerjakan di kertas (karena sulit di sini 😇).
Diketahui $V=12volt$ dan $I=2amp$. Maka $R={V \over I} = {12 \over 2} = 6ohm$
Dari jawaban (1), mendapat $V'=1volt/detik$
Dari jawaban (2), mendapat $I'=-{1 \over 3} amp/detik$
Substitusikan jadi
$$R'={1-(-{1 \over 3})6 \over 2}$$
Menghasilkan $1,5ohm/detik$. Nilainya bertambah (_increasing_).

### Exercise 4
Saya coba kerjakan soal **Exercise 4**:
Diketahui kecepatan naik balon ($y'$) pada $y'=1ft/detik$
Saat tinggi balon $y=65ft$ kecepatan sepeda ($x'$) pada $x'=17ft/detik$ di arah $x$.
Rumus mencari jarak dengan Teorema Pythagoras.
Dicari kecepatan perubahan jarak balon dengan sepeda ($s'$) setelah 3 detik.

Maka setelah 3 detik, status mereka berubah menjadi:
Ketinggian balon $y = 65+3 = 68ft$
Posisi sepeda $x = 17 \times 3 = 51ft$
Jarak diagonal $s = \sqrt{x(t)^2 + y(t)^2} = \sqrt{51^2 + 68^2} = \sqrt{2601 + 4624} = \sqrt{7225} = 85ft$

Kita menggunakan rumus turunan Teorema Pythagoras yang saya sudah tulis di atas, dengan bentuk penulisan mudah: $2ss' = 2xx' + 2yy'$.

Maka saya sederhanakan jadi $ss' = xx' + yy'$. Lalu pindah ruas $s' = {xx' + yy' \over s}$.

Substitusikan jadi
$$s' = {51 \times 17 + 68 \times 1 \over 85} = {867 + 68 \over 85} = {935 \over 85} = 11$$

Menghasilkan $11ft/detik$. Nilainya bertambah (_increasing_).


## Extreme Values of Functions

Untuk materi kedua **Extreme Values of Functions**, saya masih berusaha untuk memahami. Apakah ini berhubungan dengan implementasi dari Limit? Saya menunggu kesempatan kuliah _synchronous_ bersama Bu Marta agar bisa dijelaskan lebih lanjut.

Terima kasih sebelumnya :)

---

> Penulisan artikel refleksi ini menggunakan NeoVim dan Markdown yang diperkaya MathJax.
> Terinspirasi dari artikel oleh [Gilles Castel - How I'm able to take notes in mathematics lectures using LaTeX and Vim](https://castel.dev/post/lecture-notes-1/), namun karena $\rm\LaTeX$ sulit dipelajari, saya menggunakan Markdown.
