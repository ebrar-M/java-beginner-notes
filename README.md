[![Stars](https://img.shields.io/github/stars/ebrar-M/java-beginner-notes?logo=github&label=Stars&style=flat)](https://github.com/ebrar-M/java-beginner-notes/stargazers)
[![Forks](https://img.shields.io/github/forks/ebrar-M/java-beginner-notes?logo=github&label=Forks&style=flat)](https://github.com/ebrar-M/java-beginner-notes/network/members)
![Last commit](https://img.shields.io/github/last-commit/ebrar-M/java-beginner-notes?label=last%20commit&style=flat)
![Java](https://img.shields.io/badge/Java-17-blue?logo=java&logoColor=white&style=flat)

**---**


## 🌍 Languages
- 🇹🇷 [Türkçe](#-tr-türkçe)
- 🇬🇧 [English](#-gb-english)


## 🇹🇷 TR Türkçe

"# Java Notları Yeni Başlayanlar için ☕  

**---**

## 1. Java Nedir?

Java, **bir programlama dili** ve **bir platform**dur:

```yaml
- ✅ Nesne Yönelimli (OOP)  
- 🌍 Platformdan bağımsız (Bir kez yaz, her yerde çalıştır)  
- 🏢 Kurumsal, Android, arka uç sistemlerde yaygın olarak kullanılır  
- 🆓 Ücretsiz ve açık kaynak  

// Örnek: İlk Java programınız
public class Hello {
    public static void main(String[] args) {
        System.out.println("Merhaba, Java 🚀");
    }
}

# Çalıştır
java Hello, Java 🚀
```

**---**

## 2. Kurulum ⚙️

```yaml
- ⬇️ İndir: https://www.oracle.com/java/technologies/javase-downloads.html veya https://openjdk.org/
- 💻 Yükle: yükleyiciyi takip et
- 🧪 Doğrula: Terminal'i aç → `java -version` ve `javac -version`
```

**---**


## 3. Temeller ✨

### Değişkenler ve Veri Tipleri 📦

```java
String name = "Ebrar";   // Metin
int age = 20;            // Tam sayı
double pi = 3.14;        // Ondalık
boolean isStudent = true;// Doğru/Sahte

System.out.println(name + " " + age + " " + pi + " " + isStudent);
```


**---**

### Operatörler ⚡

```java
int x = 10;
int y = 3;

System.out.println(x + y);             // 13
System.out.println(x > y);             // true
System.out.println(x % y);             // 1
System.out.println(x > 5 && y < 5);    // true
```


**---**

### Kontrol Akışı 🔀

```java
int x = 7;

if (x > 10) {
    System.out.println("x, 10'dan büyük");
} else if (x == 7) {
    System.out.println("x, tam olarak 7 🎯");
} else {
    System.out.println("x, 10'dan küçük");
}

// for döngüsü
for (int i = 0; i < 3; i++) {
    System.out.println("Tekrar: " + i);
}

// while döngüsü
int count = 0;
while (count < 3) {
    System.out.println("Sayım: " + count);
    count++;
}
```


**---**


## 4. Veri Yapıları 📦

```java
// Dizi
String[] fruits = {"elma", "muz", "kiraz"};
System.out.println(fruits[0]); // elma

// ArrayList
import java.util.ArrayList;
ArrayList<String> colors = new ArrayList<>();
colors.add("kırmızı");
colors.add("yeşil");
System.out.println(colors);

// HashMap
import java.util.HashMap;
HashMap<String, Integer> person = new HashMap<>();
person.put("yaş", 20);
System.out.println(person.get("yaş")); // 20
```


**---**


## 5. Metodlar 🛠️

```java
public class Main {
    // Parametresiz metod
    static void greet() {
        System.out.println("Merhaba, Java Başlangıcı! 🚀");
    }

    // Parametreli metod
    static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        greet();
        System.out.println(add(3, 5));
    }
}
```


**---**


## 6. Nesne Yönelimli Programlama (OOP) 🏗️

```java
class Person {
    String name;
    int age;

    Person(String n, int a) {
        this.name = n;
        this.age = a;
    }

    void greet() {
        System.out.println("Merhaba, benim adım " + name + " ve ben " + age + " yaşındayım");
    }
}

class Student extends Person {
    String studentId;

    Student(String n, int a, String id) {
        super(n, a);
        this.studentId = id;
    }
}

public class Main {
    public static void main(String[] args) {
        Person p1 = new Person("Ebrar", 20);
        p1.greet();

        Student s1 = new Student("Ebrar", 20, "ST123");
        System.out.println(s1.studentId);
    }
}
```


**---**

## 🚀 Sonraki Adımlar

```yaml
- 🧩 Pratik: Daha fazla Java programı yazın
- 📂 Keşfet: Küçük projeler oluşturun (hesap makinesi, yapılacaklar uygulaması)
- 📱 Android geliştirme deneyin
- 🤝 İşbirliği: açık kaynak Java projelerine katkıda bulunun
```

## > Java güçlüdür ve her yerdedir. Her gün kod yazarak öğrenin 🚀"

**---**


## 🇬🇧 GB English

# Java Notes for Beginners ☕  

**---**

## 1. What is Java?

Java is a **programming language** and a **platform** that is:

```yaml
- ✅ Object-Oriented (OOP)  
- 🌍 Platform-independent (Write once, run anywhere)  
- 🏢 Widely used in enterprise, Android, backend systems  
- 🆓 Free and open-source  

// Example: Your first Java program
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, Java 🚀");
    }
}

# Run
java Hello, Java 🚀
```

**---**

## 2. Setup ⚙️

```yaml
- ⬇️ Download: https://www.oracle.com/java/technologies/javase-downloads.html or https://openjdk.org/
- 💻 Install: follow installer
- 🧪 Verify: open Terminal → `java -version` and `javac -version`
```

**---**


## 3. Basics ✨

### Variables and Data Types 📦

```java
String name = "Ebrar";   // Text
int age = 20;            // Integer
double pi = 3.14;        // Decimal
boolean isStudent = true;// True/False

System.out.println(name + " " + age + " " + pi + " " + isStudent);
```


**---**

### Operators ⚡

```java
int x = 10;
int y = 3;

System.out.println(x + y);             // 13
System.out.println(x > y);             // true
System.out.println(x % y);             // 1
System.out.println(x > 5 && y < 5);    // true
```


**---**

### Control Flow 🔀

```java
int x = 7;

if (x > 10) {
    System.out.println("x is greater than 10");
} else if (x == 7) {
    System.out.println("x is exactly 7 🎯");
} else {
    System.out.println("x is less than 10");
}

// for loop
for (int i = 0; i < 3; i++) {
    System.out.println("Repeat: " + i);
}

// while loop
int count = 0;
while (count < 3) {
    System.out.println("Count: " + count);
    count++;
}
```


**---**


## 4. Data Structures 📦

```java
// Array
String[] fruits = {"apple", "banana", "cherry"};
System.out.println(fruits[0]); // apple

// ArrayList
import java.util.ArrayList;
ArrayList<String> colors = new ArrayList<>();
colors.add("red");
colors.add("green");
System.out.println(colors);

// HashMap
import java.util.HashMap;
HashMap<String, Integer> person = new HashMap<>();
person.put("age", 20);
System.out.println(person.get("age")); // 20
```


**---**


## 5. Methods 🛠️

```java
public class Main {
    // Method without parameters
    static void greet() {
        System.out.println("Hello, Java Beginner! 🚀");
    }

    // Method with parameters
    static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        greet();
        System.out.println(add(3, 5));
    }
}
```


**---**


## 6. Object-Oriented Programming (OOP) 🏗️

```java
class Person {
    String name;
    int age;

    Person(String n, int a) {
        this.name = n;
        this.age = a;
    }

    void greet() {
        System.out.println("Hi, my name is " + name + " and I am " + age);
    }
}

class Student extends Person {
    String studentId;

    Student(String n, int a, String id) {
        super(n, a);
        this.studentId = id;
    }
}

public class Main {
    public static void main(String[] args) {
        Person p1 = new Person("Ebrar", 20);
        p1.greet();

        Student s1 = new Student("Ebrar", 20, "ST123");
        System.out.println(s1.studentId);
    }
}
```


**---**

## 🚀 Next Steps

```yaml
- 🧩 Practice: Write more Java programs
- 📂 Explore: Build mini projects (calculator, to-do app)
- 📱 Try Android development
- 🤝 Collaborate: Contribute to open-source Java projects
```

## > Java is powerful and everywhere. Learn it by coding daily 🚀



