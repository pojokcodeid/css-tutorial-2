# PSEUDO CLASS

Pseudo Class digunakan untuk menentukan keadaan khusus suatu element
contohnya :

- Memberi Style pada element saat pengguna mengarahkan mouse keatasnya.
- Style tautan sudah di klik atau belum di klik
- Memberi Style pada element saat mendapat fokus

Contoh :

```
/* unvisited link */
a:link {
  color: #FF0000;
}

/* visited link */
a:visited {
  color: #00FF00;
}

/* mouse over link */
a:hover {
  color: #FF00FF;
}

/* selected link */
a:active {
  color: #0000FF;
}
```

Apa perbedaan Pseudo Class dan Pseudo Element ?
Pseudo class digunakan untuk memberikan style pada kondisi tertentu (kelas semu) sedangkan Pseudo Element memberikan style pada kondisi tetap dan sering digunakan untuk membuat objek baru pada element HTML supaya memberikan tampilan yang lebih abstrak.

## Penggabungan Pseudo Class dengan Clas HTML

cotoh:

```
a.highlight:hover {
  color: #ff0000;
}
```

## Pseudo Class Untuk Style Element Lainnya

contoh :

```
p {
  display: none;
  background-color: yellow;
  padding: 20px;
}

div:hover p {
  display: block;
}
```

## Pseudo Class Untuk Anak

contoh :

```
p:first-child {
  color: blue;
}
```

## :lang Psudo Class

Contoh :

```
q:lang(no) {
  quotes: "~" "~";
}
```
