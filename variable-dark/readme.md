 # CSS VARIABLE
fungsi var() digunakan untuk memasukan nilai variable 
variable CSS memiliki acess ke DOM,yang berarti kita dapat membuat variable dengan cakupan local ataupun global, merubah variable dengan javascript dan merubah variable berdasarkan media query.
contoh yang paling sering digunakan adalah ketika mendefinisakan warna

Contoh Cara Tradisional :
```
body { background-color: #1e90ff; }

h2 { border-bottom: 2px solid #1e90ff; }

.container {
  color: #1e90ff;
  background-color: #ffffff;
  padding: 15px;
}

button {
  background-color: #ffffff;
  color: #1e90ff;
  border: 1px solid #1e90ff;
  padding: 5px;
}
```

Cara Penulisan :
```
var(--name, value)
```
```
--name  = ini adalah nama variablenya
value   = isi dari variable
```
## Contoh CSS Dengan Cakupan global
cakupan global di definisikan dengan :root
contoh :
```
:root {
  --blue: #1e90ff;
  --white: #ffffff;
}

body { background-color: var(--blue); }

h2 { border-bottom: 2px solid var(--blue); }

.container {
  color: var(--blue);
  background-color: var(--white);
  padding: 15px;
}

button {
  background-color: var(--white);
  color: var(--blue);
  border: 1px solid var(--blue);
  padding: 5px;
}
```

