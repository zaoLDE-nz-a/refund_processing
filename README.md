# rak-minimarket

Repositori ini memuat berkas anotasi dan tautan unduhan untuk kumpulan foto rak toko.

Kumpulan fotonya sendiri diambil dari lapangan:
* sekitar empat puluh toko kelontong, direkam dengan empat kamera berbeda,
* mencakup sepuluh kategori produk,
* pengambilan gambar pada musim semi 2014 di Istanbul.

Pemakaian dibatasi untuk riset; penggunaan komersial tidak diizinkan.

## Tautan unduhan
Berkas gambar dibagi dua bagian, masing-masing berupa arsip tar. Total ukuran di disk kurang lebih tiga gigabyte. Keduanya juga tersedia di halaman rilis repositori ini.

## Susunan folder

### FotoRak
Berisi tiga ratus lima puluh empat bidikan rak.

Pola nama berkasnya:
```
			"C<c>_P<p>_N<n>_S<s>_<i>.JPG"
			dengan
				<c> := id kamera (1: ponsel lama, 2: ponsel lain, 3: kamera saku, 4: kamera lain)
				<p> := id denah rak
				<n> := urutan rak paling atas pada gambar menurut denah
				<s> := jumlah rak yang terlihat pada gambar
				<i> := nomor salinan
```
	
### FotoProduk
Berisi potret produk dari sepuluh kategori, masing-masing punya direktori sendiri.

Pola namanya:
```
		"B<b>_N<N>.JPG"
			dengan
				<b> := id merek
				<n> := nomor salinan
```

		
### FotoMerek

Versi potong dari folder produk — bagian yang tersisa hanya logonya saja.


### ProdukDariRak

Potongan produk yang diambil langsung dari foto rak. Isinya sepuluh kategori ditambah satu kategori negatif untuk barang yang tidak masuk kelas mana pun.

Pola namanya:
```
			"<nama foto rak>_<x>_<y>_<w>_<h>.png"
			dengan
			<nama foto rak>  := gambar sumber potongan diambil
			<x>              := koordinat x sudut kiri atas pada gambar sumber
			<y>              := koordinat y sudut kiri atas pada gambar sumber
			<w>              := lebar potongan pada gambar sumber
```