# Bekerja dengan Git

- Bagaimana cara menginstall Git?

    >1. Buka git-scm.com
    >2. Download sesuai dengan sistem operasi kita
    >3. Buka installer, kemudian lakukan pengaturan terhadap penginstallan sesuai preferensi kita

- Apa saja area pada repo Git?

    >1. Working Tree
    >Folder tempat kita bekerja
    >2. Staging Area
    >Letak file yang telah diubah
    >3. History
    Letak file yang telah dicommit

- Bagaimana cara membuat suatu folder lokal menjadi repository Git?

    >1. Buka terminal di folder yang ingin kita jadikan repository
    >2. Ketik `git init` seperti [ini](1.png)

- Bagaimana cara menambahkan file kedalam staging area?

    >1. Ketikkan `git status` dalam terminal terlebih dahulu untuk memeriksa apakah ada file yang berubah
    >2. Ketik `git add <nama file>` untuk menambahkan file yang ada perubahannya ke dalam staging area. Jika dilakukan maka akan seperti [ini](2.png)

- Bagaimana cara melakukan commit file yang ada di staging area?

    >Ketik `git commit -m <pesan commit>` pada terminal kemudian ketik `git status` seperti [ini](3.png) untuk mengecek apakah sudah benar-benar tercommit atau belum.

- Bagaimana cara menambahkan semua file yang berubah sekaligus ke dalam staging area?

    >1. Ketik `git status` untuk memeriksa perubahan file
    >2. Ketik `git add .` untuk menambahkan semua file yang berubah ke dalam staging area. Jika dilakukan maka akan seperti [ini](4.png)

- Bagaimana cara melihat history commit kita?

    >Ketik `git log` seperti [ini](5.png)

- Bagaimana cara mundur ke history commit tertentu?

    >1. Pada tampilan `git log`, tentukan akan ke commit yang mana kita mundur
    >2. Ketik `git checkout <5 digit hash pertama>` untuk mundur ke commit yang memiliki 5 digit hash tersebut. Contohnya seperti [ini](6.png). Pada contoh tersebut, saya kembali ke keadaan commit pertama, jadi file `helloWorld.cpp` dan `byeWorld.cpp` yang saya tambahkan hilang.