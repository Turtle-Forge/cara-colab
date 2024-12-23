# cara-colab
Ketua:
- buat project Laravel
- push ke GitHub
- masuk ke pengaturan, invite collaborators (tambah anggota
- buat protected branch main di pengaturan
- create project pake fitur di github (pake board/kanban)
- invite collaborators (di bagian pengaturan project)
- buat tugas/todo/list tugas yg akan dikerjakan 
- convert setiap tugas/list kerjaan ke issue
- assign anggota yg akan mengerjakan todo tersebut

Running project Laravel GitHub (anggota):
- git clone <url GitHub repo>
- cd <nama repo>
- composer install
- cp .env.example .env
- php artisan key:generate
- php artisan serve (berhasil ? lanjut : rollback)
- {lanjut: ngoding}
- pindahkan card tugas ke bagian kolom do
- buat branch baru: git branch <nama branch> (misal: git branch about-page)
- git checkout about-page (masuk ke branch tsbt)
- sudah boleh ngoding (buat ngerjain tugas yg diassign di project)
- coba jalanin lagi, kalo berhasil lakukan push
- git add .
- git commit -m "membuat halaman about"
- git push -u origin about-page
- pindah ke repo github dan lakukan pull request


Ketua:
- melakukan review kode yang sudah dipush
- approve jika sudah benar

Notes:
- setiap kali mau ngerjain fitur baru diwajibkan buat branch baru
