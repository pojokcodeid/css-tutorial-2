# CSS ANIMATION
apa itu anomasi CSS?
ASnimasi memungkinkan element secara bertahap berubah dari satu gaya ke gaya lainnya. Kita busa mengubah properti CSS sebanyak yang diinginkan

1. Aturan @keyframes
Saat mengunakan aturan @keyframes animasi akan berubah secara bertahap dari gaya satu ke gaya lainnya.
Contoh :
```
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
```
2. Animation delay
Properti animation-delaymenentukan penundaan untuk memulai animasi.
contoh :
```
div {
  width: 100px;
  height: 100px;
  background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 4s;
  animation-delay: 2s;
}

@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  50%  {background-color:blue; left:200px; top:200px;}
  75%  {background-color:green; left:0px; top:200px;}
  100% {background-color:red; left:0px; top:0px;}
}
```

3. animation-iteration-count
Properti animation-iteration-countmenentukan berapa kali animasi harus dijalankan.contoh :
```
div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
  animation-iteration-count: 3;
}
```

4. animation-timing-function
Properti animation-timing-functionmenentukan kurva kecepatan animasi.
contoh :

