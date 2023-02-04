# Git & Github

- Apa itu git?

    >Git adalah sebuah version control system yang terdistribusi untuk mengelola perubahan file di dalam suatu folder atau repository.

- Apa itu Version Control System?

    >Version Control System (VCS) adalah sistem yang mengelola perubahan dari dokumen yang bisa berupa source code, website, dan file lain yang dibuat secara digital. Secara sederhana, VCS adalah sebuah sistem yang dapat mengelola perubahan dalam dokumen kita.

- Kenapa harus menggunakan VCS? Apa bedanya dengan penyimpanan cloud biasa seperti Google Drive atau Dropbox?

    >Kita menggunakan VCS agar dokumen dan file kita dapat terkelola secara rapi. Ditambah lagi, VCS dapat memudahkan kita untuk mengumpulkan hasil pekerjaan yang dilakukan secara kolaboratif.

    >VCS banyak digunakan untuk melakukan pekerjaan yang harus diupdate secara berkala. Penyimpanan cloud biasa kurang cocok untuk pekerjaan seperti ini karena tidak sefleksibel VCS yang dapat memperbarui suatu pekerjaan secara praktis.

- Apa saja keuntungan dalam menggunakan VCS?

    >- Dapat menyimpan rekaman perubahan setiap pekerjaan kita
    >- Memungkinkan pekerjaan kolaboratif yang lebih baik 
    >- Memungkinkan kita untuk merestorasi atau *roll back* perubahan yang telah dilakukan 

- Apa perbedaan menggunakan Git dengan menggunakan pengelola file manual?

    >Jika kita ingin membuat suatu perubahan menggunkaan pengelola file manual, kita tidak bisa langsung merubahnya begitu saja. Kita harus membuat salinan file dengan nama berbeda kemudian membuat perubahan disana. Sedangkan jika kita menggunakan Git, kita hanya menggunakan satu file saja. Nantinya Git akan merekam histori perubahan berdasarkan *commit* yang telah kita lakukan. Selain itu, Git juga akan merekam siapa yang melakukan, kapan, dan apa *message* dalam suatu *commit* sehingga lebih terorganisir.

    >Selain itu, dalam Git kita dapat menggunakan fitur bernama *branch*. *Branch* adalah fitur dalam Git yang memungkinkan kita untuk melakukan dua atau lebih pekerjaan secara bersamaan tanpa mengganggu jalur *commit* utama dari suatu *repository*. Nantinya jika *branch* yang telah dikerjakan ingin ditambahkan kedalam jalur *commit* utama, kita dapat menggabungkannya dengan menggunakan fitur lain yang bernama *merge*.

- Apa itu Github?

    >Github adalah webiste yang dapat mengelola sebuah project menggunakan version control system milik Github sendiri tanpa menggunakan VCS dari perangkat user. Jadi kita bisa menggunakan Github tanpa menggunakan Git.

    >Fitur VCS yang dimiliki Github sama dengan Git, yaitu bisa membuat *repo, commit, branch, merge*, dll. Bedanya adalah ini dilakukan secara online di dalam website Github.

    >Kita juga bisa menggabungkan penggunaan Git dengan Github. Jika digabung, maka kita dapat menghubungkan pekerjaan kita antara *repository* lokal dengan *repository* Github.

- Bagaimana cara menggabungkan penggunaan Git dengan Github?
    > 1. Buat *repository* di Github
    > 2. Lakukan *clone repository* ke penyimpanan lokal menggunakan Git

- Perintah dan istilah dalam Git
    >1. Repo/Repository  
    >Folder pekerjaan.

    >2. commit   
    >Rekaman dari pekerjaan kita saat keadaan tertentu.

    >3. hash       
    >Penanda unik untuk setiap *repository*.

    >4. checkout   
    >Berpindah ke sebuah *commit*.

    >5. branch  
    >Cabang bebas dari sebuah *commit*.

    >6. merge   
    >Menggabungkan *branch* yang telah dikerjakan.

    >7. remote  
    >Sumber yang memiliki *repo*, bisa berasal dari Github ataupun VCS lainnya.

    >8. clone  
    >Mengambil *repository* dari suatu *remote*.

    >9. push    
    >Mengirimkan *commit* ke suatu *repository*.

    >10. pull   
    >Mengambil *commit* ke suatu *repository*.