# Case: Package

package: kendaraan

- Motor
- Mobil
- Kereta





Mobil.java

```java
public class Mobil {
    public static void jumlahBan(){
        System.out.println("Ban mobil");
    }
}
```

Motor.java

```java
public class Motor {
    public static void jumlahBan(){
        System.out.println("Ban motor 2");
    }
}
```

Kereta.java

```java
public class Kereta {
    public static void jumlahBan(){
        System.out.println("Ban kereta banyak");
    }
}
```



Main.java

```java
Mobil.jumlahBan();
```

jangan lupa `import`

```java
import com.belajar.javafundamental.basic.kendaraaan.Kereta;
import com.belajar.javafundamental.basic.kendaraaan.Mobil;
import com.belajar.javafundamental.basic.kendaraaan.Motor;
```

