# Langkah 1

Mengaktfikan Ektensi xampp , dengan menghilangkan tanda ; (titik koma) pada bagian ektensi yang akan digunakan kemudian restart apache webs server

![1](https://user-images.githubusercontent.com/81844622/122565603-df86cc80-d070-11eb-9817-9b9d76fe1623.jpg)

# Langkah 2

Menginstall codeigniter 4.  

![2](https://user-images.githubusercontent.com/81844622/122566022-499f7180-d071-11eb-9d99-fa0c9ba20589.jpg)

# Langkah 3

Menjalankan command line interface dan perintah php spark

![3](https://user-images.githubusercontent.com/81844622/122566236-88352c00-d071-11eb-955a-8672761ddc85.jpg)

# Langkah 4

Mengaktifkan mode debugging untuk memudahkan mengetahui pesan eror apabila terjadi kesalahan dalam kode program

![4](https://user-images.githubusercontent.com/81844622/122566647-fa0d7580-d071-11eb-9320-218e42d5ad90.jpg)

Contoh pesan eror dengan menghilangkan titik koma di akhir kode

![5](https://user-images.githubusercontent.com/81844622/122566854-3d67e400-d072-11eb-9ad9-b855d5678844.jpg)

![6](https://user-images.githubusercontent.com/81844622/122566897-4789e280-d072-11eb-8113-224b394a72b9.jpg)

# Langkah 5

Mengecek route, menambahkan controller baru dan menambahkan route baru

![7 - mengecek route](https://user-images.githubusercontent.com/81844622/122567124-8a4bba80-d072-11eb-921d-ef5a81da7683.jpg)

![8](https://user-images.githubusercontent.com/81844622/122567429-d8f95480-d072-11eb-8878-e3a78c030d49.jpg)

# Langkah 6

Mengakses route dengan url localhost/about karena server apache saya mengggunakan kode 80 maka tidak dituliskan localhost:8080/about

![8 5](https://user-images.githubusercontent.com/81844622/122567677-1cec5980-d073-11eb-9921-2c7ed4799bcf.jpg)

# Langkah 7

Mengaktifkan auto rooting dengan mengubah setAutoRoute(true)

![9](https://user-images.githubusercontent.com/81844622/122567962-6f2d7a80-d073-11eb-8917-45e8383827f1.jpg)

# Langkah 8 

Menambahkan method baru pada controller page dan mengaksesnya

![10](https://user-images.githubusercontent.com/81844622/122568202-b7e53380-d073-11eb-8609-b65486872b6f.jpg)

# Langkah 9

Menambahkan layout web dengan menggunakan css disini kita akan menggunakan css dari layout pratikum 4

![11](https://user-images.githubusercontent.com/81844622/122568350-dba87980-d073-11eb-939a-c658bfef3a92.jpg)




# Lanjutan / Pratikum 12




# Langkah 10

Membuat database baru dan membuat tabel

![1](https://user-images.githubusercontent.com/81844622/123042606-46193b00-d421-11eb-9347-6980eb9103eb.jpg)

# Langkah 11

Mengkonfigurasi koneksi database, disini kita akan mengkonfigurasi file .env

![2](https://user-images.githubusercontent.com/81844622/123042745-7660d980-d421-11eb-9f2c-b1b117bb1165.jpg)

# Langkah 12

Membuat model untuk memproses data artikel

![3](https://user-images.githubusercontent.com/81844622/123044481-ebcda980-d423-11eb-8e2f-58bcde17ee6b.jpg)

# Langkah 13

Membuat controller baru dengan nama artikel.php

![4](https://user-images.githubusercontent.com/81844622/123044567-0bfd6880-d424-11eb-9a36-414b2d31b692.jpg)

# Langkah 14

Membuat view baru dengan nama artikel pada direktori app/view

![5](https://user-images.githubusercontent.com/81844622/123044717-3f3ff780-d424-11eb-864e-401be1a09717.jpg)

# Langkah 15

Selanjutnya buka localhost/artikel maka akan tampil seperti ini

![6](https://user-images.githubusercontent.com/81844622/123044822-63033d80-d424-11eb-9135-af9560305228.jpg)

# Langkah 16

Membuat tampilan detail artikel dengan menambahkan controller baru dengan view()

![7](https://user-images.githubusercontent.com/81844622/123046255-16206680-d426-11eb-99cf-4f5b52e48e44.jpg)

# Langkah 17

Membuat view detail dengan cara membuat file baru di direktori app/view/artikel/detail.php

![8](https://user-images.githubusercontent.com/81844622/123046471-55e74e00-d426-11eb-994a-8a4ea67fd049.jpg)
 
 # Langkah 18 
 
 Membuat rooting untuk artikel detail
 
 ![9](https://user-images.githubusercontent.com/81844622/123046632-88914680-d426-11eb-9b0b-514eb7d7e0f6.jpg)

# Langkah 19

Membuat controller artikel baru dengan nama admin_index

![10](https://user-images.githubusercontent.com/81844622/123046928-e02fb200-d426-11eb-8f14-538fd9217a5a.jpg)

# Langkah 20

Membuat view untuk tampilan admin dengan nama admin_index.php

![11](https://user-images.githubusercontent.com/81844622/123047022-fa699000-d426-11eb-860a-05b8ea38639c.jpg)

# Langkah 21 

Menambahkan routing baru untuk menu admin

![12](https://user-images.githubusercontent.com/81844622/123047125-1f5e0300-d427-11eb-9ed0-28fa73a411aa.jpg)

# Langkah 22

Menambahkan method baru pada controller artikel dengan nama add()

![13](https://user-images.githubusercontent.com/81844622/123047284-546a5580-d427-11eb-8a93-d4cd45062482.jpg)

# Langkah 23

membuat view untuk form tambah dengan nama form_add.php

![14](https://user-images.githubusercontent.com/81844622/123047555-9eebd200-d427-11eb-9672-9359d1b9afd1.jpg)

# Langkah 24

Menambahkan method baru pada controller artikel dengan nama edit()

![15](https://user-images.githubusercontent.com/81844622/123049746-1a4e8300-d42a-11eb-8f1d-217a42688357.jpg)

# Langkah 25

Membuat view untuk membuat form tambah dengan nama form_edit.php

![16](https://user-images.githubusercontent.com/81844622/123049897-44a04080-d42a-11eb-9d9e-6989be72993a.jpg)

# Langkah 26

Menghapus data dengan menambahkan method baru pada controller artikel dengan nama detele()

![17](https://user-images.githubusercontent.com/81844622/123050047-73b6b200-d42a-11eb-96eb-1e28283667bc.jpg)




# Lanjutan / Pratikum 13




# Langkah 27 

Membuat database baru untuk user login

![1](https://user-images.githubusercontent.com/81844622/123641460-7d864e00-d84c-11eb-9b85-a33e62beda17.jpg)

# Langkah 28

Membuat user model baru pada direktori app/models dengan nama user model.php

![2](https://user-images.githubusercontent.com/81844622/123641631-a73f7500-d84c-11eb-80ca-df11a0c7bcb3.jpg)

# Langkah 29

Membuat controller baru dengan nama user.php pada direktori app/controller kemudian menambahkan method index() dan login ()

![3](https://user-images.githubusercontent.com/81844622/123641847-e53c9900-d84c-11eb-8612-b3f8216f93cc.jpg)

# Langkah 30

Membuat view login dengan cara membuat direktori baru dengan nama user pada direktori app/views kemudian buat file baru dengan nama login.php

![4](https://user-images.githubusercontent.com/81844622/123642335-5ed48700-d84d-11eb-87b9-f1a99f2ae4bc.jpg)

# Langkah 31

Membuat database seeder dengan Membuka CLI

![5](https://user-images.githubusercontent.com/81844622/123642457-83c8fa00-d84d-11eb-8130-9e60fa15cf62.jpg)

# Langkah 32

Selanjutnya buka file userseeder.php pada direktori app/database/seeds kemudian tambahkan kode ini

![6](https://user-images.githubusercontent.com/81844622/123642667-c2f74b00-d84d-11eb-9aff-4dcd7572e293.jpg)
