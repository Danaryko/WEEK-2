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

    ```md
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

      ```md
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

      ```md
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

      ```md
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

      
    ```md
    let foo = 42; // foo is now a number
    foo = "bar"; // foo is now a string
    foo = true; // foo is now a boolean
    ```
    
    &nbsp;


    - Type Of Operator
      
      - STRING

        Untuk mengecek tipe data, dan bisa juga dilakukan untuk perbandingan.
      
      Contoh :

      ```md
      let hewan = "Kancil"
      Typeof hewan
      Output : 'String'
      ```

      &nbsp;

       - Properties String.length

         Jika ingin mengecek berapa karakter yang ada di string variabel diatas:

      ```md
      hewan.length
      Output : 6
      ```

      &nbsp;

    - Method & Prototype

        Method adalah kemampuan yang dimiliki oleh string.
        Method dalam String itu banyak sekali, dan mungkin saya akan menjelaskan beberapa saja diantaranya yaitu :

      - To UpperCase & ToLowerCase

        Method To UpperCase fungsinya yaitu mengubah String didalam variabel menjadi huruf kapital.

        Contoh :

        ```md
        Let Hewan = "Buaya"
        console.log(Hewan.ToUpperCase())
        Output : BUAYA
        ```

        &nbsp;

        Method ToLowerCase fungsinya yaitu mengubah string didalam variabel menjadi huruf kecil.

        Contoh :

        ```md
        Let Hewan = "Buaya"
        console.log(Hewan.ToLowerCase())
        Output : buaya
        ```

        &nbsp;