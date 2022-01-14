Penjelasan item Pencarian data kucing:

    1. membuat komponen catsList, lalu kita buat juga di dalamnya state cats dan catsTemp.
    2. Data API di tampilkan dalam type data array.
    3. State cats dan catsTemp merupakan tempat menampung data-data kucing dari API.
    4. Menggunakan useEffect untuk mengambil data API tersebut kemudian dimasukan kedalam state cats dan catsTemp,menggunakan fitur axios untuk mengambil datanya.
    5. setelah data diambil dan masuk ke dalam state cats akan menampilkan data tersebut dengan menggunakan .map,
    6. Untuk menampilkan name  menggunakan kode (<h3>{item.name}</h3>), jadi untuk mengambil data tersebut kita harus memasukan kode itu kedalam tag html dan baru kita panggil "item.name".
    7. untuk menampilkan data Imagenya menggunakan kode (<img src = {item.image?.url}/>).
    8. setelah semua datanya sudah dapat ditampilkan selanjutnya siapkan input untuk melakukan pencarian dari data yang sudah kita tampilkan tadi, dimana hasil dari ketikan input tadi akan di simpan di dalam state input.
    9. Lalu setelah itu kita membuat useEffect baru untuk memfilter data yang yang terdapat dalam state catsTemp, lalu cek pada console.
    10. setelah itu akan kita simpan data yang sudah kita filter tadi ke dalam state cats.
    11. Dan kita sudah dapat melakukan pencarian data kucing tadi di state cats menggunakan input.
