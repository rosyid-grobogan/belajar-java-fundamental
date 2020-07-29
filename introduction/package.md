# Package

| Nama Domain | Nama Aplikasi    | Nama Modul |
| ----------- | ---------------- | ---------- |
| belajar.com | Java Fundamental | Basic      |

Contoh package

```
com.belajar.javafundamental.basic
```

- menggunakan huruf kecil.
- menghilangkan spasinya.

## Apa sih manfaatnya?

Misalnya ada class `StringUtils` dari library A dikemudian hari saya menambahkan Library B dan di dalamnya ada class `StringUtils`. Hal ini bisa menyebabkan error karena ada 2 nama class yang sama. 

Solusinya, kita bisa menggunaan package ini.

Cara Memanggil Package

1. Fully Qualified Name
2. Import

###  Fully Qualified Name

Memanggil nama *package* secara lengkap dari class Main

```
com.belajar.javafundamental.basic.Main;
```



### Import

*Import* digunakan untuk menyingkat pemanggilan *class* yang berbeda *package*.

Jadi kita tak perlu menuliskan secara `fully qualified name` .

> Khusus untuk *class* dari *package* `java.lang`, kita tidak perlu memanggil menggunakan *fully qualified name*. dan tidak perlu menggunakan `import` saat memanggilnya, misalnya class `java.lang.System` yang kita gunakan untuk *print* *“Hello world!”*. 
>
> ```java
> System.out.println("Hello world!");
> ```

Bagaimana kalau kita *import* beberapa *class* dari *package* yang sama? Kita bisa menggunakan *wildcard* (simbol *) untuk menggantikan nama *class*-nya. Artinya, Java akan otomatis mengenali seluruh class dari *package* tersebut. 



## Tips: IntelliJ

**alt + Enter** : import 