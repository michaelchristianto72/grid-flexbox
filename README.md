# grid-flexbox
study case for css grid and flexbox

*CSS Grid*: merupakan pembagian layout secara 2 dimensi (vertikal dan horizontal). 
Grid memiliki istilah seperti:
- "grid container" ketika diberi display: grid
- "grid item" yaitu children langsung dari "grid container"
- "grid line" yaitu garis pembagi untuk membuat struktur dari grid
- "grid cell" yaitu ruang diantara 2 baris dan 2 kolom yang berdekatan

**CSS Grid Property** yang digunakan:
- grid: shorthand dari properti grid-template-areas, grid-template-columns, grid-template-rows
- grid-template-areas: menjelaskan sebuah grid template dengan cara mereferensikan nama grid area menggunakan properti "grid-area". mengulangi nama grid-area di grid-template-areas akan membuat konten tersebut menyatu (merge)
- grid-area: memberikan nama ke item agar bisa direferensikan ke template 
- grid-template-columns: properti untuk menjelaskan banyaknya kolom di grid layout dan lebar dari kolom tersebut.
- grid-template-rows: properti untuk menjelaskan banyaknya baris di grid layout dan tinggi dari baris tersebut.

*CSS Flexbox*: merupakan pembagian layout secara 1 dimensi, dan sebagai metode yang memberikan distribusi ruang antar items. flexbox memiliki dua axis yaitu main axis dan cross axis (vertikal dan horizontal) yang dapat didefinisikan di flex-direction. namun, flexbox hanya dapat mengatur layout 1 dimensi saja, antara itu row atau column.

**CSS Flexbox Property** yang digunakan:
- flex-grow: menentukan kemampuan flex item untuk "mengembang". contohnya jika semua items diberi flex-grow: 1, maka sisa lebar space akan diisi oleh lebar items secara merata.
- flex-direction: menjelaskan arah dari flex items di dalam flex container
- order: flex items akan diatur sesuai urutan yang akan muncul di dalam flex container