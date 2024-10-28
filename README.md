# CodeAx

CodeAx adalah bahasa pengaturcaraan yang menyokong pemrograman berorientasikan objek (OOP) dan fungsi. Ia direka untuk memudahkan pengaturcaraan dengan sintaks yang ringkas dan intuitif.

## Ciri-ciri Utama

- **Pemrograman Berorientasikan Objek**: Menyokong konsep OOP seperti kelas dan objek.
- **Sintaks Ringkas**: Memudahkan pemahaman dan penulisan kod.
- **Menyokong Pelbagai Jenis Data**: Termasuk `int`, `float`, `long`, `double`, `char`, dan `boolean`.
- **Struktur Kawalan**: Menyokong `if`, `else`, `for`, `while`, dan `do while`.
- **Fungsi Dalam Kelas dan Main**: Semua fungsi mesti diletakkan dalam `main` atau dalam kelas.
- **Penggunaan Boolean**: Menyokong penggunaan boolean untuk logik keputusan.

## Katakunci

Berikut adalah senarai katakunci yang disokong dalam CodeAx:

- `class`
- `main`
- `import`
- `public`
- `private`
- `static`
- `int`
- `float`
- `long`
- `double`
- `char`
- `boolean`
- `for`
- `do`
- `while`
- `if`
- `else`
- `? :` (operator ternari)

## Contoh Penggunaan

### 1. Contoh Kelas

```codeax
main test() {
    Person p = new Person
    p.set(1)
    System.println(p.get())
}

class Person {
    int id

    public void set(int id) {
        Person.id = id
    }

    public int get() {
        return Person.id
    }
}

Berikut adalah contoh kod kelas Animal.ax, Cat.ax dan Dog.ax

**Nama Fail**: `Animal.ax`
```java
class Animal {
    public String name
}
```

**Nama Fail**: `Cat.ax`
```java
public class Cat : Animal {

    public void name(String name) {
        Cat.name = name
    }

    public String name() {
        return Cat.name
    }

}
```

**Nama Fail**: `Dog.ax`
```java
public class Dog : Animal {

    public void name(String name) : Dog.name = name

    public String name() : return Dog.name

}
```
