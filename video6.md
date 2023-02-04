# Git Branch & Merge

- Bagaimana cara melihat ada branch apa saja dalam repository kita?

    >1. Buka terminal dalam repository kita
    >2. Ketik `git branch`

- Bagaimana cara membuat branch baru dalam repository kita?

    >1. Buka terminal dalam repository kita
    >2. Ketik `git branch <nama branch baru>`

    >Implementasi pertanyaan satu dan dua adalah seperti [ini](ss/7.png)

- Bagaimana cara pindah ke branch lain?

    >Ketik `git checkout <nama branch tujuan>` seperti [ini](ss/8.png)

    >Nantinya setelah kita pindah ke branch lain, kita dapat mengerjakan file pada branch tersebut tanpa memengaruhi branch lain. Contohnya adalah seperti [ini](ss/9.png).

    >Pada screenshot tersebut, saya menambahkan file `fibonacci.cpp` pada branch `update`. Kemudian saat saya berpindah ke branch `master`, file tersebut tidak ada karena saya hanya menambahkannya ke branch `update` saja.

- Bagaimana cara melakukan merge dalam Git?

    >1. Lakukan `checkout` terlebih dahulu ke branch `master`
    >2. Ketik `git merge <nama branch yang ingin digabung>`
    Contohnya seperti [ini](ss/10.png).

- Bagaimana cara mengecek branch apa saja yang telah di merge?

    >Ketik `git branch --merged` seperti [ini](ss/11.png)

- Bagaimana cara menghapus suatu branch dalam Git?

    >Ketik `git branch -d <nama branch yang ingin dihapus>`
    >Contohnya adalah seperti [ini](ss/12.png).