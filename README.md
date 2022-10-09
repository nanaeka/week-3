# Writing week-3

# JS Intermediate-Array




 Array
 
 
 
 Array adalah tipe data list order yang dapat menyimpan tipe data apapun di dalamnya.Array dapat menyimpan tipe data String, Number, Boolean, dan lainnya.
 
 
 
 
 Contoh Array

      // Product Team

      // 1. Product Manager

      // 2. Front End Developer

      // 3. Back End Developer

      let productTeam = ['Product Manager', 'Front End Developer', 'Back End Developer']: console.log(productTeam);
      
      
      
# Membuat Array

•	Array didefinisikan menggunakan square brackets
      
 
# Array Properties

      // Square Bracket
      []




•  Mengakses/Memanggil Array



Array pada javascript dihitung dari index data ke-0.Data pertama adalah index ke-0.


# Update Array

 Seperti tipe data dan variabel pada umumnya, kita dapat mengupdate data pada Array


# Const in Array

•  Jika menggunakan let, kita dapat mengubah array  dengan array baru dan konten nilai yang ada di dalam array dengan nilai lain

•  Const tidak bisa melakukan update data. Namun pada Array kita dapat melakukan update konten nilai di dalam array (mutable).

•  Yang tidak bisa adalah mengubah array dengan array yang baru jika menggunakan const

# Array Properties

Array memiliki 5 properti yang sering digunakan yaitu constructor, length, index, input, dan prototype.


.length

 length akan mengembalikan nilai dari jumlah panjang data suatu array.


# Array Method
 Array memiliki method atau biasa disebut built-in methods.Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan.
Kita tidak perlu membuat function lagi jika method yang kita butuhkan sudah tersedia.


# Contoh Array Built-in 

.push()


 .push() adalah method untuk menambahkan item  array pada urutan yang paling akhir.


.pop()


 .pop() adalah method yang menghapus item array index terakhir.
 
 
 .shift()
 
 
 .shift() adalah method untuk menghapus item Array pada index pertama
 
 
 .unshift()
 
 
 .unshift() adalah method untuk menambahkan item Array pada index pertama


.sort()


.sort() adalah method untuk mengurutkan secara Ascending atau Descending Alphanumeric



# Looping pada Array

.forEach()


.forEach() adalah method untuk melakukan looping pada setiap elemen array.



.map()


.map() melakukan perulangan/looping dengan membuat array baru.



   Kita bisa lihat bahwa .map() dan forEach() sama-sama melakukan looping dan mengembalikan nilai baru dari operasi yang dilakukan 

   Perbedaannya adalah .forEach tidak dapat membuat Array baru dari hasil operasi yang ada dalam looping Lalu dari segi performance juga sangat jauh.
   
   Gunakan .map() jika akan melakukan operasi pada array seperti yang dapat mengubah nilai array sebelumnya.


# JavaScript - Multidimensional Array

Multidimensional Array bisa dianalogikan dengan array of array.Ada array didalam array.

     let inventory  =  [
         ['Kaos Polos', 10], 
         ['Jaket Hoodie', 12], 
         ['Topi', 24], 
         ['Celana Jeans', 8],
     ];
     console.log(inventory);



Akses index multidimensional array


 Operation using map in multidimensional array

 LOOPING FOR MULTIDIMENSIONAL ARRAY
 
 
 
 # JavaScript Object
 
 object adalah sebuah tipe data pada variabel yang menyimpan properti dan fungsi (method)

 Properti adalah data lengkap dari sebuah object.

 Method adalah action dari sebuah object. Apa saja yang dapat dilakukan dari suatu object.
 
 

Membuat sebuah object
   let person = {}; // person is an empty object
 
 
 
 
 Mengakses Object dan Property Object




































