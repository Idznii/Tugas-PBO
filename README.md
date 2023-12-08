# Tugas-PBO
Nama : Idznii Sholekhah
        
NPM  : G1F022001

KELAS : A SISTEM INFORMASI
   
   MATKUL : PBO

Tugas 
1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
   Input kode program 
   ![Screenshot 2023-12-08 182249](https://github.com/Idznii/Tugas-PBO/assets/150024894/783dba35-83d3-4519-b2e5-f70c28101eeb)

   penjelasan :

    for i in range(1, 101):
   Ini adalah loop for yang mengatur variabel i untuk mengambil nilai dari 1 hingga 100.
   if i % 10 == 0 or (i - 9) % 10 == 0 or (i - 8) % 10 == 0:
   Ini adalah kondisi if yang memiliki tiga bagian yang dihubungkan dengan operator logika OR (or).
   i % 10 == 0:
   Ini memeriksa apakah i adalah kelipatan 10.
   (i - 9) % 10 == 0:
   Ini memeriksa apakah i - 9 adalah kelipatan 10 (sebagai contoh, 11 - 9 = 2, yang merupakan kelipatan 10).
   (i - 8) % 10 == 0:
   Ini memeriksa apakah i - 8 adalah kelipatan 10 (sebagai contoh, 12 - 8 = 4, yang merupakan kelipatan 10).
   print("Idznii"):
   Jika salah satu dari kondisi di atas terpenuhi, maka program mencetak string "Idznii".
   else: print(i):
   Jika tidak ada kondisi di atas yang terpenuhi, program mencetak nilai i.
Dengan demikian, output dari program ini adalah mencetak angka dari 1 hingga 100, dan setiap kali nilai tersebut adalah kelipatan 10 atau dua digit sebelumnya, program akan mencetak "Idznii" sebagai gantinya.

    output :

    ![Screenshot 2023-12-08 185517](https://github.com/Idznii/Tugas-PBO/assets/150024894/606628f4-1357-473c-a568-461123972e45)
   
    ![Screenshot 2023-12-08 185851](https://github.com/Idznii/Tugas-PBO/assets/150024894/473d8b34-c67d-4477-8e05-2006a190982c)

    ![Screenshot 2023-12-08 192841](https://github.com/Idznii/Tugas-PBO/assets/150024894/26237b6a-3fc2-42bb-a04f-a49d7e9b5b1e)

    ![Screenshot 2023-12-08 185911](https://github.com/Idznii/Tugas-PBO/assets/150024894/3c32d1f8-8508-4f33-8dac-91d51ae63b37)
   
2. Buatlah program bebas, dengan menerapkan if else pada:
  a. For Loops
  b. While Loops

  Jawab:

  a. For Loops

  input kode program 
     
   ![Screenshot 2023-12-08 193442](https://github.com/Idznii/Tugas-PBO/assets/150024894/55191872-29a2-45b7-8f3e-6495ec4a2376)

   penjelasan :
    for i in range(1, 11):
    Ini adalah loop for yang mengatur variabel i untuk mengambil nilai dari 1 hingga 10 .
    if i % 2 == 0:
    Ini adalah kondisi if yang memeriksa apakah i habis dibagi dua (dengan modulus % menghasilkan sisa bagi 0), yang menunjukkan bahwa i adalah angka genap.
    print(f"{i} adalah angka genap."): 
    Jika kondisi di atas terpenuhi, program mencetak string yang menyatakan bahwa nilai i adalah angka genap.
    else:
    Ini adalah bagian else yang akan dijalankan jika kondisi di atas tidak terpenuhi, yang berarti i adalah angka ganjil.
print(f"{i} adalah angka ganjil."): Jika kondisi di atas tidak terpenuhi, program mencetak string yang menyatakan bahwa nilai i adalah angka ganjil.
Jadi, output dari program ini akan mencetak apakah setiap nilai dalam rentang 1 hingga 10 adalah angka genap atau ganjil.
    Output program 
    
   ![Screenshot 2023-12-08 193719](https://github.com/Idznii/Tugas-PBO/assets/150024894/bab19f09-db35-417c-9f25-583b9fc899d2)

 b. While Loops 

 input kode program 
 
   ![Screenshot 2023-12-08 193847](https://github.com/Idznii/Tugas-PBO/assets/150024894/5cdd7521-6760-4323-a97b-fd944446e057)
  
  penjelasan :
counter = 1:
Ini adalah inisialisasi variabel counter dengan nilai awal 1. Variabel ini akan digunakan untuk melacak nilai yang sedang diuji dalam loop.
while counter <= 10:
Ini adalah loop while yang akan terus berjalan selama nilai counter kurang dari atau sama dengan 10.
if counter % 2 == 0: 
Ini adalah kondisi if yang memeriksa apakah counter habis dibagi dua (dengan modulus % menghasilkan sisa bagi 0), yang menunjukkan bahwa counter adalah angka genap.
print(f"{counter} adalah angka genap."):
Jika kondisi di atas terpenuhi, program mencetak atau menampilkan nilai counter adalah angka genap.
else:
Ini adalah bagian else yang akan dijalankan jika kondisi di atas tidak terpenuhi, yang berarti counter adalah angka ganjil.

print(f"{counter} adalah angka ganjil."): Jika kondisi di atas tidak terpenuhi, program mencetak string yang menyatakan bahwa nilai counter adalah angka ganjil.
counter += 1: Pada setiap  loop, nilai counter akan ditambahkan 1. 
output 
![Screenshot 2023-12-08 194216](https://github.com/Idznii/Tugas-PBO/assets/150024894/60da7992-a1e2-40e8-abf8-edd8a4f9f9aa)

3.  Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for
     input kode program
    ![Screenshot 2023-12-08 194312](https://github.com/Idznii/Tugas-PBO/assets/150024894/e9a510bf-5bdb-4f73-8327-dff6f7046e9b)

    penjelasan :
    nilai_array = [10, 20, 30, 40, 50]:
    Ini adalah deklarasi variabel nilai_array yang berisi sebuah array (atau dalam Python disebut sebagai list) dengan nilai [10, 20, 30, 40, 50].
    for nilai in nilai_array:
    Ini adalah loop for yang digunakan untuk melakukan iterasi melalui setiap elemen dalam array nilai_array. Setiap elemen diwakili oleh variabel.
    print(nilai):
    Di dalam loop, setiap nilai dari nilai_array dicetak menggunakan fungsi print. Dengan demikian, setiap elemen dalam array akan dicetak satu per satu.
    Jadi, output dari program ini akan mencetak semua nilai yang ada dalam array nilai_array secara berurutan:
    output :
    
    ![Screenshot 2023-12-08 194519](https://github.com/Idznii/Tugas-PBO/assets/150024894/1afa31f7-b013-4bb8-8ef3-ec4f0fd4327d)

































































































