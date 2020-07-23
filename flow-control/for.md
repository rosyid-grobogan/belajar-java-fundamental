## Perulangan for

**Penulisan**

```java
for (mulai; kondisi; tipe_perulangan) {
    // blok kode yang akan diulangi
}
```

Misal: perulangan 1 - 5

```java
for(int number = 1; number <= 5; number++ ){
    System.out.println("Number :"+ number);
}
```

Hasil: 1 - 5

```
Number :1
Number :2
Number :3
Number :4
Number :5
```

Misal: perulangan 5 - 1

```java
for(int number = 5; number >= 1; number-- ){
    System.out.println("Number :"+ number);
}
```

Hasil: 5 - 1

```
Number :5
Number :4
Number :3
Number :2
Number :1
```



**Penjelasan**

**mulai**

`mulai` merupakan nilai awal untuk perulangan. disini saya ingin memulai angkanya dari angka 1, maka saya berikan nilai 1.

misal: 

```java
int number = 1;
```

**kondisi**

persyaratan kondisi jika terpenuhi (bernilai `true`). disini saya ingin memberikan kondisi jika masih jangkauan di angka 1 - 5.

```java
number <= 5;
```

ulangi kode yang ada di dalam block perulangan, jika number nilai kurang dari dan sama dengan angka 5.

**tipe_perulangan**

disini saya bisa mengatur apakah perulangannya bertambah dan berkurang.

pertambah

```java
number++
```

berkurang

```
number--
```

!> jika salah akan terjadi perulangan tiada henti (infinity loop)

```java
int number = 5; number > 1; number--
```

**blok pada for**
area blok di for ditandai `{`  dan `}`

```java
for () {
    // area blok yang akan diulang
}
```

