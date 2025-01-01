## Apa itu Pseudo-Element?

- Pseudo-Element digunakan untuk memberi style pada bagian tertentu dari suatu element.
- misalnya :
  Style untuk huruf pertama, barus dari element
  menyisipkan konten sebelum atau sesudah element
  dsb..

## Sintaks

```
selector::pseudo-element {
  property: value;
}
```

### 1. ::first-line Pseudo-Element

- ini digunakan untuk menambahkan gaya khusus pada baris pertama text
  contoh : (class pada latihan = contoh1)

```
p::first-line {
  color: #ff0000;
  font-variant: small-caps;
}
```

catatan : ::first-line hanya bisa di terapkan untuk element tingkat block
apa saja elementnya bisa cek dari link berikut<br>
https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements <br>
properti yang dapat digunakan :

- font properties
- color properties
- background properties
- word-spacing
- letter-spacing
- text-decoration
- vertical-align
- text-transform
- line-height
- clear

multi pseudo-element juga dapat dilakukan

### 2. ::first-letter Pseudo-Element

ini digunakan khusus untuk styling huruf pertama pada text
contoh :

```
p::first-letter {
  color: #ff0000;
  font-size: xx-large;
}
```

### 3. ::before Pseudo-elements

digunakan untuk menyisipkan beberapa konten sebelum komponent
cotoh :

```
h1::before {
  content: url(smiley.gif);
}
```

### 4. ::after Pseudo-Elemenkomponent

digunakan untuk menyisipkan beberapa konten setelah kontent
contoh :

```
h1::after {
  content: url(smiley.gif);
}
```

### 5. ::marker Pseudo-Element

digunakan untuk memilih penanda item
contoh :

```
::marker {
  color: red;
  font-size: 23px;
}
```

### 6. ::selection Pseudo-Element

ini cocok untuk porsi element yang dipilih oleh pengguna
contoh :

```
::selection {
  color: red;
  background: yellow;
}
```

Referensi kunjungi :

- https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements
