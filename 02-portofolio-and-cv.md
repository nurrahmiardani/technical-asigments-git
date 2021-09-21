1. membuat sebuah folder kosong dengan namamu sendiri
    mkdir nurrahmi
2. membuat sebuah file dengan nama README.md, isi file tersebut dengan kalimat "Halo perkenalkan aku halaman utama"
    vim README.md
3. insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan "Inisialisasi Git Repository"
    git init
    git add .
    git commit -m "inisialisasi git repository"
4. buat branch baru dengan nama cv, hal ini berguna agar histori kita tidak tercampur
    git branch cv
5. pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat: "Ini adalah file CV"
    git checkout cv
    vim cv.txt
6. kemudian dokumentasikan menggunakan commit dengan pesan "Inisialisasi CV"
    git add .
    git commit -m "inisialisasi cv"
7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan commit
    git commit -m "menambahakn perusahaan pertama" 
    git commit -m "menambahakn perusahaan kedua"
    git commit -m "menambahakn perusahaan ketiga"
8. kembali ke branch master
    git chehckout master
9. ubah file README.md jangan lupa untuk mendokumentasikannya menggunakan commit dengan pesan "update master pertama"
    git add .
    git commit -m "update master pertama"
10. gabungkan branch cv kedalam branch master menggunakan perintah git merge
    git merge cv
11. unggah Git Repository tersebut kedalam GitHub
    git push -u origin master