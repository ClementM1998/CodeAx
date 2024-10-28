# CodeAx

CodeAx adalah sebuah bahasa pengaturcaraan objektif berorientasikan fungsi yang direka untuk menjadi ringkas, mudah, dan efisien. Ia mempunyai struktur unik dengan ciri-ciri yang disesuaikan khusus untuk memudahkan pengurusan kelas dan pengendalian fail. CodeAx direka supaya boleh diimplementasi dengan mudah menggunakan Java.

## Ciri-ciri Utama
- **Pengurusan kelas yang mudah**: CodeAx menggunakan pendekatan satu kelas bagi setiap fail, dan nama fail mesti sepadan dengan nama kelas.
- **Fungsi utama (`main`)**: Fungsi utama bagi setiap fail menggunakan kata kunci `main`, tanpa penggunaan `;` sebagai penamat baris.
- **Ciri OOP dan fungsi**: Menyokong pendekatan OOP, tetapi membolehkan kaedah didefinisikan di luar kelas.
- **Sokongan komen**: Menggunakan `~` untuk komen satu baris.
- **Pengimportan fail**: Menyokong `import <lib>` untuk perpustakaan CodeAx dan `import "lib"` untuk perpustakaan tersuai.
- **Data types**: Menyediakan jenis data asas seperti `int`, `float`, `long`, `double`, `char`, dan `boolean`.
- **Inheritance**: Menggunakan simbol `:` untuk warisan kelas dan antaramuka.

## Contoh Kod

Berikut adalah contoh struktur kod dalam CodeAx:

```plaintext
`helloWorld.ax`:

```java
main helloWorld() {
    System.println("Hello, World!")
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
