# Classpath

Pengertian

?> "Mekanisme di java untuk menemukan classs lain"

Umumnya class lain itu berasal dari

1. `library` yang berbeda.
2. `JDK` itu sendiri. misal  class `System` : `System.out.println`.

Bagaimana jika `class` yang dicari tidak ditemukan?

```
ClassNotFoundException atau NoClassDefFoundError.
```



## Lib

Cara Menambahkan Library secara manual

1. Buat `Directory` dengan klik pada root folder project.
2. Beri nama `libs`.
3. Copy Paste file `commons-lang3-3.9.jar` ke folder `libs`. bisa download [disini](https://repo1.maven.org/maven2/org/apache/commons/commons-lang3/3.9/commons-lang3-3.9.jar)
4. jadikan `Library` dengan klik kanan filenya > pilih `Add as Library..` dan pilih `OK`.



./lib/commons-lang3-3.9.jar

```
https://repo1.maven.org/maven2/org/apache/commons/commons-lang3/3.9/commons-lang3-3.9.jar
```

IntelliJ: klik kanan pada file `commons-lang3-3.9.jar` > pilih `Add as Library..`   > lalu pilih `Ok`

Jika berhasil

![](/media/uxcover/CLOUD/workout-docs/belajar-java-fundamental/cases/package/berhasil-tambah-library.png)



Main.java

```java
import org.apache.commons.lang3.time.DateUtils;
...
Date today = new Date();
System.out.println("Hari ini = " + today);
Date tomorrow = DateUtils.addDays(today, 1);
System.out.println("Besok = " + tomorrow);
..
```

out

```
Hari ini = Sat Aug 01 09:56:05 WIB 2020
Besok = Sun Aug 02 09:56:05 WIB 2020
```



> Kekurangan: sangat kurang efektif jika untuk projek besar.

Solusi:

Tool Manager: seperti `Maven` atau `Gradle`.



## References

- http://www.baeldung.com/java-classnotfoundexception-and-noclassdeffounderror
- [https://maven.apache.org](https://maven.apache.org/)
- https://gradle.org
- https://spring.io/guides/gs/maven
- https://spring.io/guides/gs/gradle