<h1> Video 1 : Pengenalan Git & Github </h1>

<h3> Version control system </h3> 

<ul> 
    <li> Disebut juga revision control system / souce code management </li>
    <li> Version control system adalah sistem yang mengelola perubahan dari sebuah dokumen, program komputer, website dan kumpulan informasi lain. </li>
    <li> Kegunaan Version control system: 
        <ol>
             <li> Melacak perubahan serta menyimpan histori versi dari dokumen atau kode.</li> 
             <li>Memudahkan kolaborasi.</li>
        </ol> 
    </li>
    <li>Beberapa hal yang dapat dilakukan oleh Version control system:
        <ol> 
        <li>Menyimpan rekaman/snapshot perubahan pada souce code.</li>
        <li>Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi.</li>
        <li>Memungkinkan kita untuk kembali ke keadaan sebelum perubahan.</li>
        </ol> 
    </li>
</ul>

<h3>Git</h3>

<ul>
    <li>Git adalah software untuk mengelola perubahan file di dalam folder (disebut repository/repo)</li>
    <li>Git akan menyimpan histori perubahan file menggunakan serangkaian commit</li>
    <li> Commit akan menyimpan informasi:
        <ol>
            <li>string untuk mencirikan suatu commit</li>
            <li>Author, yaitu siapa yang melakukan commit</li>
            <li>Commit message, umumnya berisi informasi mengenai apa yang diubah</li>
        </ol>
    </li>
    <li> <strong>Branch</strong> adalah fitur git untuk membuat "cabang baru" dari commit utama atau canag utama kita.  Tujuan dibuatnya branch adalah untuk membuat perubahan pada kode tetapi tidak ingin mengganggu kode di cabang utama.</li>
    <li>Jika pada branch perubahan sudah dirasa bagus dan ingin digabungkan dengan kode di main branch maka dilakukan <strong>merge</strong></li>
</ul>


<h3>GitHub</h3>

<ul>
    <li>Github adalah layanan cloud untuk menyimpan & mengelola project/ repo git</li>
    <li>Git dapat digunakan di dalam github secara online</li>
    <li>Jika kita memiliki git di lokal dan juga memiliki akun github, kita dapat mengupload repo dari lokal ke github maupun sebaliknya. Proses upload ke github disebut <strong>Push</strong> dan proses sebaliknya disebut <strong>Pull</strong>. Yang di push dan pull ini adalah commit.</li>
    <li>Untuk melakukan push dan pull harus dilakukan beberapa hal dulu yaitu:
        <ol>
            <li>Menjadikan github sebagai remote, yaitu sumber dari repo. Maksudnya dalah kita membuat repo di github.</li>
            <li>Utuk menyimpannya di lokal, repo yang dibuat di github tadi akan di clone ke folder yang kita inginkan. Dengan begini, repo sudah ada di github dan di lokal kita.</li>
        </ol>
    </li>
     <li>Flow kerja yang diharapkan dengan github : 
        <ol>
            <li>Membuat repo di github</li>
            <li>Clone repo dari github ke lokal, di folder yang kita inginkan</li>
            <li>Commit setiap perubahan pada kode</li>
            <li>Jika sudah selesai lakukan push</li> 
        </ol>
     </li>
</ul>

<h3>Istilah git yang sudah dipelajari: </h3>
<ul>
    <li>repo : folder project</li>
    <li>commit : rekaman/ snapshot dari repo</li>
    <li>hash : penanda unik pada sebuah commit</li>
    <li>checkout : berpindah ke sebuah commit</li>
    <li>branch : cabang bebas dari sebuah commit</li>
    <li>merge : menggabungkan branch</li>
    <li>remote: sumber yang memiliki repo</li>
    <li>clone : mengambil repo dari remote</li>
    <li>push : mengirimkan commit ke repo</li>
    <li>pull : mengambil commit dari repo</li>
</ul>
