### Menggunakan Markdown di GitHub

GitHub mendukung **GitHub Flavored Markdown (GFM)** yang punya beberapa fitur tambahan selain standar Markdown, seperti:

- **Task List** ✅
- **Syntax Highlighting** untuk berbagai bahasa pemrograman
- **Mention** user dan issue:
  ```markdown
  @username mengomentari issue #123
  ```

- **Referensi file atau folder**:
  ```markdown
  Lihat file [`README.md`](./README.md)
  ```

- **Menambahkan badge** dari Shields.io:
  ```markdown
  ![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
  ```

---

### Syntax Highlighting di Code Block

Markdown mendukung *syntax highlighting* untuk banyak bahasa. Cukup tambahkan nama bahasanya setelah tiga backtick:

```markdown
```python
def hello():
    print("Hello, Markdown!")
```
```

Hasil:
```python
def hello():
    print("Hello, Markdown!")
```

Beberapa contoh bahasa yang bisa digunakan:
- `python`
- `javascript`
- `bash`
- `html`
- `css`
- `java`
- `kotlin` dan lainnya

---
