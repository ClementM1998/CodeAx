# CodeAx

CodeAx adalah bahasa pengaturcaraan objektif berorientasikan fungsi yang direka untuk menjadi ringkas, mudah, dan efisien. Ia menggabungkan ciri-ciri berorientasikan objek dan fungsional, dengan struktur dan sintaks yang disesuaikan bagi memudahkan pengurusan kelas serta pengendalian fail.

## Ciri-ciri Utama

- **Pengurusan Kelas**: CodeAx menggunakan pendekatan satu kelas per fail, di mana nama fail mesti sepadan dengan nama kelas.
- **Fungsi Utama (`main`)**: Kata kunci `main` digunakan sebagai titik mula dalam fail, tanpa `;` sebagai penamat baris.
- **Pendekatan OOP**: Menyokong pendekatan OOP, tetapi membolehkan fungsi didefinisikan di luar kelas.
- **Komen**: Menggunakan `~` untuk komen satu baris dan `~* ... *~` untuk komen berbilang baris.
- **Pengimportan Fail**: `import <lib>` untuk perpustakaan CodeAx dan `import "lib"` untuk perpustakaan tersuai.
- **Jenis Data Asas**: Menyediakan jenis data seperti `int`, `float`, `long`, `double`, `char`, dan `boolean`.
- **Warisan (Inheritance)**: Menggunakan simbol `:` untuk warisan kelas dan antaramuka.
- **Kelas Statik**: Menyokong kelas statik, di mana semua fungsi dalam kelas tersebut menjadi `static`.

## Contoh Kod

Berikut adalah contoh kod dalam fail `helloWorld.ax`:

**Nama Fail**: `helloWorld.ax`

```java
main helloWorld() {
    System.println("Hello, World!")
}

~* Definisi kelas Person *~
class Person {
    int id

    public void set(int id) {
        Person.id = id
    }

    public int get() {
        return Person.id
    }
}
