<h1>Menggunakan Git</h1>

<h3>Beberapa perintah git umum (git command) : </h3>
<ul>
    <li>$ git init : inisialisasi repo git di komputer kita</li>
    <li>$ git add &ltfile(s)&gt : menambahkan file ke staging area </li>
    <li>$ git status : untuk mengetahui status repo kita, apakah ada file baru, apakah ada yang dirubah, dll</li>
    <li>$ git commit : untuk commit </li>
    <li>$ git config : untuk konfigurasi ke dalam git</li>
    <li>$ git branch : untuk membuat branch</li>
    <li>$ git help : untuk mendapat penjelasan mengenai command git yang tidak dimengerti</li>
</ul>

<h3>Tiga area pada repo git </h3> 
<ol>
    <li>Working tree : Folder tempat bekerja, folder tempat menyimpan file seperti biasa</li>
    <li>Staging area : Memberitahu git bahwa perubahasn sudah dilakukan</li>
    <li>History : perubahan yang sudah di commit akan masuk ke history</li>
</ol>
<p><strong>notes : </strong>Staging area dan history akan tersimpan ke dalam folder .git (.git folder yang dibuat jika kita sudah menginisiasi folder kita sebagai repo)</p>
<ul>Ilustrasi mengenai tiga are pada repo git : 
    <li>Jika kita sudah menginisialisasi suatu folder dikomputer kita sebagai repo git, maka git akan memantau apakah ada perubahan/tidak</li>
    <li>Jika ada perubahan, perubahan dapat disimpan di staging area menggunakan command git add</li>
    <li>Jika di staging area sudah oke maka baru dilakukan commit dengan command git commit sehingga perubahan masuk ke history</li>
</ul>

<h3>Flow kerja menggunakan git</h3>
<ol>
    <li>Menginisiasi folder lokal menjadi repo git (menggunakan git init)</li>
    <li>Mengedit file di lokal (sepert biasa)</li>
    <li>Menyimpan perubahan file ke staging area (menggunakan git add)</li>
    <li>Melakukan commit pada file dengan git commit (notes: sebelum commit, jika belum, harus konfigurasi identitas dulu pake git config)</li>
    <li>Cek status lokasi branch sekarang, jumlah commit, serta tracking file yang tersimpan di staging area menggunakan command git status<li>
    <li>Untuk mengecek histori git menggunakan commit git log</li>
</ol>

<h3>Command baru yang dipelajari :</h3>
<ul>
    <li>$ pwd : mengetahui direktori tempat kita berada sekarang</li>
    <li>$ ls : mengetahui ada file/folder apa saja dalam suatu folder</li>
</ul>


<h3>Berikut adalah link berisi screenshot bukti percobaan menggunakan git:</h3>
<p>https://drive.google.com/drive/folders/1yy3flX6G7kKzxnELZin0XaNFwGNs-yR5?usp=share_link</p>