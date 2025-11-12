No.,Perintah (Command),Keterangan / Fungsi
1.,mkdir project_sistem_operasi_B,Membuat direktori (folder) baru bernama project_sistem_operasi_B di lokasi saat ini (/home/imin/).
2.,cd project_sistem_operasi_B,"Mengubah direktori (Change Directory). Masuk ke dalam direktori yang baru dibuat, yaitu project_sistem_operasi_B. Semua perintah selanjutnya akan dijalankan dari dalam direktori ini."
3.,mkdir src doc data,"Membuat tiga direktori (folder) sekaligus di dalam project_sistem_operasi_B: src, doc, dan data."
4.,touch README.md src/main.sh,Membuat dua file kosong: README.md di direktori saat ini (project_sistem_operasi_B) dan main.sh di dalam sub-direktori src.
5.,du -h ./project_sistem_operasi_B,Menampilkan penggunaan ruang disk (Disk Usage) dari direktori project_sistem_operasi_B dan semua isinya. Opsi -h (human-readable) membuat ukuran ditampilkan dalam format yang mudah dibaca (misalnya K untuk Kilobytes).