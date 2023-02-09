# Pertemuan 6
NAMA   : Maftukhin Jafar Nadwi<br>
NIM    : 312210704 <br>
KELAS  : TI.22.C9 <br>

# Latihan Program list
# Buat sebuah list sebanyak 5 elemen dengan nilai bebas
<p> Ketik 5 elemen angka bebas seperti berikut<p>
<p> misal angkanya 31,33,35,37,39 <p>
<p> dalam akses list ini, urutannya tidak dimulai dari 1, tetapi dari 0. misal 31 adalah urutan 0 ([0]), 33 urutan ke 1 ([1]) dan begitu seterusnya. <p>

![Untitled2](https://user-images.githubusercontent.com/124107247/217919693-a36c1e65-560a-4b82-8a02-cc6ce68cd446.png)


# Akses list
## Menampilkan elemen ke 3
<p> program ini untuk menampilkan elemen ketiga. bentuk penulisannya (a[2]). <p> 

## Mengambil nilai elemen ke 2 sampai elemen ke 4
<p> program ini untuk menampilkan elemen ke 2 sampai ke empat. maka bentuk penulisannya (a[1:4])<p>

## Mengambil nilai terakhir
<p> program ini untuk mengambil nilai terakhir dengan bentuk penulisan (a[-1]), tanda minus berati urutan nya dimulai dari belakang <p>

<p> script nya seperti berikut <p>

![Untitled3](https://user-images.githubusercontent.com/124107247/217919888-50d172bc-0d9b-47f6-a111-24a95be4c60f.png)


<p>maka hasil nya bisa dilihat bahwa 35 adalah elemen ketiga<p>
<p> 33, 35,37 adalah elemen ke 2 ke 4<p>
<p> 39 adalah elemen terakhir <p>

# Mengubah elemen list
## Mengubah elemen ke 4 dengan nilai lainnya
<p> program list ini adalah mengganti angka pada elemen ke 4 menjadi angka lainnya. misal nya diubah menjadi angka 40. Maka bentuk penulisannya (a[3]=40)<p>

## Mengubah elemen ke 4 sampai dengan elemen terakhir
<p> elemen ke 4 sampai terakhir adalah angka 37 dan 39, maka diganti dengan angka bebas, misal diganti menjadi angka 42 dan 45. maka bentuk penulisannya (a[3:]=[42,45])<p>

<p> script nya seperti berikut <p>

![Untitled4](https://user-images.githubusercontent.com/124107247/217921027-7aa64860-c02f-4616-98b8-54126cf59d02.png)

<p> maka hasil run seperti berikut <p>

![Untitled5](https://user-images.githubusercontent.com/124107247/217921083-537097f6-4829-4681-a6cc-809e20b9109d.png)

<p> pada elemen keempat sudah diganti menjadi 40 <p>
<p> pada elemen keempat sampai terakhir sudah terganti menjadi 42 dan 45 <p>

# Menambah elemen list
## Mengambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
<p> Mengambil 2 elemen pertama dan dijadikan list baru/kedua. Bentuk penulisannya (b=a[0:2]<p>

## Menambah list B dengan nilai string
<p> yaitu menambahkan kata/kalimat pada list yang kedua. misal kata python. bentuk penulisannya b.append('python')

## Menambah list B dengan 3 nilai
<p> Menambahkan 3 angka terakhir. bentuk penulisannya b.extend([50,55,60])

## Menggabungkan list B dengan list A
<p> bentuk penulisannya b.extend(a)

##
<p> append adalah menambahkan elemen ke list<p>
<p> extend adalah menyatukan list pertama dengan list lain(atau yang lain yang bisa diubah, belum tentu daftar)<p>

<p> bentuk script nya seperti berikut <p>

![Untitled6](https://user-images.githubusercontent.com/124107247/217921144-9998d82c-8efe-4638-93de-dd9f4ef7159d.png)


<p> hasil run nya seperti berikut <p>

![Untitled7](https://user-images.githubusercontent.com/124107247/217921186-61e97056-1537-423f-8517-8e9e652d71ab.png)


# Praktikum
## Membuat progran sederhana untuk menambahkan data kedalam list dengan rincian sebagai berikut.
<p>Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)<p>
<p>Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya<p>
<p>Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)<p>

<p> bentuk scriptnya seperti berikut <p>

![Untitled9](https://user-images.githubusercontent.com/124107247/217921729-b96be522-5fa3-4b51-b712-65ed22e6ea17.png)

<p> kemudian run, masukan nama, nim, nilai tugas, nilai UTS, nilai UAS. kemduain ketik y/t untuk menambahkan data atau tidak. jika mengetik y maka akan mengulang untuk menambahkan data data, tapi jika ketik t maka program langsung menampilkan hasil data serta menghitung nilai akhir. misal seperti berikut data datanya <p>

![Untitled8](https://user-images.githubusercontent.com/124107247/217921777-814ae369-9198-4d3a-acc7-a441a390f50a.png)
<p>makasi<p>
