# Gandiva-Protocol
The Gandiva Protocol - set berbagai template dan struktur yang memungkinkan mahasiswa menyelesaikan tugas akhir dengan baik, aman, dan cepat dan juga memudahkan dosen pembimbing untuk melakukan proses pengarahan, monitoring, dan evaluasi dengan memanfaatkan teknologi version control system dan cloud storage.

## Mengapa menggunakan Gandiva Protocol?
Bagian terakhir dalam perjalanan sebagai mahasiswa adalah menyelesaikan pembuktian diri sebagai seorang sarjana: membuat tugas akhir / skripsi. Skripsi adalah milestone yang mengukuhkan bahwa seorang mahasiswa telah mampu membuat suatu karya ilmiah yang memberikan sumbangsih kepada literasi ilmu pengetahuan.

Di Program Studi Teknologi Informasi, dalam melakukan proses penyelesaian tugas akhir, semua prosesnya harus dilakukan dengan efisien, aman dan termonitor dengan baik. **Gandiva Protocol** memberikan template dan struktur bagi mahasiswa, sehingga pekerjaan tugas akhir mereka menjadi terstruktur dan terorganisir dengan baik. Mulai dari template penulisan proposal, naskah laporan, hingga naskah publikasi artikel.

Selain template penulisan beserta sub folder kelengkapan untuk menyimpan file desain, gambar, foto, dan literature terkait, juga disediakan template untuk menyimpan file teknis seperti kode program, desain perangkat keras, dan data hasil observasi penelitian. Dengan demikian, tidak ada lagi masalah klasik dan konyol seperti projek musnah terkena ransomware, laptop rusak, file hilang, file2-revisi1, file1-revisi2, dan segala kerumitasn proses revisi, dan yang paling penting, seluruh kegiatan dapat dimonitor dan dievaluasi dengan mudah dan cepat oleh dosen pembimbing tanpa harus menunggu berjam-jam dan menghabiskan berliter-liter bensin hanya untuk menyerahkan selembar kertas kepada dosen pembimbing.

## Struktur Umum Gandiva Protocol

Secara umum, struktur Gandiva Protocol adalah sebagai berikut:

1.   NASKAH
     - Images
          - Gambar 1.jpg
          - Logo 1.jpg
          - Desain Software.jpg
          - Desain Hardware.jpg
     - Datasheet
          - Datasheet 1.xlsx
          - Datasheet 2.pdf
     - Literatures
          - literature1.pdf
          - literature2.pdf
     - Dokumen Proposal Skripsi - \[NIM\] - \[NAMA\] - \[TAHUN ANGKATAN\] - \[TAHUN SKRIPSI\].docx
     - Presentasi Proposal Skripsi  - \[NIM\] - \[NAMA\] - \[TAHUN ANGKATAN\] - \[TAHUN SKRIPSI\].pptx
     - Dokumen Laporan Skripsi - \[NIM\] - \[NAMA\] - \[TAHUN ANGKATAN\] - \[TAHUN SKRIPSI\].docx
     - Presentasi Laporan Skripsi  - \[NIM\] - \[NAMA\] - \[TAHUN ANGKATAN\] - \[TAHUN SKRIPSI\].pptx
     - Dokumen Artikel Skripsi - \[NIM\] - \[NAMA\] - \[TAHUN ANGKATAN\] - \[TAHUN SKRIPSI\].docx
2.   PROJECT
     - software
          - firmware
          - backend
          - frontend
     - hardware
          - schematic
          - design
          - rendered
     - docs
          - sensordatasheet.pdf
          - pinout.pdf

Terdapat dua folder utama, NASKAH dan PROJECT. Pada folder **naskah** berisi semua file yang terkait dengan proses penyusunan proposal, laporan, dan artikel skripsi. Proposal diperlukan untuk melakukan ujian proposal skripsi, laporan diperlukan untuk ujian utama skripsi, dan artikel diperlukan untuk melakukan publikasi laporan skripsi di jurnal TIERS atau jurnal lain yang bereputasi. Nama file yang berisi \[NIM\], \[NAMA\], \[TAHUN ANGKATAN\], dan \[TAHUN SKRIPSI\] diganti menjadi punya mahasiswa terkait. Contoh: **Dokumen Proposal Skripsi - 110010129 - I WAYAN ADITYA SURANATA - 2011 - 2015.docx** lalu simpan setiap dokumen dalam format PDF untuk memudahkan tim dosen melakukan revisi via PDF Comment. Ini juga untuk menghindari kerusakan format karena membuka file DOCX dengan versi Word Prosesor yang berbeda. Jika file naskah diperiksa dalam bentuk PDF, maka dosen bisa dengan mudah memberi komentar tanpa harus khawatir merusak format.

Pada folder **project**, berisi berbagai file dan kode program terkait dengan projek skripsi yang dibuat. Struktur pada folder projek tidak terlalu strik, mahasiswa bisa merubah dan menggunakan strukturnya sendiri yang disesuaikan dengan jenis projek yang dibuat. Dengan catatan, disetiap folder disediakan file **README.md** yang berisi detail dan tujuan dari setiap folder yang dibuat.

> Ingat untuk menggunakan fitur .gitignore untuk menyembunyikan file yang bersifat rahasia.

## Alur Pengerjaan Skripsi dengan Gandiva Protocol
Secara umum, alur penggunaan Gandiva Protokol mirip dengan saat kita melakukan Fork Repository. Garis besarnya adalah sebagai berikut:

- [X] Buat akun GitHub
- [X] Buat repository SKRIPSI, dan inisialisasi. **SET PRIVATE AGAR TIDAK DILIHAT OLEH PUBLIC!**
- [X] Clone Gandiva Protocol ke akun pribadi, copy isinya ke repository SKRIPSI yang dibuat tadi.
- [X] Mulai bekerja di repository SKRIPSI, commit, push.
- [X] Tambahkan dosen pembimbing sebagai kolaborator ke repo SKRIPSI.
- [X] Mulai proses bekerja di folder Gandiva Protocol dengan memilih branch sesuai jenis pekerjaan. Gunakan ISSUE yang diberikan oleh dosen pembimbing sebagai acuan membuat branch, dan **hindari bekerja di branch main**. Selalu buat branch baru sesuai jenis ISSUE atau jenis pekerjaan.
- [X] Dosen pembimbing akan mengevaluasi ISSUE yang telah diberikan ke mahasiswa, dicek apakah mahasiswa sudah menyelesaikan ISSUE tersebut atau belum.
- [X] Proses berlanjut diseputaran ISSUE, ISSUE disini bisa berbentuk instruksi dari dosen pembimbing untuk melakukan revisi, atau dari pribadi mahasiswa sendiri untuk tujuan penambahan fitur, percobaan, dan sebagainya.
- [X] Lakukan proses merge ke branch utama di repo lokal pribadi setelah selesai dengan ISSUE atau branch khusus untuk memastikan branch main selalu menjadi branch yang paling up-to-date.

Untuk memberikan gambaran yang lebih jelas tentang alur penggunaan Gandiva Protocol, akan disediakan video podcast sebagai bahan referensi.
