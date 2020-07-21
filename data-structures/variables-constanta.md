# Variables dan Constanta

---

## Variable

> Kita akan belajar varibale mulai dari:
>
> - [x] Teori, pengertian, penulisan, contoh, bentuk variable dan studi kasus.

Variable memiliki nama yang disebut dengan `identifier`.

> Istilah `identifier` akan sering kamu temui ketika membaca buku berbahasa inggris.



**Pengertian**

?> "Penampung nilai untuk sebuah tipe data"

**Penulisan Variable (Deklarasi Variable)**

```
tipe_data nama_variable;
```

```java
int umur;
char a;
```

**Contoh: Variasi**

```java
int umur;			// deklarasi variable umur yang bertipe int
int umur = 20;		// deklarasi dan inisialisasi
int angka, umur, ktp;	// deklarasi 3 variable sekaligus
int angka = 5, umur = 20, ktp = 12345; // deklasari dan inisialisasi
```

```java
int a, b, c; // declares three int: a, b, and c
int d = 3, e, f = 5; // declares three more int, initializing d and f
byte z = 22; // initializes z
double pi = 3.14159 // declares an aproximation of pi
char x = 'x'; // the variable x has the value 'x'
```

## Mengenal 3 Bentuk Variable

Ada 3 bentuk variable:

1. variable `local`.
2. variable `instan` (instansiasi).
3. variable `static`.



### 1. Variable Local

**Pengertian**

?> "variable yang dituliskan di dalam method atau block".

> block diawali tanda { dan diakhiri }
>
> {
>
> // area dalam block
>
> }

**Siklus Hidup:** variable local akan dihapus dari memori ketika method / block selesai dijalankan.

**Scope (Ruang Lingkup):** hanya berada di dalam `method` atau `block`.



### 2. Variable Instance (Instansiasi)

**Pengertian**

?> "Variable yang dituliskan di dalam class atau secara global yang diluar method atau block".

**Scope (Ruang Lingkup):** bisa dipanggil secara global tergantung `access modifier`.



### 3. Variable Static

**Pengertian**

?> "Variable yang ditulis dengan keyword (kata kunci) `static`".



### Perbedaan Variable Instance dan Variable Static: Ketika di panggil

| No  | Variables         | Description                                    |
| --- | ----------------- | ---------------------------------------------- |
|     | Variable Instance | Harus di instansiasi dulu dengan keyword `new` |
|     | Variable Static   | Langsung bisa dipanggil                        |

**Ilustrasi**:

```
Kode itu harus dipanggil dulu, kemudian baru bisa diberikan tugas.
Ibarat: Bos dan Karyawan.
Seorang Bos harus memanggil salah satu karyawannya terlebih dahulu, baru bisa memberikan dia tugas kerjaa.
```

**Cara Panggil Variable Static**

```
nama_class.nama_varible_static = nilai_data;
```

```java
User.namaLengkap = "Rosyid Grobogan";
```

> Saya berharap penjelasan ini mudah dipahami oleh teman-teman yang belajar Java.
