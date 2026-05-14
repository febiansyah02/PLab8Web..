# Praktikum 8: Implementasi AJAX pada CodeIgniter 4

Repositori ini berisi hasil Praktikum 8 mengenai implementasi teknik **AJAX (Asynchronous JavaScript and XML)** menggunakan pustaka **jQuery** pada framework **CodeIgniter 4**.

## Deskripsi Tugas
Pada praktikum ini, dilakukan pembuatan fitur pemuatan data dan penghapusan data artikel secara dinamis tanpa perlu memuat ulang (*reload*) halaman web. Hal ini dicapai dengan berkomunikasi melalui endpoint API yang mengembalikan data dalam format **JSON**.

## Fitur Utama
* **Load Data Otomatis**: Mengambil data artikel dari database saat halaman dibuka menggunakan fungsi `$.ajax()` atau `$.get()`.
* **Hapus Data (No-Reload)**: Menghapus data artikel secara langsung dari tabel dan memperbarui tampilan secara otomatis setelah proses hapus sukses.
* **Format JSON**: Pertukaran data antara server (PHP) dan client (JavaScript) dilakukan sepenuhnya menggunakan format JSON.

## Struktur Folder Terkait
Berikut adalah file-file penting yang dikonfigurasi dalam praktikum ini:
* `app/Controllers/AjaxController.php` - Menangani request dan mengembalikan respon JSON.
* `app/Views/ajax/index.php` - Halaman tampilan utama yang berisi script jQuery.
* `app/Config/Routes.php` - Konfigurasi rute untuk akses endpoint AJAX.
* `public/assets/js/jquery-4.0.0.min.js` - Library jQuery yang digunakan.

## Cara Penggunaan
1.  Pastikan server local (Apache & MySQL) sudah aktif melalui XAMPP.
2.  Jalankan perintah `php spark serve` pada terminal.
3.  Akses alamat: `http://localhost:8080/ajax`.
4.  Data artikel akan dimuat secara otomatis ke dalam tabel.
5.  Gunakan tombol **Hapus** untuk menguji fitur penghapusan data secara *asynchronous*.

## Teknologi yang Digunakan
* [CodeIgniter 4](https://codeigniter.com/) - Framework PHP.
* [jQuery](https://jquery.com/) - Pustaka JavaScript untuk memudahkan manipulasi DOM dan AJAX.
* [JSON](https://www.json.org/) - Format pertukaran data.

## Hasil Pratikum
<img width="1919" height="1079" alt="Cuplikan layar 2026-05-14 075036" src="https://github.com/user-attachments/assets/be56701e-539b-4f07-ab00-a0d0fa31ec28" />
<img width="1919" height="1079" alt="Cuplikan layar 2026-05-14 075048" src="https://github.com/user-attachments/assets/b654b410-da58-49f1-928f-d86b2a419690" />
<img width="1918" height="1079" alt="Cuplikan layar 2026-05-14 075100" src="https://github.com/user-attachments/assets/ac22ff73-e509-4f9a-b38e-c7f7a8b45b5a" />


---
**Dibuat oleh:** M FEBIANSYAH MULYADI  
**NIM:** 312410593

**Universitas Pelita Bangsa**
