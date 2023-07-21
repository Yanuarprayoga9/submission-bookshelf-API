Terdapat 7 kriteria utama yang harus Anda penuhi dalam membuat proyek Bookshelf API.

### Kriteria 1 : Aplikasi menggunakan port 9000 || compeleted
### Kriteria 2 : Aplikasi dijalankan dengan perintah npm run start. || completed
### Kriteria 3 : API dapat menyimpan buku
Method : POST
URL : /books
Body Request:

{
    "name": string,
    "year": number,
    "author": string,
    "summary": string,
    "publisher": string,
    "pageCount": number,
    "readPage": number,
    "reading": boolean
}
