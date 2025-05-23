### Tips Menulis Markdown yang Rapi dan Konsisten

Agar konten Markdown mudah dibaca dan dipelihara, perhatikan beberapa tips berikut:

* Gunakan indentasi dan struktur heading yang konsisten (`#`, `##`, `###`, dst).
* Pisahkan blok kode dan teks biasa dengan garis kosong.
* Hindari baris terlalu panjang dalam satu paragraf (maksimal 80–120 karakter) agar mudah dibaca di editor.
* Gunakan *list* (bullet atau number) untuk poin-poin penting, jangan menjejalkan semua dalam paragraf.
* Manfaatkan fitur **preview** sebelum commit, agar tahu tampilan akhirnya.

Contoh struktur heading yang baik:

```markdown
# Judul Utama

## Subjudul

### Detail
```

---


### Menambahkan Gambar di Markdown

Markdown mendukung penyisipan gambar dengan sintaks berikut:

```markdown
![Deskripsi gambar](URL_gambar)
```

Contoh:

```markdown
![Logo Markdown](https://markdown-here.com/img/icon256.png)
```

Jika gambar ada di repositori:

```markdown
![Diagram](./images/diagram.png)
```

---

### Link Internal dan Eksternal

Gunakan link Markdown untuk navigasi ke:

* **Halaman eksternal**:

  ```markdown
  [Kunjungi GitHub](https://github.com)
  ```

* **File atau bagian dalam dokumen**:

  ```markdown
  [Lihat Bagian Fitur](#fitur)
  ```

Pastikan teks yang dituju di heading tidak diubah, karena tautan internal bergantung pada itu.

---

### Menulis Tabel di Markdown

Markdown mendukung pembuatan tabel sederhana:

```markdown
| Bahasa     | Digunakan Untuk        |
|------------|------------------------|
| Python     | Data science, backend  |
| JavaScript | Web development        |
| Kotlin     | Android development    |
```

Hasil:

| Bahasa     | Digunakan Untuk       |
| ---------- | --------------------- |
| Python     | Data science, backend |
| JavaScript | Web development       |
| Kotlin     | Android development   |

---
