# CodeAx

CodeAx adalah bahasa pengaturcaraan yang menyokong pemrograman berorientasikan objek (OOP) dan fungsi. Ia direka untuk memudahkan pengaturcaraan dengan sintaks yang ringkas dan mudah dipelajari.

## Ciri-ciri Utama

- **Pemrograman Berorientasikan Objek**: Menyokong konsep OOP seperti kelas dan objek.
- **Sintaks Ringkas**: Memudahkan pemahaman dan penulisan kod.
- **Menyokong Pelbagai Jenis Data**: Termasuk `int`, `float`, `long`, `double`, `char`, dan `boolean`.
- **Struktur Kawalan**: Menyokong `if`, `else`, `for`, `while`, dan `do while`.
- **Fungsi Dalam Kelas dan Luar Main**: Semua fungsi mesti diletakkan di luar blok `main` atau dalam kelas.

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

## Operasi dan Simbol

Berikut adalah senarai operasi dan simbol yang disokong dalam CodeAx:

### 1. Operasi Aritmetik

- `+`  : Penjumlahan
- `-`  : Pengurangan
- `*`  : Pendaraban
- `/`  : Pembahagian
- `%`  : Modulus (sisa)

### 2. Operasi Perbandingan

- `==` : Sama dengan
- `!=` : Tidak sama dengan
- `>`  : Lebih besar daripada
- `<`  : Kurang daripada
- `>=` : Lebih besar atau sama dengan
- `<=` : Kurang atau sama dengan

### 3. Operasi Logik

- `&&` : Dan (AND)
- `||` : Atau (OR)
- `!`  : Tidak (NOT)

### 4. Simbol Penugasan

- `=`  : Penugasan asas
- `+=` : Tambah dan kemudian penugasan
- `-=` : Tolak dan kemudian penugasan
- `*=` : Darab dan kemudian penugasan
- `/=` : Bahagi dan kemudian penugasan
- `%=` : Modulus dan kemudian penugasan

### 5. Operator Ternari

- `? :` : Operator ternari digunakan untuk membuat keputusan ringkas. Sintaks adalah seperti berikut:
```java
condition ? valueIfTrue : valueIfFalse
```

## Contoh Kod CodeAx

Berikut adalah contoh kod kelas Test.ax

```java
main Test() {
    System.println("Hello World")
}
```

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
