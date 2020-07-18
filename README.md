# Belajar java

---



## Mengenal Deklarasi, Inisialisasi dan Instansiasi

### Deklarasi

**Deklarasi** adalah istilah untuk menyebut proses pembuatan variabel, dimana kita meminta compiler Java agar menyiapkan tempat di memory komputer untuk sebuah variabel. 

Misalnya: 

```java
String[] nama ;
```



### Inisialisasi

**Inisialisasi** sendiri adalah proses pemberian nilai awal ke variabel tersebut.

Yang dicirikan dengan tanda sama dengan “ = “.

Misalnya

```java
int angka = 5 ;
```



### Instansiasi

Secara sederhana perintah instansiasi ditandai dengan keyword **new**.

Misalnya:

```java
int[] umur ;          // deklarasi
umur = new int[10] ;  // inisialisai sekaligus instansiasi dengan panjang array 10 karakter
```





# Data Structure

## Variable

Pengertian

```
"Penampung nilai dari sebuah tipe data"
```



Cara Penulisan

```
type identifier [ = value ][, identifier [= value ] …];
```

Contoh

```java
int a, b, c; // declares three int: a, b, and c
int d = 3, e, f = 5; // declares three more int, initializing d and f
byte z = 22; // initializes z
double pi = 3.14159 // declares an aproximation of pi
char x = 'x'; // the variable x has the value 'x'
```



## Tipe Data

Jika dikelompokkan berdasarkan object dan non-object, maka ada 2 macam:

- Non Object : Primitif
- Berbasis Object: Wrapper Class, Array

### Tipe Data: Primitif

Ada 8 Tipe Data Primitive (Simple types)

1. byte
2. short
3. int
4. long
5. float
6. double
7. boolean

Kemudian dari 8 tipe data itu bisa kita kelompokkan menjadi 4 kelompok

| Integers | Floating-point numers | Characters | Boolean |
| -------- | --------------------- | ---------- | ------- |
| byte     | float                 | char       | boolean |
| short    | double                |            |         |
| int      |                       |            |         |
| long     |                       |            |         |



### Tipe Data: Wrappers Class

Pengertian

```
"Tipe data bawaan java yang berupa object"
```

- Setiap data primitif mempunyai padanan di wrapper class
- Wrapper berupa Class
- Bersifat Immutable

> Immutable: Variable yang memegang objectnya bukan variable reference



### Tipe Data: Array

**Why ?**

Ketika kita ingin menyimpan 5 buah nilai dari nama user

Jika kita membuatnya tanpa array, maka kita harus menyiapkan 5 buah variabel

Tanpa Array

```java
String nama1, nama2, nama3, nama4, nama5
```

Menggunakan Array

```java
String[] nama = new String[5]
```

Lalu bagaimana jika kita memiliki 10.000 data nama user dan ingin menampilkannya?



**Pengertian**

> **“Array adalah object bawaan java yang dapat menyimpan kumpulan data dengan tipe data yang sama.”**

Misalnya: 

Angka bulat saja (*integer*), kumpulan karakter saja (*char*), maupun kumpulan angka pecahan saja (*double*). Di dalam bahasa Java, kita tidak bisa membuat 1 array dengan berbeda tipe data (harus 1 jenis saja).

- bisa menyimpan tipe data primitif, wrapper class maupun reference
- Tempat hidup: HEAP

Cara Membuat Array

> 3 hal yang harus kita lakukan:
>
> 1. Mendeklarasikan variable array
> 2. Menginisialisasi object array
> 3. Mengisi array dengan data



Langkah Pertama: Mendeklarasikan Array

Java menyediakan 2 Cara untuk mendeklarasikan array

1. Cara yang disarankan
2. Cara yang diadopsi dari bahasa C/C++

| Deklarasi 1     | Deklarasi 2                |
| --------------- | -------------------------- |
| Preferred way   | Work but not preferred way |
| `String[] nama` | `String nama[]`            |

Deklarasi Array Multi dimensi

```java
String[][]		// array 2 dimensi
String[][][]    // array 3 dimensi
```



