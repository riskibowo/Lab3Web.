# Lab3Web.

## Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
</header>
</body>
</html>
```
## Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
```
<section id="order-list">
<h2>Ordered List</h2>
<ol>
<li>Pemrograman Web</li>
<li>Sistem Informasi</li>
<li>Basis Data 2</li>
</ol>
</section>
```
![image](https://github.com/riskibowo/Lab3Web./assets/115862112/9f02daee-c06f-452a-b01d-01f3e21b27c4)
## Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
```
<section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>
```
![image](https://github.com/riskibowo/Lab3Web./assets/115862112/ee685579-4a6f-4702-b27f-2878d0c3c17b)
## Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
```
<section id="unorder-list">
<h2>Description List</h2>
<dl>
<dt>Fakultas Teknik</dt>
<dd>Teknik Industri</dd>
<dd>Teknik Informatika</dd>
<dd>Teknik Lingkungan</dd>
<dt>Fakultas Ekonomi dan Bisnis</dt>
<dd>Akuntansi</dd>
<dd>Manajemen</dd>
<dd>Bisnis Digital</dd>
</dl>
</section>
```
![image](https://github.com/riskibowo/Lab3Web./assets/115862112/22d51840-359a-484d-92a9-f5a74e07d312)
## Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
</header>
</body>
</html>
```
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
       <tr>
          <th>No.</th>
          <th>Fakultas</th>
          <th>Program Studi</th>
      </tr>
</thead>
<tbody>
    <tr>
        <td>1.</td>
        <td>Teknik</td>
        <td>Teknik Informatika</td>
    </tr>
<tr>
     <td>2.</td>
     <td>Teknik</td>
     <td>Teknik Industri</td>
</tr>
<tr>
      <td>3.</td>
        <td>Teknik</td>
        <td>Teknik Lingkungan</td>
      </tr>
</tbody>
</table>
```
![image](https://github.com/riskibowo/Lab3Web./assets/115862112/9020ffe8-e109-4b93-a03b-e4a423752106)
## Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan
cellspacing pada tag table.
```
<table border="1" cellpadding="4" cellspacing="0">
```

```
<table border="1" cellpadding="6" cellspacing="0">
  <thead>
       <tr>
           <th>No.</th>
           <th>Fakultas</th>
           <th>Program Studi</th>
       </tr>
</thead>
 <tbody>
        <tr>
             <td>1.</td>
              <td rowspan="3">Teknik</td>
             <td>Teknik Informatika</td>
        </tr>
<tr>
      <td>2.</td>
           <td>Teknik Industri</td>
    </tr>
<tr>
  <td>3.</td>
           <td>Teknik Lingkungan</td>
        </tr>
     </tbody>
</table>
```
![image](https://github.com/riskibowo/Lab3Web./assets/115862112/c499dbf4-8329-498b-a1a2-2701e8a5fa83)




# Membuat Form
Buat file baru dengan nama lab3_form.html seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Form</h1>
</header>
</body>
</html>
```
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
```
</head>
    
        <header>
            <h1>Form Mahasiswa</h1>
        </header>
    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Mahasiswa</legend>	
            <p>
                <label for="nama">Nama Lengkap</label>
                <input type="text" id="nama" name="nama" placeholder="">
            </p>
            <p>
                <label for="nomor">No. HP</label>
                <input type="text" id="nomor" name="nomor" placeholder="">
            </p>
            <p>
                <label for="email">E-mail</label>
                <input type="text" id="email" name="email" placeholder="">
            </p>
            <p>
                <label>Tanggal Lahir:</label>
                <input type="" name="" />
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L" /><label
    for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P" /><label
    for="jk_p">Perempuan</label>
            </p>
            <p>
            <label>Agama</label>
            <select name="Agama">
                <option value="islam"selected="selected">Islam</option>
                <option value="kristen">Kristen</option>
                <option value="katholik">Katholik</option>
                <option value="hindu">Hindu</option>
                <option value="budha">Budha</option>
            </select>
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" placeholder="Alamat anda" cols="25" rows="4"></textarea>
            </p>
            <p>
            <label>Pilih Jurusan</label>
            <select name="Pilih Jurusan" size="4">
                 <option value="TI"selected="selected">Teknik Informatika</option>
                 <option value="TK">Teknik Komputer</option>
                 <option value="TIN">Teknik Industri</option>
                 <option value="TS">Teknik Sipil</option>
                 <option value="TM">Teknik Mesin</option>
                 <option value="TL">Teknik Lingkungan</option>
            </select>
            </p>
            <p><input type="submit" name="tombol" value="Kirim" </p>
            <p><input type="reset" name="tombol2" value="Hapus" </p>
    </form>
    <style>
		form p > label {
			display: inline-block;
			width: 100px;
			height: 20px;
		}
		form input[type="text"], form textarea {
			border: 1px solid #197a43;
		}
		form input[type="submit"] {
			border: 1px solid #197a43;
			background-color: #197a43;
			color: #ffffff;
			font-weight: bold;
			padding: 5px 15px;
		}
		form input[type="reset"] {
			border: 1px solid #197a43;
			background-color: #197a43;
			color: #ffffff;
			font-weight: bold;
			padding: 5px 12px;
		}
	</style>
```
![image](https://github.com/riskibowo/Lab3Web./assets/115862112/3abac8b8-f62e-46cb-a2a4-c928acccbbd7)




