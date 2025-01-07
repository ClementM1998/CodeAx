# CodeAx

CodeAx adalah bahasa pengaturcaraan berorientasikan objek (OOP) yang direka untuk memberi kemudahan dalam menulis kod yang ringkas dan efisien. Berikut adalah beberapa ciri penting:

## Ciri-Ciri Utama

- **Paradigma**: Berorientasi Objek (OOP)
- **Sintaks**: Tidak menggunakan `;` sebagai penamat baris
- **Fungsi Utama**: Menggunakan kata kunci `main` sebagai titik masuk utama
- **Jenis Data**: Menyokong jenis data `int`, `float`, `long`, `double`, `char`, dan `boolean`
- **Inheritance**: Menggunakan `:` sebagai simbol pewarisan
- **Modulariti**: Setiap fail hanya boleh mempunyai satu kelas, satu interface, atau satu enum
- **Perulangan dan Kondisi**: Menyokong `for`, `while`, `do while`, `if`, `else`, dan operator ternari `? :`
- **Pengurusan Fail**: Fail utama mesti sepadan dengan nama kelas atau fungsi utama (`main`) di dalamnya

## Struktur Fail
- **Satu Class, Interface, atau Enum per Fail**: CodeAx hanya membenarkan satu class, interface, atau enum bagi setiap fail, kecuali untuk fail utama.
- **Fail Utama**: Dalam fail utama, pengguna boleh memasukkan lebih daripada satu elemen, iaitu class, interface, dan enum, semuanya boleh berada dalam fail ini.

## Senarai Kata Kunci

Berikut ialah senarai kata kunci yang disokong oleh CodeAx:

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
- `interface`
- `enum`
- `true`
- `false`
- `void`
- `null`

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
