# Github : Branch

- Apa itu Branch dalam Github?

    >Branch adalah cabang commit atau snapshot dalam suatu repository yang tidak memengaruhi commit pada master branch atau branch utama.

- Ketika kapan kita menggunakan Branch?

    >1. Ketika kita sedang mengembangkan fitur yang eksperimental atau yang belum pasti
    >2. Ketika ada dua orang atau lebih yang mengerjakan repo yang sama

- Bagaimana cara membuat Branch di Github?

    >Cara Pertama
    >1. Buat file baru atau edit file yang sudah ada
    >2. Pada bagian *commit changes*, tandai bagian *Create a new branch for this commit*

    >Cara Kedua 
    >1. Buka repository yang ingin dibuat branch
    >2. Tekan dropdown branch yang ada di bagian kiri atas
    >3. Ketik nama branch yang ingin dibuat
    >4. Klik *create branch*

>Ketika kita berada di branch selain master branch, maka ketika kita hendak melakukan commit, commit tersebut akan dilakukan menuju branch yang kita buka sebelumnya. Jadi segala perubahan yang ada di branch ini tidak akan memengaruhi master branch atau branch utama.

- Bagaimana cara menggabungkan (merge) branch utama dengan branch yang lain?

    >1. Buka branch yang ingin digabung dengan branch utama
    >2. Klik tombol *Compare & pull request*
    >3. Pastikan ada centang hijau dengan kalimat *Able to merge*
    >3. Isi pesan pull request
    >4. Klik *Create pull request*
    >5. Pindah ke tab *Pull requests*
    >6. Tekan pull request yang kita masukkan tadi
    >7. Klik *Merge pull request* kemudian *Confirm merge*

- Bagaimana cara menghapus suatu branch?

    >1. Buka repository yang ingin kita hapus branchnya
    >2. Klik *branches*
    >3. Klik ikon tong sampah pada branch yang ingin kita hapus

- Bagaimana jika branch yang ingin dimerge tidak bisa digabung secara otomatis?

    >1. Setelah dilakukannya pull request, buka tab *Pull requests* 
    >2. Pada branch yang ingin digabung, klik *Resolve conflicts*
    >3. Kita akan diarahkan pada text editor
    >4. Edit file yang berkonflik 
    >5. Jika dirasa konfliknya sudah tidak ada, klik *Mark as resolved*
    >6. Klik *Commit merge* 
    >7. Klik *Merge pull request* kemudian *Confirm merge*