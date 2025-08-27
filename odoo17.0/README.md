# Odoo 17 Docker Setup

Repository ini berisi konfigurasi Docker untuk menjalankan **Odoo 17** beserta **custom addons**.

## Struktur Folder
- `custom-addons/` : Modul Odoo tambahan/buatan sendiri
- `config/` : File konfigurasi Odoo
- `docker-compose.yml` : File Docker Compose untuk Odoo dan PostgreSQL
- `odoo_pg_pass` : File berisi password database (tidak di-push)
- `.gitignore` : File untuk mengabaikan file sensitif dan temporary

## Persiapan File Password
Sebelum menjalankan Docker, **buat file `odoo_pg_pass` di root repo** dengan isi password PostgreSQL yang akan digunakan Odoo.  
Contoh:
