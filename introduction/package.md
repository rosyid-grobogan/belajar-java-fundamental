# Package

| Nama Domain | Nama Aplikasi    | Nama Modul |
| ----------- | ---------------- | ---------- |
| belajar.com | Java Fundamental | Basic      |

Contoh package

```
com.belajar.javafundamental.basic
```

Penulisan Package

- Untuk `Nama Domain` penulisannya harus dibalik
  misal: `belajar.com` menjadi `com.belajar`
- Menggunakan `huruf kecil` semuanya.
- Menghilangkan `spasi`nya.

## Apa sih manfaatnya?

Misalnya ada class `StringUtils` dari library A dikemudian hari saya menambahkan Library B dan di dalamnya ada class `StringUtils`. Hal ini bisa menyebabkan error karena ada 2 nama class yang sama.

Solusinya, kita bisa menggunaan package ini.

Cara Memanggil Package

1. Fully Qualified Name
2. Import

### Fully Qualified Name

Memanggil nama _package_ secara lengkap dari class Main

```
com.belajar.javafundamental.basic.Main;
```

### Import

_Import_ digunakan untuk menyingkat pemanggilan _class_ yang berbeda _package_.

Jadi kita tak perlu menuliskan secara `fully qualified name` .

> Khusus untuk _class_ dari _package_ `java.lang`, kita tidak perlu memanggil menggunakan _fully qualified name_. dan tidak perlu menggunakan `import` saat memanggilnya, misalnya class `java.lang.System` yang kita gunakan untuk _print_ _“Hello world!”_.
>
> ```java
> System.out.println("Hello world!");
> ```

Bagaimana kalau kita _import_ beberapa _class_ dari _package_ yang sama? Kita bisa menggunakan _wildcard_ (simbol *) untuk menggantikan nama *class*-nya. Artinya, Java akan otomatis mengenali seluruh class dari *package\* tersebut.

## Tips: IntelliJ

**alt + Enter** : import
