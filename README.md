# StudyGroup-MP-Motionlab
## 1-Version Control (Git)
Version Control adalah sistem yang mengelola perubahan terhadap code dan dokumen yang dibuat.

### Version Control Tools
1) **Git**
Git adalah aplikasi version control populer di dunia perangkat lunak (software). Git memungkinkan developer untuk mencatat dan mengelola perubahan kode, baik secara individu maupun kolaboratif.
2) **GitHub**
GitHub adalah platform berbasis website yang menggunakan *Git Base*.
3) **Platform Lain**
GitHub bukan satu-satunya platform kolaborasi yang mendukung Git. Ada juga GitLab dan Bitbucket, yang memiliki fitur-fitur unik masing-masing, seperti CI/CD di GitLab dan integrasi dengan Atlassian di Bitbucket.

### Fitur dan Alur Kerja 
1) **Fitur**
    - **Commit**: Menyimpan perubahan kode dari waktu tertentu.
    - **Branching**: Membuat *branch* dari kode untuk mengembangkan fitur baru tanpa mengganggu kode utama.
    - **Merging**: Menggabungkan perubahan dari branch berbeda ke branch utama.
    - **Revert**: Mengembalikan perubahan yang dibuat.
    - **Stash**: Menyimpan perubahan sementara tanpa melakukan commit.
2) **Alur Kerja**
    - **Centralized Workflow**: Semua developer berkerja di *branch* yang sama (*main branch*).
    - **Feature Branch Workflow**: Setiap fitur aplikasi memiliki *branch* sendiri untuk meminimalisir terjadinya konflik.
    - **Gitflow**: Alur kerja yang terstruktur dengan *branch* khusus untuk pengembangan, pengujian, dan produksi.

### Perintah Dasar Git 
Inisialisasi repository baru.
```
 git init
```
Memeriksa perubahan yang terjadi.
```
 git status
```
Menambahkan perubahan ke staging area.
```
 git add
```
Menyimpan perubahan sebagai satu versi.
```
 git commit
```
Mengunggah perubahan ke repositori jarak jauh
```
 git push
```
Mengambil perubahan dari repositori jarak jauh
```
 git pull
```
Mengembalikan commit tertentu (undo)
```
 git reset
```

### Situasi 
1) **Branching and Merging**
Branching adalah fitur yang memungkinkan developer untuk membuat cabang terpisah untuk mengerjakan fitur baru atau memperbaiki kode tanpa mengganggu kode utama. Setelah perubahan siap, merging akan dilakukan dengan menyatukan perubahan ke dalam branch utama.
2) **Resolusi Konflik**
Konflik terjadi ketika dua pengguna atau lebih melakukan perubahan pada bagian kode yang sama. Untuk menyelesaikan konflik ini, git meminta pengguna untuk menyelesaikan konflik secara manual dengan memilih perubahan yang sesuai atau menggabungkannya (merge).
3) **Berkolaborasi di Git**\
Konsep penting kolaborasi di Git:
    - Fork: Menyalin repositori pengguna lain untuk pengembangan lebih lanjut.
    - Pull Request: Permintaan untuk menggabungkan perubahan dari repositori kita ke repositori asalnya.
    - Code Review: Proses memeriksa kdoe agar sesuai dengan standar yang telah ditentukan.