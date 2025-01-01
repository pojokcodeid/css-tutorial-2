# CSS FUNCTION
CSS Function digunakan sebagai nilai untuk berbagai properti CSS.

## CSS attr() Function

digunakan untuk memberikan nilai dari atribute yang dipilih
contoh :

```
a:after {
  content: " (" attr(href) ")";
}
```

## CSS calc() Function

digunakan untuk melakukan perhitungan untuk digunakan sebagai nilai property
contoh :

```
#div1 {
  position: absolute;
  left: 50px;
  width: calc(100% - 100px);
  border: 1px solid black;
  background-color: yellow;
  padding: 5px;
  text-align: center;
}
```

## CSS conic-gradient() Fungsi

digunakan untuk menyetel gradient berbentuk kerucut sebagai gambar latar belakang
contoh :

```
#grad {
  background-image: conic-gradient(red, yellow, green);
}
```

## CSS Counter() Function

mengembalikan nilai saat ini
contoh :

```
h2::before {
  counter-increment: section;
  content: "Section " counter(section, upper-roman) ": ";
}
```

## CSS cubic-bezier() Function

digunakan untuk medefinisikan kurva cubik cubic-bezier
contoh :

```
div {
  width: 100px;
  height: 100px;
  background: red;
  transition: width 2s;
  transition-timing-function: cubic-bezier(0.1, 0.7, 1.0, 0.1);
}
```
