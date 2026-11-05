# Orbit — Kalkulator Grafik

Kalkulator ilmiah dan grafik interaktif yang berjalan langsung di browser, tanpa instalasi dependensi.

## Fitur

- Kalkulator ilmiah dengan operasi dasar, pangkat, faktorial, konstanta `pi` dan `e`, serta fungsi trigonometri dan matematika.
- Mode sudut radian dan derajat, riwayat jawaban terakhir melalui `Ans`, dan dukungan tombol keyboard.
- Plot beberapa fungsi sekaligus, termasuk `sin(x)`, `x^2 - 3`, dan `1/x`.
- Kanvas grafik interaktif dengan grid koordinat, geser, zoom, dan pengaturan ulang tampilan.
- Desain responsif, efek tombol 3D, dan parser ekspresi tanpa `eval`.

## Menjalankan aplikasi

### Laragon / PHP

Letakkan folder ini di direktori web Laragon, lalu buka `http://localhost/kalkulator/`. `index.php` akan mengarahkan ke aplikasi `index.html`.

### Tanpa server

Buka `index.html` langsung di browser.

### GitHub Pages

Aplikasi dapat dipublikasikan sebagai situs statis dari branch utama karena `index.html`, CSS, dan JavaScript tidak memerlukan backend.

## Ekspresi yang didukung

Operator: `+`, `-`, `*`, `/`, `^`, faktorial `!`, kurung, dan perkalian implisit seperti `2x`.

Konstanta: `x`, `pi`, `e`, `Ans`.

Fungsi satu argumen: `sin`, `cos`, `tan`, `asin`, `acos`, `atan`, `sinh`, `cosh`, `tanh`, `sqrt`, `cbrt`, `abs`, `ln`, `log`, `log2`, `exp`, `floor`, `ceil`, `round`, dan `sign`. Fungsi `min` dan `max` menerima satu atau lebih argumen.

Fungsi trigonometri mengikuti mode sudut yang dipilih. Pangkat menggunakan `^`, misalnya `x^2` atau `2^3`.
