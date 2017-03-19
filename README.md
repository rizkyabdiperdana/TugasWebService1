# TugasWebService1 (Analisa)

<?xml version="1.0"?>                 == memberi arti bahwa dokumen ini dibuat dengan aturan XML versi 1.0. 

<!DOCTYPE books [                     == adalah suatu deklerasi yang digunakan untuk mengidentifikasi jenis dokumen HTML yang digunakan                                            sehingga browser dapat menentukan bagaimana memperlakukan kode tersebut dan books merupakan                                                elemen rootnya.
  <!ELEMENT buku      (#PCDATA)>      == adalah suatu relasi yang dihubungkan dan buku merupakan deklarasinya, sedangkan (#PCDATA)                                                  menunjukan tipe isi dari elemen yaitu data karakter. 
  <!ELEMENT judul     (#PCDATA)>      == adalah suatu relasi yang dihubungkan dan judul merupakan deklarasinya, sedangkan (#PCDATA)                                                menunjukan tipe isi dari elemen yaitu data karakter.
  <!ELEMENT pengarang (#PCDATA)>      == adalah suatu relasi yang dihubungkan dan pengarang merupakan deklarasinya, sedangkan (#PCDATA)                                            menunjukan tipe isi dari elemen yaitu data karakter.
  <!ELEMENT penerbit  (#PCDATA)>      == adalah suatu relasi yang dihubungkan dan penerbit merupakan deklarasinya, sedangkan (#PCDATA)                                              menunjukan tipe isi dari elemen yaitu data karakter.
  <!ELEMENT harga     (#PCDATA)>      == adalah suatu relasi yang dihubungkan dan harga merupakan deklarasinya, sedangkan (#PCDATA)                                                menunjukan tipe isi dari elemen yaitu data karakter.
]>

<books>                                   == adalah digunakan sebagai judul atau ‘header’, dan ini merupakan root elemen dari dokumen. 
<buku isbn="978-1594489501"></buku>       == adalah anak dari elemen root yang menyatakan gambaran dari root induknya. 
<judul>Cara Menaklukkan Algoritma</judul> == adalah anak dari elemen root yang menyatakan gambaran dari root induknya. 
<pengarang>Rizky Abdi Perdana</pengarang> == adalah anak dari elemen root yang menyatakan gambaran dari root induknya. 
<penerbit>Bintang Media</penerbit>        == adalah anak dari elemen root yang menyatakan gambaran dari root induknya. 
<harga>90000</harga>                      == adalah anak dari elemen root yang menyatakan gambaran dari root induknya. 

</books>                                  == adalah penutup dari judul yang menggambarkan isi dari dokumen.
