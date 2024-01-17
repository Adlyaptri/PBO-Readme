## PBO-Readme
# JOBSEET 1
A. Java

Karakteristik Java: collaborative, general purpose, concurrent, class-based, object-oriented.
Prinsip Write Once, Run Anywhere (WORA).
B. Perbedaan JDK, JRE, dan JVM
a) JDK: Development Kit yang menyediakan lingkungan pengembangan dan JRE.
b) JRE: Runtime Environment untuk menjalankan program Java.
c) JVM: Java Virtual Machine sebagai komponen penting.

C. IDE (Integrated Development Environment)
Pemrograman Java melalui text editor (Notepad++, Sublime Text) dan IDE (NetBeans).
Penggunaan NetBeans IDE sebagai contoh IDE Java.

D. Package
Mekanisme package untuk membedakan class dengan nama yang sama.
Sinkronisasi package dengan struktur direktori berkas source code dan hasil kompilasinya.

E. Import
Penggunaan import untuk memasukkan method atau perintah dalam bahasa pemrograman Java.

F. Class, Object, Method, Variable
Konsep dasar pemrograman berorientasi objek: class sebagai blueprint, object sebagai instance, method sebagai kumpulan pernyataan, variable sebagai tempat penyimpanan data.

KESIMPULAN
Praktikum ini memberikan pemahaman mendalam mengenai konsep dasar Java, penggunaan IDE, package, import, dan pemrograman berorientasi objek. Mahasiswa diharapkan mampu membuat program sederhana dan memahami struktur dasar pengembangan aplikasi Java.
Praktikum ini berhasil memberikan pemahaman yang baik mengenai bahasa pemrograman Java dan konsep dasarnya. Mahasiswa diharapkan dapat mengaplikasikan konsep yang telah dipelajari dalam pengembangan aplikasi Java lebih lanjut.


# JOBSHEET 2 Java Basic Syntax
A. Package
Mekanisme package untuk membedakan class dengan nama yang sama.
Sinkronisasi package dengan direktori berkas source code (.java) dan hasil kompilasinya (.class).

B. Import
Penggunaan import sebagai perintah untuk memasukkan method atau perintah ke dalam program Java.

C. Class, Object, Method, Variable
Konsep dasar class sebagai cetak biru atau blueprint.
Object sebagai hasil cetakan dari class.
Method sebagai tindakan atau prilaku dalam class.
Variable sebagai data dalam class.

D. Java Archive (JAR)
Konsep pemaketan program Java menggunakan JAR.
Pembuatan berkas JAR dan penjelasan tentang metadata di dalamnya.

KESIMPULAN
Praktikum ini berhasil memberikan pemahaman mendalam mengenai mekanisme package, import, dan konsep dasar dalam pemrograman Java. Selain itu, mahasiswa juga memahami proses pemaketan menggunakan JAR dan kegunaannya dalam distribusi program.
Praktikum ini memberikan landasan pemahaman yang kuat mengenai konsep dasar pemrograman Java, organisasi kode dengan package, import, dan penggunaan JAR untuk distribusi program. Mahasiswa diharapkan dapat menerapkan konsep-konsep ini dalam pengembangan program Java lebih lanjut.


# JOBSHEET 3 Java Variables & Data Types
A. Variables
Variabel sebagai satuan dasar penyimpanan dalam program Java.
Konsep nilai atau value yang dapat berubah selama berjalannya program.
Tipe variabel dalam Java: local variable, static variable, dan instance variable.

B. Data Types
Penggunaan tipe data untuk menentukan jenis nilai atau value yang akan disimpan di dalam memori dan diproses dalam program.
Tipe data primitive: int, float, double, char, boolean, dll.
Tipe data bentukan: definisi dan penggunaan.

KESIMPULAN
Praktikum ini berhasil memberikan pemahaman mendalam mengenai konsep variabel, tipe data, dan perbedaan antara tipe data primitive dengan tipe data bentukan. Mahasiswa dapat mengaplikasikan variabel dan tipe data dalam pembuatan program Java sederhana.

Praktikum ini memberikan dasar pemahaman yang kuat mengenai penggunaan variabel dan tipe data dalam pemrograman Java. Mahasiswa diharapkan mampu mengimplementasikan konsep-konsep ini dalam pengembangan program yang lebih kompleks.


# JOBSHEET 4 Java Operators
A. Java Operators
Java Operators sebagai simbol-simbol untuk memanipulasi atau mengolah variabel.
Variabel yang dioperasikan disebut operand.
Pembagian Java Operators berdasarkan jumlah operand:
a) Unary Operator
b) Binary Operator
c) Ternary Operator

KESIMPULAN
Praktikum ini memberikan pemahaman mengenai penggunaan Java Operators dan konsep operand. Mahasiswa diharapkan dapat menggunakan operator-operator tersebut secara efektif dalam pemrograman Java.


# JOBSHEET 5 Input Data Keyboard
A. Kelas Scanner
Digunakan secara ekstensif untuk memasukkan data dari keyboard.
Data yang dimasukkan, seperti angka, tidak perlu dikonversi dari String ke tipe data lainnya.
Berada dalam paket java.util.
Deklarasi umum: import java.util.Scanner; dan Scanner BacaInput = new Scanner(System.in);

B. Kelas BufferedReader
Menggunakan fungsi readLine() untuk menerima inputan dari keyboard.
Perlu mengimport library import java.io.BufferedReader; import java.io.InputStreamReader; import java.io.IOException;

C. Kelas JOptionPane
Menggunakan dialog box dari javax.swing package.
Memudahkan user dengan tampilan dialog box.
Perlu mengimport library import javax.swing.JOptionPane; atau import javax.swing.*;

D. Perbedaan Kelas Scanner, BufferedReader, dan JOptionPane
Kelas Scanner: Variabel untuk perhitungan matematika tidak perlu dikonversi, bisa langsung dihitung.
Kelas BufferedReader: Perlu konversi sebelum dilakukan perhitungan matematika pada variabel yang akan digunakan.
Kelas JOptionPane: Digunakan untuk input dan output data berbasis GUI swing, memberikan tampilan dialog box.

KESIMPULAN
Praktikum ini memberikan pemahaman mengenai penggunaan kelas Scanner, BufferedReader, dan JOptionPane dalam menerima input dari pengguna dalam pemrograman Java. Mahasiswa diharapkan dapat memilih kelas yang sesuai dengan kebutuhan aplikasi yang dikembangkan.


# JOBSHEET 6 Java Decision Making
A. Percabangan IF
Bentuk percabangan sederhana dengan hanya satu kondisi pada pemilihan IF.
Contoh:
if (kondisi) {
    // pernyataan yang dieksekusi jika kondisi terpenuhi
}

B. Percabangan IF-ELSE
Menyertakan bagian ELSE untuk menangani situasi ketika kondisi pada IF tidak terpenuhi.
Contoh:
if (kondisi) {
    // pernyataan yang dieksekusi jika kondisi terpenuhi
} else {
    // pernyataan yang dieksekusi jika kondisi tidak terpenuhi
}

C. Percabangan IF-ELSE-IF
Lebih dari satu kondisi pada percabangan.
Contoh:
if (kondisi1) {
    // pernyataan jika kondisi1 terpenuhi
} else if (kondisi2) {
    // pernyataan jika kondisi2 terpenuhi
} else {
    // pernyataan jika semua kondisi tidak terpenuhi
}

D. Percabangan SWITCH-CASE
Mirip dengan percabangan IF ELSE, namun menggunakan struktur switch dan case.
Contoh:
switch (nilai) {
    case nilai1:
        // pernyataan jika nilai sama dengan nilai1
        break;
    case nilai2:
        // pernyataan jika nilai sama dengan nilai2
        break;
    default:
        // pernyataan jika nilai tidak sama dengan semua nilai yang ada
}

KESIMPULAN
Praktikum ini memberikan pemahaman mengenai penggunaan percabangan IF, IF-ELSE, IF-ELSE-IF, dan SWITCH-CASE dalam membuat keputusan atau memilih jalur eksekusi berdasarkan kondisi tertentu. Mahasiswa diharapkan dapat memilih bentuk percabangan yang sesuai dengan kebutuhan dalam pengembangan program.


# JOBSHEET 7 Java Loop
Praktikum ini membahas pernyataan-pernyataan pengulangan (loop) dalam pemrograman Java, meliputi FOR, WHILE, dan DO-WHILE. Pengulangan memungkinkan eksekusi suatu proses yang berulang tanpa harus menulis kode program yang panjang.

A. Pernyataan FOR
Digunakan untuk mengulang suatu proses dengan menentukan kondisi awal, kondisi terminasi, dan langkah iterasi.
Contoh:
for (int i = 0; i < 10; i++) {
    // pernyataan yang diulang sebanyak 10 kali
}

B. Pernyataan WHILE
Pengecekan kondisi dilakukan sebelum tubuh loop dieksekusi.
Contoh:
while (kondisi) {
    // pernyataan yang diulang selama kondisi terpenuhi
}

C. Pernyataan DO-WHILE
Tubuh loop dieksekusi setidaknya satu kali sebelum pengecekan kondisi.
Contoh:
do {
    // pernyataan yang diulang minimal sekali
} while (kondisi);

KESIMPULAN
Praktikum ini memberikan pemahaman mengenai pernyataan pengulangan FOR, WHILE, dan DO-WHILE dalam pemrograman Java. Mahasiswa diharapkan dapat memilih jenis pengulangan yang sesuai dengan kebutuhan dalam pengembangan program.


# JOBSHEET 8 Java Array
Praktikum ini membahas konsep array dalam pemrograman Java, meliputi definisi, pendeklarasian, dan penggunaannya. Array merupakan struktur data yang memungkinkan penyimpanan sekumpulan data dengan tipe yang sama, diakses melalui indeks.

A. Pengertian Array
Array adalah variabel yang menyimpan sekumpulan data dengan tipe data yang sama.
Setiap data di array disebut elemen, dan setiap elemen memiliki lokasi atau alamat memori yang berbeda.
Elemen array diakses melalui indeks, yang dimulai dari 0.

B. Pendeklarasian dan Penggunaan Array
Pendeklarasian array dilakukan dengan menyebutkan tipe data elemen, diikuti dengan nama array dan tanda kurung siku [].
Contoh pendeklarasian array:
// Mendeklarasikan array dengan nama 'angka' yang dapat menyimpan 5 data bertipe int
int[] angka = new int[5];
Pengisian dan pengaksesan nilai dalam array:

// Mengisi nilai pada indeks ke-0
angka[0] = 10;

// Mengakses nilai pada indeks ke-0
int nilai = angka[0];

KESIMPULAN
Praktikum ini memberikan pemahaman mengenai array sebagai struktur data dalam pemrograman Java. Mahasiswa diharapkan dapat mendefinisikan, mendeklarasikan, dan menggunakan array dengan baik untuk menyimpan dan mengelola sekumpulan data.


# JOBSHEET 9 Java Class
Praktikum ini membahas konsep dasar Object-Oriented Programming (OOP) dalam pemrograman Java. OOP fokus pada pengorganisasian program berdasarkan objek, yang mencerminkan objek-objek di dunia nyata dengan sifat dan tingkah laku tertentu.

A. Object dan Konsep Dasar OOP
Objek dalam OOP mencerminkan entitas di dunia nyata, seperti mobil, singa, atau manusia.
Setiap objek memiliki sifat (attribut) dan tingkah laku (behavior).
Contoh: Objek mobil memiliki attribut seperti tipe transmisi, warna, dan manufaktur, serta tingkah laku seperti berbelok, mengerem, dan berakselerasi.

B. Konsep Sifat dan Tingkah Laku
Sifat (Attribut): Karakteristik atau data yang dimiliki oleh objek. Misalnya, warna, tipe, atau manufaktur pada objek mobil.
Tingkah Laku (Behavior): Aksi atau kegiatan yang dapat dilakukan oleh objek. Misalnya, berbelok, mengerem, atau berakselerasi pada objek mobil.

KESIMPULAN
Praktikum ini memberikan pemahaman mendasar tentang konsep OOP, terutama fokus pada objek, sifat, dan tingkah laku. Mahasiswa diharapkan dapat mengidentifikasi dan mendefinisikan objek-objek dalam pemrograman Java dengan baik.


# JOBSHEET 10 Clsdd, Object, Property, Method, Constructor, dan Visibility
Praktikum ini membahas konsep dasar Object-Oriented Programming (OOP) dengan fokus pada class, object, property, method, constructor, dan visibility. OOP memungkinkan pemrogram untuk mengorganisasikan kode program dengan lebih terstruktur melalui penggunaan class dan objek.

A. Class
Class merupakan blueprint atau cetakan untuk menciptakan suatu instance dari object.
Analogi class dapat diibaratkan dengan laptop, memiliki ciri-ciri seperti merk, keyboard, dan dapat melakukan tindakan seperti menghidupkan atau mematikan.

B. Object
Objek adalah hasil cetak dari class atau turunan dari class.
Objek memiliki seluruh ciri-ciri (property dan method) yang dimiliki oleh class.

C. Property
Property atau atribut adalah data yang terdapat dalam sebuah class.
Contoh property pada class laptop: merk, warna, jenis processor, ukuran layar, dll.

D. Method
Method adalah tindakan yang bisa dilakukan di dalam class.
Contoh method pada class laptop: menghidupkan, mematikan, mengganti cover, dll.

E. Constructor
Constructor merupakan method khusus untuk menginisialisasi objek.
Nama constructor harus sama dengan nama class, dan tidak memiliki nilai kembalian.

F. Visibility
Visibility menentukan aturan tentang siapa yang dapat mengakses data/atribut dan method.
Modifiers yang digunakan dalam Java: public, private, dan protected.

KESIMPULAN
Praktikum ini memberikan pemahaman tentang konsep dasar OOP, khususnya terkait class, object, property, method, constructor, dan visibility. Mahasiswa diharapkan dapat memahami struktur dasar dalam pembuatan class dan objek dalam pemrograman Java.


# JOBSHEET 11 Inheritance dan Encapsulation
Praktikum ini membahas dua konsep penting dalam Object-Oriented Programming (OOP), yaitu Inheritance (Pewarisan) dan Enkapsulasi. Inheritance memungkinkan kelas baru mewarisi data dan method dari kelas yang telah ada, sedangkan enkapsulasi berkaitan dengan pembungkusan data dan method untuk menjaga keamanan dan informasi detail.

A. Inheritance (Pewarisan)
Inheritance adalah proses pewarisan data dan method dari superclass (parent class) ke subclass (child class).
Superclass adalah kelas yang mewariskan, sedangkan subclass adalah kelas yang menerima warisan.
Contoh:
// Superclass
class Animal {
    void eat() {
        System.out.println("Eating...");
    }
}

// Subclass
class Dog extends Animal {
    void bark() {
        System.out.println("Barking...");
    }
}

B. Enkapsulasi
Enkapsulasi adalah cara pembungkusan data dan method dalam suatu kelas.
Menyembunyikan informasi detail dari kelas untuk mencapai information hiding.
Penting untuk keamanan dan menghindari kesalahan program.
Contoh:
public class Person {
    private String name;

    public String getName() {
        return name;
    }

    public void setName(String newName) {
        name = newName;
    }
}

KESIMPULAN
Praktikum ini memberikan pemahaman tentang konsep pewarisan (inheritance) dan enkapsulasi dalam OOP. Mahasiswa diharapkan dapat menggunakan inheritance untuk mengorganisir dan mengelola kode program dengan lebih efisien, serta menerapkan enkapsulasi untuk menjaga keamanan dan information hiding.


# JOBSHEET 12 OOP Lanjutan
Praktikum ini membahas prinsip-prinsip dasar dalam Object-Oriented Programming (OOP) dan implementasinya dalam pemrograman Java. OOP adalah paradigma pemrograman yang fokus pada objek sebagai elemen utama, dengan atribut dan perilaku tertentu.

A. Prinsip-prinsip OOP
1. OOPs (Object-oriented Programming System)
Model pemrograman komputer yang menekankan desain perangkat lunak berbasis objek, lebih fokus pada data atau objek daripada fungsi dan logika.
Objek memiliki atribut dan perilaku unik, dan OOP berfokus pada manipulasi objek.

2. Prinsip Pemrograman Berorientasi Objek:
a. Inheritance (Pewarisan)
Membentuk class baru yang mewarisi atau memiliki bagian-bagian dari class yang sudah ada.
Menggunakan sistem hirarki atau bertingkat, memungkinkan pembentukan struktur yang lebih kompleks.

b. Polymorphism
Objek berbeda dapat diakses melalui satu interface.
Objek polymorphic dapat beradaptasi dengan metode apa pun yang diimplementasikan pada objek tersebut.

c. Abstraction
Proses menyembunyikan detail implementasi dan hanya menampilkan fungsionalitas umum.
Dibagi menjadi class abstract dan interface.

d. Encapsulation
Konsep pengikatan data atau metode berbeda menjadi satu unit data.
Memudahkan pembacaan kode karena informasi yang disajikan sudah merupakan satu kesatuan.

KESIMPULAN
Praktikum ini memberikan pemahaman mendalam tentang prinsip-prinsip dasar OOP dan implementasinya dalam pemrograman Java. Mahasiswa diharapkan dapat menerapkan inheritance, polymorphism, abstraction, dan encapsulation untuk meningkatkan struktur dan keamanan kode program.
