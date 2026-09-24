PENJELASAN PROGRAM PENILAIAN DAN KELULUSAN MAHASISWA

Di program ini, pertama saya memasukkan nama peserta, nilai tugas, nilai kuis, nilai ujian, dan kehadiran. Semua data itu disimpan ke variabel masing-masing supaya nanti bisa dipakai di program.
Untuk nilai tugas, kuis, ujian, dan kehadiran, saya memakai float(). Tujuannya supaya kalau nilainya ada koma, misalnya 82.5, program tetap bisa membaca nilainya.
Setelah itu, program menghitung nilai akhir. Nilai tugas dikali 30%, nilai kuis dikali 20%, dan nilai ujian dikali 50%. Hasil dari ketiganya dijumlahkan, lalu jadilah nilai akhir peserta.
Setelah nilai akhir didapat, program mengecek kehadiran dan nilainya pakai if, elif, dan else. Yang dicek dulu adalah kehadiran. Kalau kehadirannya kurang dari 75%, otomatis tidak lulus, walaupun nilainya bagus.
Kalau kehadirannya sudah cukup, baru program melihat nilai akhirnya. Kalau nilainya minimal 85 dan kehadiran minimal 80%, dapat Predikat A. Kalau nilainya minimal 75 dan kehadiran minimal 80%, dapat Predikat B. Kalau nilainya minimal 65 dan kehadiran minimal 75%, dapat Predikat C.
Selain dari kondisi itu, statusnya Tidak Lulus. Di akhir program, hasilnya ditampilkan, yaitu nama peserta, nilai akhir, kehadiran, dan status kelulusannya.
