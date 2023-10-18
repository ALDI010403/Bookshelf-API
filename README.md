# Bookshelf API

Repository ini untuk menyelesaikan Submission Bookshelf API dari dicoding di kelas Belajar Membuat Aplikasi Back End untuk pemula
Terdapat 7 kriteria utama yang harus Anda penuhi dalam membuat proyek Bookshelf API.

# kriteria penilaian yang harus terpenuhi
- [x] Kriteria 1 : Aplikasi menggunakan port 9000
Aplikasi yang Anda buat harus menggunakan port 9000. Jika komputer yang Anda gunakan untuk membuat submission tidak bisa memakai port 9000,  buatlah submission dengan port lain, lalu ketika submission hendak dikirimkan silakan ganti portnya ke 9000.

- [x] Kriteria 2 : Aplikasi dijalankan dengan perintah npm run start.
Aplikasi yang Anda buat harus memiliki runner script start. Cara membuatnya, Anda tambahkan properti start ke dalam properti scripts pada package.json seperti berikut:
```
{
  "name": "submission",
  ...
  "scripts": {
    "start": "node src/server.js",
  }
}
```

- [x] Kriteria 3 : API dapat menyimpan buku
API yang Anda buat harus dapat menyimpan buku melalui route:

Method : POST
URL : /books

- [x] Kriteria 4 : API dapat menampilkan seluruh buku
API yang Anda buat harus dapat menampilkan seluruh buku yang disimpan melalui route:

Method : GET
URL: /books

- [x] Kriteria 5 : API dapat menampilkan detail buku
API yang Anda buat harus dapat menampilkan seluruh buku yang disimpan melalui route:

Method : GET
URL: /books/{bookId}

- [x] Kriteria 6 : API dapat mengubah data buku
API yang Anda buat harus dapat mengubah data buku berdasarkan id melalui route:

Method : PUT
URL : /books/{bookId}

- [x] Kriteria 7 : API dapat menghapus buku
API yang Anda buat harus dapat menghapus buku berdasarkan id melalui route berikut:

Method : DELETE
URL: /books/{bookId}

# hasil tes API
ini adalah screenshot tes API untuk aplikasi Bookshel API yang sudah di tentukan dicoding
![Screenshot (218)](https://github.com/ALDI010403/Bookshelf-API/assets/102725152/0b5179bf-b085-48a4-8454-f9f6038e5d25)

## Author
Aldi
