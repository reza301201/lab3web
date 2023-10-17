# lab3web
# Lab3

Nama : Reza Kurniawan

NIM  : 312210436

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Instruksi Praktikum
> 1. Persiapkan text editor misalnya VSCode.
> 2. Buat folder baru dengan nama Lab3Web
> 3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
> 4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## Praktikum
**1. Membuat Ordered List & Undordered List**

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
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
    </section>
    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
        </ul>
        </section><section id="unorder-list">
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

</header>
</body>
</html>
```

<img width="960" alt="list" src="https://github.com/MohAzmii04/Lab3web/assets/115864496/c4094cfd-c645-417e-8e72-a88308f255b1">


**2. Membuat Table**

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

<img width="960" alt="tabel" src="https://github.com/MohAzmii04/Lab3web/assets/115864496/4b332a02-9fe6-4c0a-baab-6bfac794f908">



**3. Menggabungkan Sel Data**

```
<tr>
  <td>1.</td>
  <td rowspan="3">Teknik</td>
  <td>Teknik Informatika</td>
</tr>
```

<img width="960" alt="list2" src="https://github.com/MohAzmii04/Lab3web/assets/115864496/4e63accb-0882-4f6b-ab4e-649e87d602a2">

**4. Membuat Form**

```
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama" />
    </p>
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
      <label>Jenis Kelamin</label>
      <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l"
        >Laki-laki</label
      >
      <input id="jk_p" type="radio" name="kelamin" value="P" /><label
        qafor="jk_p"
        >Perempuan</label
      >
    </p>
    <p><input type="submit" value="Login" /></p>
  </fieldset>
</form>
```

<img width="960" alt="form" src="https://github.com/MohAzmii04/Lab3web/assets/115864496/4e6f0c06-b1f3-461b-a8dd-ff2569276cd8">

**5. Menambahkan Style**

```
<style>
        form p > label {
            display: inline-block;
            width: 100px;
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
    </style>
```



**6. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org**


<img width="960" alt="verif" src="https://github.com/MohAzmii04/Lab3web/assets/115864496/155a34a6-ac4c-4be3-b81b-58d972434f80">

## Pertanyaan dan Tugas
1. Buatlah form yang menampilkan **dropdown** menu dan **listbox** dengan *multiple selection.*

```<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas Form Dropdown and Listbox</title>
    <link rel="stylesheet" href="Style.css">
</head>

<body>
    <nav>
        <a href="Lab3_list.html">List HTML</a>
        <a href="lab3_tabel.html">Tabel HTML</a>
        <a href="lab3_form.html">Form HTML</a>
        <a href="Lab3_tugas.html">Form Dropdown & Listbox</a>
    </nav>
    <header>
        <h1>Form Dropdown & Listbox</h1>
    </header>

    <form class="form_tugas">
        <label for="dropdown">Pilih salah satu buah:</label>
        <select name="dropdown" id="dropdown">
            <option value="apel">Apel</option>
            <option value="jeruk">Jeruk</option>
            <option value="durian">Durian</option>
            <option value="mangga">Mangga</option>
            <option value="semangak">Semangka</option>
        </select>

        <br><br>

        <label for="listbox">Pilih beberapa buah:</label>
        <select name="buah[]" multiple id="listbox">
            <option value="apel">Apel</option>
            <option value="jeruk">Jeruk</option>
            <option value="durian">Durian</option>
            <option value="mangga">Mangga</option>
            <option value="semangka">Semangka</option>
            <option value="kelapa">Kelapa</option>
            <option value="anggur">Anggur</option>
            <option value="melon">Melon</option>
            <option value="pepaya">Pepaya</option>
            <option value="nanas">Nanas</option>
        </select>

        <br>

        <input type="submit" value="Submit" id="input_tugas">
    </form>
</body>

</html>
```

```body {
    font-family: Tahoma;
  }
  
  h1 {
    margin-top: 50px;
    text-align: center;
    color: #352593;
  }
  
  .tabel {
    margin: 20px auto;
  }
  
  form p > label {
    display: inline-block;
    width: 100px;
  }
  
  form input[type="text"],
  form textarea {
    border: 1px solid #46140c;
  }
  
  form input[type="submit"] {
    border: 1px solid #020203;
    background-color: #1b2435;
    color: #ffffff;
    font-weight: bold;
    padding: 5px 15px;
    border-radius: 10px;
  }
  
  form input[type="submit"]:hover {
    background-color: #2098cb;
    cursor: pointer;
  }
  
  nav {
    background-color: #3fb8e0c5;
    padding: 10px;
    position: fixed;
    top: 0px;
    right: 0px;
    left: 0px;
    text-align: center;
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
    padding: 2px 4px;
    font-size: 13px;
  }
  
  nav a:hover {
    color: #487689;
  }
  
  nav a:active {
    color: #3dd274;
  }
  
  /* Style untuk form dropdown & listbox */
  .form_tugas {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #5851b7;
    background-color: #47419b;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  /* Style untuk label */
  .form_tugas label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
  }
  
  /* Style untuk select dropdown dan listbox */
  .form_tugas select {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #fffafd;
    border-radius: 3px;
  }
  
  /* Style untuk tombol Submit */
  .form_tugas #input_tugas {
    background-color: #6caaed;
    color: #060202;
    padding: 5px 15px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  
  .form_tugas #input_tugas:hover {
    background-color: #2eb042;
  }
  }
```

<img width="960" alt="tugas" src="https://github.com/MohAzmii04/Lab3web/assets/115864496/91619416-1e4d-48c3-b70c-40b3a8ca1e54">

## Finish, Terima Kasih
