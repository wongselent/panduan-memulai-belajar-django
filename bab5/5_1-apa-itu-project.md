## 5.1 Apa itu Project?

Project dalam Django merupakan sebuah inti dari web aplikasi yang akan kita buat. Dan merupakan sebuah container bagi submodule serta konfigurasi. Project pada dasarnya bisa berjalan tanpa harus mempunyai App. Namun, pada skala besar biasanya akan memerlukan banyak App dalam sebuah project bila dibutuhkan. Jadi relasi antara Project dengan App bisa saling berelasi ataupun berjalan dengan sendirinya. Tergantung dari apa yang akan kita ciptakan.

### Struktur Direktori Django Project

```
djangotutorial/
|-- djangotutorial
|   |-- __init__.py
|   |-- settings.py
|   |-- urls.py
|   `-- wsgi.py
`-- manage.py
```

Itu adalah contoh struktur direktori Project yang sudah dijelaskan sebelumnya dalam sesi awal.