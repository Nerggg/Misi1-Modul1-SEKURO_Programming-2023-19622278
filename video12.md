# .gitignore

- Apa itu .gitignore?

    >File yang bisa kita tambahkan dalam repository kita agar nantinya ketika kita melakukan add dan commit, file tersebut tidak terbawa oleh add dan commit-nya.

- Bagaimana cara menambahkan .gitignore kedalam repository kita?

    >Cukup buat file bernama `.gitignore` kedalam folder repository kita.

- Bagaimana cara menambahkan file atau folder?

    >1. Untuk menambahkan file, ketik nama filenya dalam `.gitignore`
    >2. Untuk menambahkan folder, ketik `<nama folder>/` dalam `.gitignore`

    >Contohnya adalah seperti [ini](17.png). Pada screenshot tersebut, saya menambahkan folder `old` dan file `beatrix.cpp`. Ketika saya menambahkan keduanya kedalam `.gitignore` dan melakukan add pada terminal, kedua file tersebut akan diabaikan oleh Git sehingga tidak ikut ditambahkan.