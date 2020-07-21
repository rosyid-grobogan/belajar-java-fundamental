# Tipe Data: Array

---

## Why ?

Ketika kita ingin menyimpan 5 buah nilai dari nama user

Jika kita membuatnya tanpa array, maka kita harus menyiapkan 5 buah variabel

**Tanpa Array**

```java
String nama1, nama2, nama3, nama4, nama5
```

**Menggunakan Array**

```java
String[] nama = new String[5]
```

Lalu bagaimana jika kita memiliki 10.000 data nama user dan ingin menampilkannya?

## Pengertian

?> "Array adalah object bawaan java yang dapat menyimpan kumpulan data dengan tipe data yang sama."

Misalnya:

Angka bulat saja (_integer_), kumpulan karakter saja (_char_), maupun kumpulan angka pecahan saja (_double_). Di dalam bahasa Java, kita tidak bisa membuat 1 array dengan berbeda tipe data (harus 1 jenis saja).

- bisa menyimpan tipe data primitif, wrapper class maupun reference
- Tempat hidup: HEAP

## Cara Membuat Array

> 3 hal yang harus kita lakukan:
>
> 1. Mendeklarasikan variable array
> 2. Menginisialisasi object array
> 3. Mengisi array dengan data

## Langkah Pertama: Mendeklarasikan Array

Java menyediakan 2 Cara untuk mendeklarasikan array

1. Cara yang disarankan
2. Cara yang diadopsi dari bahasa C/C++

| Deklarasi 1     | Deklarasi 2                |
| --------------- | -------------------------- |
| Preferred way   | Work but not preferred way |
| `String[] nama` | `String nama[]`            |

## Deklarasi Array Multi dimensi

```java
String[][]		// array 2 dimensi
String[][][]    // array 3 dimensi
```



> Saya berharap penjelasan ini mudah dipahami oleh teman-teman yang belajar Java.