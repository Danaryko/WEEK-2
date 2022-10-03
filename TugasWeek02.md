# **Rangkuman Week 2**

## Algoritma dan Struktur Data

- Algoritma

  - <div align="justify">Algortima Adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Untuk menyelesaikan suatu masalah, tentunya kita harus mempunyai data struktur, nah data inilah yang akan kita gunakan untuk menyelesaikan suatu masalah dengan menggunakan algoritma.

  &nbsp;

  - Mengapa kita memerlukan algoritma?

    Manfaat algoritma antara lain:

    - <div align="justify">Membantu menyederhanakan suatu program yang rumit dan juga besar.
    - <div align="justify">Mempermudah pembuatan program yang dapat menyelesaikan masalah tertentu.
    - <div align="justify">Membantu menyelesaikan suatu masalah dengan logika dan juga sistematis.

  &nbsp;

  - Kualitas Algortima

    Kualitas wajib dari algoritma

    - <div align="justify">Input dan output harus didefinisikan terlebih dahulu dengan tepat
    - <div align="justify">Setiap step harus benar-benar clear dan tidak ambigu
    - <div align="justify">Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu.
    - <div align="justify">Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.

    &nbsp;

  - Penggunaan Algortima

    - Soal
      <div align="justify">Buatlah Algoritma untuk menyelesaikan problem ini

      David memiliki program yang membutuhkan untuk convert data dari jumlah jam ke detik

      Contohnya jika program memiliki input 2 jam maka output yang diharapkan adalah 7200 detik

    - Jawaban

      - Mulai
      - Deklarasi variabel n, hasil_convert
      - Menambahkan nilai n
      - <div align="justify">Melakukan proses (n jam = n \* 3600" lalu disimpan ke dalam hasil_convert
      - Menampilkan hasil convert (n jam) = + "detik"
      - Stop

    &nbsp;

- Pseudocode

  - <div align="justify">Pseudocode adalah menuliskan algoritma sebelum kita implementasikan ke bahasa pemograman tertentu.

    &nbsp;

  - Bagaimana menulis pseudocode

    - <div align="justify">Menggunakan HURUF BESAR pada kata kunci (key commands).

      CONTOH: IF number is > 10 THEN …

    - 1 statement = 1 baris
    - Gunakan indentasi
    - Simpel

    Contoh :

    ```javascript
    STORE "width" with any number
    STORE "height" with any nummber
    STORE "area" without any value

    CALCULATE "width" times "height"
    SET "area" value with calculation result
    DISPLAY "area"
    ```

    &nbsp;

  - Pseudocode berdasarkan kondisi masalah

    - Procedural

      Procedural adalah cara berpikir secara runtun. Artinya serangkaian perintah yang berurutan.

      Contoh :

      ```javascript
      STORE "width" with any number
      STORE "height" with any nummber
      STORE "area" without any value

      CALCULATE "width" times "height"
      SET "area" value with calculation result
      DISPLAY "area"
      ```

      &nbsp;

    - Conditional

      Conditional digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi.

      Jika hari ini tidak hujan, maka Bob pergi ke pasar,

      jika tidak maka Bob dirumah aja.

      ```javascript
      IF "bright"
      DO "go to the market"
      ELSE
      DO "stay at home"
      ```

    &nbsp;

    - Looping

      Komputer dapat melakukan sebuah proses yang sama berulang-ulang.

      Jika membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping.

      Contoh :

      ```javascript
      STORE "count" t0 1

      WHILE "count" < 11
      DISPLAY "count"
      CALCULATE "count" mod 2
      STORE "reminder" value with calculation result
      IF "reminder" equals to 0
      DISPLAY "EVEN!"
      ELSE
      DISPLAY "ODD!"
      ```

      &nbsp;

    - Recursive

      Recursive adalah pola pikir dalam algoritma yang memanggil method/function didalam sebuah function

## Built-In Method dan Prototype

  JavaScript adalah bahasa dinamis dengan tipe dinamis. Variabel dalam JavaScript tidak secara langsung terkait dengan jenis nilai tertentu, dan variabel apa pun dapat diberi (dan ditetapkan ulang) nilai dari semua jenis: 

  
  ```javascript
  let foo = 42; // foo is now a number
  foo = "bar"; // foo is now a string
  foo = true; // foo is now a boolean
  ```
    
  &nbsp;


  #### **Type Of Operator**
      
  - **STRING**

      Untuk mengecek tipe data, dan bisa juga dilakukan untuk perbandingan.
      
        Contoh :

      ```javascript
      let hewan = "Kancil"
      Typeof hewan
      Output : 'String'
      ```

      &nbsp;

       - Properties String.length

         Jika ingin mengecek berapa karakter yang ada di string variabel diatas:

      ```javascript
      hewan.length
      Output : 6
      ```

      &nbsp;

    #### **Method & Properties**

      Method adalah kemampuan yang dimiliki oleh string.
      Method dalam String itu banyak sekali, dan mungkin saya akan menjelaskan beberapa saja diantaranya yaitu :

      - To UpperCase & ToLowerCase

        > Method To UpperCase fungsinya yaitu mengubah String didalam variabel menjadi huruf kapital.

        Contoh :

        ```javascript
        let Hewan = "Buaya"
        console.log(Hewan.ToUpperCase())
        Output : BUAYA
        ```

        &nbsp;

        > Method ToLowerCase fungsinya yaitu mengubah string didalam variabel menjadi huruf kecil.

        Contoh :

        ```javascript
        let Hewan = "Buaya"
        console.log(Hewan.ToLowerCase())
        Output : buaya
        ```

        &nbsp;

      - charAt

        > charAt akan mengembalikan sebuah karakter berdasarkan posisi index nya yang sudah ditentukan.

        Syntax

        ```javascript
        charAt(index)
        ```
        &nbsp;

        Contoh :

        ```javascript
        let Hewan = "Buaya"
        console.log(Hewan.charAt(1))
        Output : u
        ```
        &nbsp;

      - Includes

        > Includes merupakan method untuk melakukan Pencarian, jika ditemukan akan mengembalikan nilai _true_ jika salah akan mengembalikan nilai _false_.

        Contoh :

        ```javascript
        let Hewan = "Buaya"
        console.log(Hewan.includes("B"))
        Output : true
        ```
        &nbsp;

      - Split
        > Method ini membutuhkan sebuah pola, lalu dibagi dari string yang dituju. Setelah dipisah akan menjadi sebuah data _Array_.
      
        Contoh : 

        ```javascript
        let Kata = "Semua manusia pada dasarnya akan mati"
        console.log(Kata.split(""))
        Output : ['Semua', 'manusia', 'pada', 'dasarnya', 'akan', 'mati']
        ```
        &nbsp;

        > Method includes merupakan salah satu method yang mempunyai sifat Case-sensitivity. 

        Contoh :

        ```javascript
        "Blue whale".includes("blue")
        Output : false
        ```
        &nbsp;

  - **NUMBER**

      Number adalah objek pembungkus yang digunakan untuk mewakili dan memanipulasi angka seperti 1 atau -1.

      - Number Method

        -  isNaN

            >Method ini fungsi nya yaitu untuk mengecek apakah variabel didalam data number atau string, jika number akan memunculkan nilai _false_, jika string akan memunculkan nilai _true_.

            Contoh :

            ```javascript
            isNan(123)
            Output : False
            ```
            &nbsp;

        - toString

          >Method ini fungsi nya yaitu mengubah number menjadi sebuah string. 

          Contoh :

          ```javascript
          isNan(123)
          Output : False
          ```
          &nbsp;

        - toFixed

          >Method ini fungsinya menghitung jumlah angka yang ada di belakang koma.

          Contoh :

          ```javascript
          let nilai = 32,980
          nilai.toFixed(1)
          Output : '32,9'
          ```
          &nbsp;
        

  - Objek Math

     Sama seperti objek pada umumnya, objek Math memiliki properti, nilai, dan method. Objek Math hanya bisa digunakan untuk tipe data number, dan tidak bisa digunakan untuk tipe data BigInt.
     Keuntungan memakai objek Math adalah kita tidak perlu lagi mikir dalam menulis kode ketika membuat operasi Matematika.

      - Objek Math Properties

        Ada 8 properti objek Math, yaitu:

        ```md
        Math.E                  // Bilangan Euler
        Math.LN2             // Log 2 
        Math.LN10           // Log 10
        Math.LOG2E        // Log E di Basis 2
        Math.LOG10E      // Log E di Basis 10
        Math.PI                 // Pi
        Math.SQRT1_2    // Akar Kuadrat dari 0.5
        Math.SQRT2         // Akar Kuadrat dari 2
        ```
        &nbsp;
      Biasanya, properti-properti ini digunakan untuk operasi matematika yang lebih kompleks.

    
      - Objek Math Method

      Method di objek Math ada banyak sekali dan kita bahas beberapa yang sering digunakan.
      
      ```md
      Math.abs() -> mengubah Number yang bernilai negatif menjadi positif.
      Math.pow(x, y) -> Digunakan untuk menghitung hasil dari x pangkat y.
      Math.sqrt(x) -> Digunakan untuk menghitung akar kuadrat dari x.
      Math.round(x) -> Digunakan untuk membulatkan angka desimal x menjadi bilangan bulat. 
      Math.floor(x) -> Digunakan untuk membulatkan angka desimal x ke bawah.
      Math.ceil(x) - > Digunakan untuk membulatkan angka desimal x ke atas.
      Math.random() -> Digunakan untuk menampilkan angka secara acak antara 0 hingga 1 (0 termasuk. 1 tidak).
      Math.max() -> Digunakan untuk mencari angka terbesar di antara parameter.
      Math.min() -> Digunakan untuk mencari angka terkecil di antara parameter. 
      ```
      &nbsp;

## DOM Events
  DOM merupakan singkatan dari Document Object Model. DOM merepresentasikan  halaman dimana kita bisa merubah struktur, style, dan isinya dari sebuah website. DOM bukan Bagian dari javascript, melainkan sebuah Web API untuk membangun website. DOM bisa dipakai di bahasa pemrograman lain.
  DOM adalah jembatan supaya bahasa pemrograman dapat berinteraksi dengan dokumen HTML, dengan memakai DOM, javascript dapat memanipulasi HTML. Beberapa hal yang dapat dilakukan oleh DOM adalah:
    
  - Mengubah elemen HTML pada halaman website
  - Mengubah atribut HTML pada halaman website
  - Mengubah CSS style pada halaman website
  - Menambah/menghapus elemen maupun atribut HTML
  - Menambah HTML event
  - Berinteraksi dengan semua HTML event di website Di dalam  HTML DOM, semua elemen HTML dari sebuah website dianggap sebagai objek. Sebagaimana objek pada
  JavaScript pada umumnya, objek elemen HTML di HTML DOM juga memiliki properti dan method yang lebih dikenal dengan sebutan DOM Property dan DOM Method. Jadi, untuk mengubah value property dari elemen HTML, kita bisa menggunakan DOM Property dan untuk memanggil fungsi dari suatu elemen HTML, kita bisa menggunakan DOM Method.

  Ada 2 item yang akan didapatkan saat mengakses DOM yaitu : 
    
  - Element 

    Bentuk DOM nya seperti element
    
    Seperti :

    ```html
    <h1 id = "title">Hallo</h1>
    ```
    &nbsp;

    Contoh : 

    ```javascript
    let title = document.getElementByid("title")
    console.log(title)
    Output : <h1 id = "title">Hallo</h1>
    ```
    &nbsp;

  - Node

    Bentuk DOM nya seperti Array

    Contoh : 

    ```html
    <ul class="list">
      <li class="item">satu</li>
      <li class="item">dua</li>
      <li class="item">tiga</li>
    </ul>
    ```
    ```javascript
    let itemQuarry = document.querySelector(".item")
    console.log(itemQuarry.parentNode);
    Output : NodeList(3) [li.item, li.item, li.item] 
    ```

















