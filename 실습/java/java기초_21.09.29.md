# Java

*****

### ๐ป ๊ธฐ์ด ๋ช๋ น์ด ์ค๋ช ๐ป

***

##### ๐ก ๊ธฐ๋ณธ๊ตฌ์ฑ ๐ก

```java
// ํจํค์ง๋ช
package mc.sn.Example;

// ๋ฉ์ธ ํด๋์ค
public class Test {

    // ๋ฉ์ธ ๋ฉ์๋
	public static void main(String[] args) {
        
    }
}
```

****

##### ๐ก ์ถ๋ ฅ ๐ก

```java
package mc.sn.Example;

public class Test {

	public static void main(String[] args) {
        // ์ถ๋ ฅ ๋ช๋ น
        System.out.println("Hello World!");			// 1๋ฒ
        System.out.print("Hello World!");			// 2๋ฒ
        System.out.println();					   // 3๋ฒ
        
    }
}
```

1๋ฒ ๋ผ์ธ ์ถ๋ ฅ (โ์ ์ปค์ ์์น) : **์ถ๋ ฅํ๊ณ  ์ค๋ฐ๊ฟ**

```
Hello World!
โ
```

2๋ฒ ๋ผ์ธ ์ถ๋ ฅ(โ์ ์ปค์ ์์น) : **์ถ๋ ฅํ๊ณ  ์ค๋ฐ๊ฟ ์ํจ**

```java
Hello World!โ
```

3๋ฒ ๋ผ์ธ ์ถ๋ ฅ(โ์ ์ปค์ ์์น) : **์ถ๋ ฅ์์ด ์ค๋ฐ๊ฟ**

```java

โ
```

*****

๐ก ์๋ ฅ ๐ก

```java 
package mc.sn.Example;

// ์๋ ฅ ๋ฉ์๋ Scanner ์ฌ์ฉ์ ์ํ import๋ฅผ ํด์ค์ผํจ
import java.util.Scanner;

public class Test {

	public static void main(String[] args) {
        int A;		// ์ ์ํ ๋ณ์
        float B;	// ์ค์ํ ๋ณ์
       	String C;	// ๋ฌธ์์ด ๋ณ์
        
        // ์๋ ฅ ๋ฉ์๋ ์ธ์คํด์คํ
        Scanner sc = new Scanner();
        // ์๋ ฅ ๋ช๋ น
        A = sc.nextInt();
        B = sc.nextFloat();
        C = sc.nextLine();      
    }
}
```

