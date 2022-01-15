# love-animation
ini adalah projek diri gw yang menggunakan animasi di html dan css untuk membuat animasi hati, dan juga code untuk kalian explor dengan animasi gw

using:
<br>HTML, CSS</br>

## Mengedit / Coding love

### 1. Penggunaan icon
utnuk iconnya gw pake boxicons, lu tinggal klik <b>boxicons.com<b> untuk cari icon2 yang lu suka


### 2. Tambahkan created by
untuk mengganti created by, lu bisa mengubah setingan di bagian coding html

```html
        <i class='bx-fw bx bxs-lemon'></i>Oxzproz
        animation
```

### 3. settingan style 
untuk setingan stylenya lu ganti di bagian warna merah aja
```html
body {
    background: #3e0000;
    margin: 0;
    padding: 0;
}
```
```html
  .heart {
    width: 180px;
    height: 100px;
    position: absolute;
    top: 50%;
    left: 35%;
    background: #ff3e3e;
    transform-origin: right bottom;
    transition: 1s;
}
 ```
 ```html
  .heart:hover::before {
    transform: rotate(450deg) translateY(100px);
    border-top-left-radius: 50px;
    border-bottom-left-radius: 50px;
    background: #e22c2c;
}
 ```
