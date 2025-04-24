### Menyisipkan Kutipan Blok Bertingkat

Markdown mendukung kutipan (blockquote), dan kamu bisa membuat kutipan bertingkat juga:

```markdown
> Ini adalah kutipan.
>> Ini adalah kutipan di dalam kutipan.
```
Hasil:
> Ini adalah kutipan.  
>> Ini adalah kutipan di dalam kutipan.

---

### Menyisipkan Referensi Link

Kamu bisa menuliskan link dengan gaya referensi, supaya lebih rapi:

```markdown
Ini adalah [tautan referensi][google].

[google]: https://www.google.com
```
Hasil:
Ini adalah [tautan referensi](https://www.google.com).

---

### Escaping Karakter Khusus

Kalau kamu ingin menampilkan karakter khusus seperti `*`, `_`, atau `#` tanpa memicu format Markdown, gunakan `\`:

```markdown
\*teks ini tidak ditebalkan\*
```
Hasil:
\*teks ini tidak ditebalkan\*

---

### Merapikan Tampilan Heading (Setext-style)

Markdown juga mendukung heading alternatif (khusus Heading 1 dan 2):

```markdown
Heading 1
=========

Heading 2
---------
```
Hasil:
Heading 1  
=========

Heading 2  
---------

---
