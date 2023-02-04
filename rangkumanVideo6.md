<h1>Menggunakan branch dan merge di git</h1>

<h3>Implementasi branch di git</h3>

<h5>Flow yang terjadi di dalam git saat kita melakukan commit : </h5>
<ul>
    <li>Saat kita melakukan commit, git akan melakukan:
        <ol>
            <li>Membuat hash sebagai penanda  untuk melacak commit yang kita lakukan. (hash berbeda2x untuk setiap commit)</li>
            <li>Meletakkan commit ini pada jalur utama atau master branch</li>
        </ol>
    </li>
    <li>Untuk mengetahui branch mana yang aktif (berada di branch mana kita sekarang?), git memiliki head. Head adalah pointer yang mengarah ke branch yang sedang aktif. Simpelnya, Head dan nama branch adalah 'penunjuk' ke hash yang menandai suatu commit. </li>
    <li>Jika kita melakukan commit lain di branch yang sama, maka pointer head + branch akan menunjuk ke arah hash yang baru.</li>
</ul>

<h5>Yang akan terjadi di dalam git saat kita membuat branch : </h5>
<ul>
    <li>Kita dapat membuat branch baru dengan command git branch < nama branch > </li>
    <li><strong>Perlu diingat,</strong>, jika kita membuat branch baru, maka <strong> branch tersebut akan mengarah ke commit yang sama</strong> dengan branch terakhir kita melakukan commit.
    <li>Atau mudahnya, saat kita membuat branch baru, branch tersebut akan memiliki pointer head yang sama dengan branch terakhir kita melakukan commit (pointer head sama => menunjuk commit yang sama)</li>
</ul>

<h5>Yang akan terjadi di dalam git saat kita pindah branch : </h5>
<ul>
    <li>Kita dapat pindah branch dengan command git chekout < nama branch > </li>
    <li>Jika kita pindah branch, tidak semudah visualisasi di github, di dalam git, <strong>bukan berarti langsung ada "jalur baru" yang terbentuk dari commit yang sekarang ditunjuk, ke jalur lain!</strong></li>
    <li>Yang sebenarnya terjadi adalah saat kita pindah branch adalah : </li>
    <ol>
        <li>branch baru dan branch master tetap menunjuk ke commit yang sama</li>
        <li>Tetapi,<strong>pointer head akan menunjuk ke branch yang berbeda,</strong> yaitu branch ke branch tempat kita pindah!</li>
    </ol>  
    <li>Jadi, intinya, jika kita pindah branch, yang bergerak cuman pointer headnya doang, sisanya diem.</li> 
</ul>

<h5>Yang akan terjadi dalam git saat kita melakukan commit di branch baru : </h5>
<ul>
    <li>Pointer head dan branch "bergerak" membuat jalur baru</li>
    <li>Pada tahap ini baru terbentuk cabang</li>
</ul>

<h3>Melakukan merge di git</h3>

<h5>Ada 2 jenis merge di git : </h5>
<ol>
    <li>Fast Forward</li>
    <li>Three-way merge</li>
</ol>

<h5>Fast forward merge</h5>
<ul>
    <li>Terjadi jika branch yang ingin kita merge ada di direct path</li>
</ul>

<h3>Beberapa istilah git terkait branch : </h3>
<ul>
    <li>$ git branch : menampilkan daftar branch yang ada</li>
    <li>$ git log -all --decorate --oneline --graph : Menampilkan historis mengenai branch</li>
    <li>$ alias nama_var = command yang mau disingkat : menyingkat command yang kepanjangan dengan meng aliaskan command sebagai suatu nama yang singkat</li>
</ul>


<h3>Berikut adalah link berisi screenshot bukti percobaan menggunakan git:</h3>
<p>https://drive.google.com/drive/folders/1IjZcOW2IdtqNSG77HAtKil9T4kcBxvB4?usp=share_link</p>


