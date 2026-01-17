# Tag Input

Tag Input di gunakan untuk membuat elemen-elemen yang di gunakan untuk meminta informasi dari user.

| ATRIBUT | KETERANGAN
| :--- | :--- | 
| NAME | Mendefinisikan nama dari elemen input. Atribut ini harus di tuliskan kecuali untuk tipe submit dan clear
| SIZE | Menentukan lebar dari element input
| MAXLENGTH | Menentukan jumlah maksimum karakter yang dapat di masukan pada element input
| VALUE | Untuk kotak teks, menentukan teks yang tertulis, untuk check box atau radio, menentukan nilai item yang di pilih. untuk Submit dan Reset, menentukan teks yang tertulis pada tombol.
| CHECKED | Hanya di gunakan untuk check box atau radio, Menentukan pilihan default.
| TYPE| Menentukan tipe input yang di buat

Type input yang dapat di buat adalah:

- Text, digunakan untuk membuat kotak teks
- password, dugunakan untuk membuat kotak teks, tetapi semua karakter akan di tampilkan dengan tanda *.
- Check Box, digunakan untuk membuat suatu  daftar pilihan yang dapat di pilih lebih dari satu.
- Radio, di gunakan untuk membuat suatu daftar pilihan yang hanya dapat di pilih satu saja.
- Reset, di gunakan untuk membuat tombol yang fungsinya untuk menghapus semua isian form yang telah di berikan.
- Submit, di gunakan untuk membuat tombol yang fungsi nya untuk mengirimkan data form agar di olah.

1. Bukalah Notepad++, kemudian tuliskan kode berikut

```
<HTML>
	<HEAD>
		<TITLE>SELECT</TITLE>
	</HEAD>
	<BODY>
		Apa Golongan Darah Anda?
		<FORM>
			<SELECT NAME=�JumlahAnak�>
				<OPTION SELECTED VALUE=�A�>A
				<OPTION VALUE=�B�>B
				<OPTION VALUE=�AB�>AB
				<OPTION VALUE=�O�>O
			</SELECT>	
		</FORM>
	</BODY>
</HTML>

```

## Output

![image]()
