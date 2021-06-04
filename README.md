<p align="justify"><b>Web Server</b> </br>
Seperti yang sudah disebutkan sebelumnya, informasi pada sebuah website disimpan pada server. Lantas apa itu server? Banyak yang mengira bahwa server adalah sebuah komputer dengan performa tinggi dan berukuran besar. Hal tersebut tidak salah karena biasanya komputer yang dijadikan server memang harus memiliki performa yang tinggi. Selain untuk menyimpan data (HTML, CSS, dan JS disimpan di sini), server juga harus melakukan pekerjaan yang cukup berat, yaitu menanggapi, menyediakan, dan mengelola data yang diminta oleh client. Tidak hanya satu client, namun bisa ratusan bahkan ribuan.</br></br>
Tetapi pengertian server sebenarnya lebih merujuk pada sebuah software yang dapat menghubungkan sebuah komputer dengan komputer lain. Jadi penekanan sebuah server bukan pada sebuah komputernya, melainkan pada rule atau fungsi dari sebuah komputer tersebut.</br></br>
<b>HTTP Server</b></br>
HTTP Server merupakan sebuah software yang dapat menerima transaksi dari HyperText Transfer Protocol dalam suatu website atau biasa disebut dengan “HTTP Server”. Banyak software yang dapat melakukan tugas tersebut. Apache adalah salah satunya yang cukup friendly, gratis, dan tersedia untuk seluruh komputer dengan basis UNIX (termasuk MacOS) dan juga Windows.</br></br>
<b>DNS Server</b></br>
Setiap perangkat baik komputer, smartphone, modem, maupun router yang terkoneksi internet akan memiliki IP Address. Contohnya, komputer yang menjadi host dari dicoding.com memiliki IP 104.28.20.105, Jika kita menggunakan IP tersebut untuk mengakses sebuah website, tentu akan repot. Mengingat kumpulan angka memang dapat seorang manusia lakukan, tapi bagaimana jika harus mengingat 10 IP? Untuk mengatasinya, dibuatlah Domain Name System (DNS) yang dapat mengubah/mengarahkan website melalui sebuah nama domain (“dicoding.com”). </br></br>
<b>Client</b></br>
Jika ada penyedia (server) tentu ada pengguna bukan? Perangkat yang meminta (request) suatu layanan tertentu ke suatu server disebut dengan client. Browser merupakan salah satu client yang memanfaatkan HTTP Server dalam transaksi datanya. Jelas, tujuannya adalah untuk mengolah, menampilkan, dan melakukan interaksi dengan dokumen yang disediakan oleh web server. Layaknya sebuah pelukis, browser mampu menyajikan informasi dalam bentuk visual yang indah bersumber dari data mentah yang diperoleh dari server.</br></br>
<b>Server-side dan Client-side</b></br>
Dalam pengembangan web, terdapat istilah “Client-Side” atau “Server-side”. Hal ini merujuk pada sebuah proses yang dilakukan pada sisi client atau di sisi server. Untuk client side, semua proses terjadi di sisi pengguna, client meminta data ke server di mana data yang dikirimkan nanti diolah di sisi client. Biasanya data yang diolah dalam bentuk HTML, CSS, dan JavaScript. </br></br>
Sedangkan untuk server side, semua proses yang terjadi dilakukan di sisi server. Server side bertanggung jawab untuk merespon data yang diminta oleh client side. Biasanya server side merupakan tempat di mana terjadinya interaksi pada database, sehingga sisi client tidak mengetahui prosesnya dan memang tidak boleh tahu. Client hanya diberikan sebuah data hasil olahan dari sisi server.</br></br>
<b>Anatomi Website</b></br>
Kita terbiasa dengan tampilan website yang nampak pada browser, tetapi apakah kalian tahu bagaimana website dapat tampil demikian? Terdapat 3 (tiga) fondasi penting dalam membuat website. Pertama adalah HTML, salah satu markup language yang digunakan untuk membuat struktur dan menampilkan konten pada World Wide Web (Website). CSS dan JavaScript merupakan fondasi lainnya yang digunakan untuk mempercantik dan menjadikan website lebih dinamis dan interaktif. </br></br>
Sama seperti halnya tubuh manusia yang disusun dari kerangka tulang, HTML pada website berperan sebagai kerangka dasar yang digunakan dalam menampilkan visual pada website. Tapi jika hanya sebatas kerangka, seorang manusia akan terlihat menyeramkan dan aneh bukan? Maka dari itu untuk mempercantik tampilannya kita membutuhkan sebuah kulit. Di sinilah peran CSS. Setelah memiliki kulit dan nampak cantik, selanjutnya kita membutuhkan sebuah otak dan otot agar seorang manusia dapat dinamis dan berinteraksi. Dalam website JavaScript-lah yang berperan dalam membuat website yang dinamis dan interaktif.</br></br>
<b>Bagaimana Website bekerja?</b></br>
Ketika kita mengunjungi dicoding.com, tentu kita membutuhkan sebuah koneksi internet, karena website memerlukan sebuah web server hosting yang dapat diakses di mana saja. Ketika kita menuliskan “dicoding.com” dan menekan enter pada browser, hal yang pertama dilakukan browser adalah menghubungi Domain Name System (DNS) server untuk mengarahkan ke alamat server. Kemudian browser mengirimkan sebuah permintaan (request) agar server mengirimkan salinan dari informasi yang nantinya ditampilkan pada client (browser). Jika request tersebut berhasil, maka server menanggapi (response) permintaan tersebut dan mulai mengirimkan salinan yang dibutuhkan secara berangsur. Browser menggabungkan bagian-bagian informasi yang diperoleh untuk kemudian tampil di jendela browser.</br></br>
Untuk menampilkan informasi pada jendela, browser menggunakan HTML dan CSS yang dikirimkan dari server. Dengan begitu, informasi dalam bentuk HTML dan CSS-lah yang dikirimkan server untuk client (browser). Beberapa halaman website juga membutuhkan informasi ekstra seperti berkas gambar, suara atau video, tetapi berkas tersebut sebenarnya hanya ditanamkan (embed) pada HTML. Dan beberapa halaman website sebenarnya juga membutuhkan JavaScript untuk me-render HTML atau CSS agar dapat menampilkan informasi secara dinamis.</br></br>
<b>Requirement Tools</b></br>
Terdapat tools yang harus kita siapkan sebelumnya untuk mengikuti kelas ini, yaitu Text Editors dan Browser.</br></br>
<b>Text Editors</b></br>
Dalam mengembangkan sebuah website, tentu kita akan banyak menuliskan sebuah kode HTML, CSS, maupun JavaScript. Maka dari itu, langkah awal yang harus kita siapkan adalah sebuah text editor. Beberapa sistem operasi sebenarnya sudah menyediakan text editor usungannya sendiri. Contohnya Windows memiliki Notepad, Linux memiliki Text Editors dan Macintosh memiliki TextEdit. Ketiga aplikasi tersebut bisa kita gunakan untuk belajar membuat sebuah website, meskipun masih banyak alternatif text editor lainnya selama masih dapat menyimpan sebuah plain text dengan format .html.</br></br>
Perlu diperhatikan bahwa kode yang kita tuliskan merupakan sebuah plain text. Pastikan kita menggunakan text editor yang tepat. Jangan pernah menggunakan Microsoft Word untuk menuliskan sebuah kode, karena aplikasi tersebut menampilkan teks yang telah diformat atau biasa disebut dengan rich text. Selain text editors usungan sistem operasi yang kita gunakan, berikut tiga text editor lainnya yang bisa kita gunakan untuk membuat sebuah website.</br></br>
<b>Visual Studio Code</b></br>
Visual Studio Editor merupakan sebuah text editor yang dikembangkan oleh Microsoft. Dalam text editor ini terdapat fitur debugging, Git control, syntax highlighting, code completion, snippets, dan code refactoring. Visual Studio Code tersedia untuk sistem operasi Windows, Mac maupun Linux, dan tentunya text editor ini bisa kita gunakan secara gratis. Untuk mengunduhnya silakan kunjungi website berikut: https://code.visualstudio.com/</br></br>
<b>Atom Editor</b></br>
Atom merupakan text editor gratis dan juga open source untuk Windows, Linux, dan MacOS. Sama seperti Visual Studio Editor, kedua text editor ini merupakan editor yang populer digunakan oleh web developer. Untuk mengunduhnya, silakan kunjungi website berikut: https://atom.io/</br></br>
<b>Emacs</b></br>
Editor ini mungkin tidak secanggih opsi-opsi sebelumnya dalam menuliskan kode HTML, CSS, dan JavaScript. Namun, jika kalian tertarik belajar melalui proses tanpa fitur yang mempermudah kita dalam menuliskan sebuah kode, maka text editor ini cocok untuk dicoba. Emacs memiliki fitur yang tidak disangka-sangka untuk sebuah text editor, seperti news reader, kalkulator, dan fitur untuk enkripsi/dekripsi file. Emacs tersedia untuk Windows, Macs, maupun Linux secara gratis. Untuk mencobanya, kalian bisa mengunjungi halaman website berikut: https://www.gnu.org/software/emacs/</br></br>
<b>Browser</b></br>
Seperti yang sudah kita ketahui, untuk mengakses website membutuhkan sebuah browser. Tentu untuk mengembangkan website juga diperlukan sebuah browser untuk melihat seperti apa tampak website yang sedang kita kembangkan. Kita bisa menggunakan browser apa pun untuk mengunjungi sebuah website, tetapi hasil yang ditampilkan mungkin dapat berbeda pada di setiap browser. Walaupun tampilan pada setiap browser berbeda, pada kelas ini kalian tidak perlu mencobanya satu per satu untuk melihatnya pada masing - masing browser. Kami sarankan Anda untuk menggunakan browser yang populer yaitu Google Chrome atau Mozilla Firefox. </br></br>
Seperti text editor, sebenarnya sistem operasi sudah mempunyai browser usungannya masing-masing, misal Microsoft Edge di Windows dan Safari di MacOS. Akan tetapi kedua browser tersebut tidak memiliki fitur developer tools atau Dev Tools seperti yang dimiliki oleh Google Chrome dan Mozilla Firefox.</br></br>
Developer Tools atau Dev Tools merupakan alat yang dapat digunakan untuk melakukan debugging pada sebuah website. Dev Tools ini merupakan tools yang andal dalam mencari suatu bugs dan memperbaikinya. Bahkan kita dapat mensimulasikan tampilan website pada sebuah layar smartphone, sehingga tak perlu repot-repot memakai smartphone untuk melihat responsibilitas website yang kita kembangkan.</br></br>
<b>Membuat berkas HTML Pertama</b></br>
Untuk langkah awal tentunya kita membuat sebuah berkas HTML. Kita akan mencoba membuatnya dari nol dengan menggunakan alat yang ada. Gunakanlah text editor usungan sistem operasi masing-masing agar kita tahu bagaimana pengalaman membuat dan menuliskan sebuah kode tanpa bantuan code completion.</br></br>
<b>Windows</b></br>
Langkah awal dalam membuat berkas HTML adalah kita buka Notepad pada komputer kita. Untuk membukanya bisa melalui beberapa cara, salah satunya melalui fitur Run yang terdapat pada Windows. Silakan gunakan kombinasi tombol Windows + R untuk membuka jendela Run, kemudian tuliskan “notepad”</br></br>
<b>Struktur Dasar HTML</b></br>
Website serupa dengan berkas dokumen yang ada seperti koran, majalah, atau buku. Serupa dalam hal memiliki struktur konten layaknya dokumen sehari-hari yang kita baca. Pada sebuah majalah terdapat judul, gambar yang ditampilkan dan teks dalam bentuk paragraf. Terkadang, jika konten tersebut panjang terdapat sub-judul untuk memisahkannya menjadi beberapa bagian.</br></br>
Judul dan subjudul pada sebuah dokumen menggambarkan suatu hierarki dari informasi. Misalnya, judul dengan ukuran besar merupakan judul utama dalam sebuah konten. Kemudian diikuti dengan judul kecil di bawahnya yang menjelaskan informasi dengan lebih mendetail lagi.</br></br>
Berkas HTML dasarnya memiliki struktur yang nampak seperti ini:
</p>

```plantuml 
 <html>
    <head>
    <title>Judul Halaman</title>
    </head>
    <body>
        <h1>Heading Utama</h1>
        <p>Sebuah Paragraph.</p>
    </body>
</html>
```

<p align="justify">Di antara tag pembuka dan penutup sebuah elemen, kita dapat meletakkan sebuah konten. Konten dapat berupa teks ataupun sebuah elemen HTML lain. Contohnya, elemen <html> memiliki konten yaitu elemen <head> dan juga elemen <body>. Lalu, elemen <head> memiliki konten berupa elemen <title> yang di dalamnya memiliki konten berupa teks dari judul halaman yang ditampilkan. Begitu pula dengan elemen lainnya, sehingga hirarki elemen HTML nampak seperti ini.</p>
<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Dasar-Pemrograman-Web/blob/main/gambar2.jpeg"></p>
<p align="justify"><b>Elemen <html></b></br>
Hierarki elemen teratas pada berkas HTML adalah elemen HTML-nya itu sendiri. Elemen ini digunakan untuk memberitahu kepada browser bahwa ini merupakan sebuah berkas HTML sekaligus menjadi root dari sebuah berkasnya itu. Seluruh elemen lainnya tentunya dituliskan pada konten elemen ini.</br></br>
<b>Elemen <head></b></br>
Elemen <head> pada berkas HTML berfungsi sebagai tempat disimpannya informasi dari dokumen HTML. Informasi dapat berupa elemen meta, style, atau link. Dan juga pada elemen ini judul dari dokumen HTML didefinisikan dengan menggunakan elemen <title>. Berikut contoh elemen yang berada pada konten head:
 
  ```plantuml
1.<title> 
2.<style>
3.<base>
4.<link>
5.<meta>
6.<script>
7.<noscript>
```
 
 </p>

<p align="justify">Pada HTML versi 4.01, elemen <head> wajib ada dalam sebuah berkas HTML. Berikut contoh penulisan sebuah elemen <head> beserta contoh konten di dalamnya:</br>
  
  ```plantuml
<head>
    <meta charset="utf-8">
    <title>Judul halaman</title>
    <style> Style </style>
</head>
```

Tetapi sejak HTML5, penggunaan <head> dapat dihilangkan. Sehingga struktur dasar berkas HTML menjadi seperti ini:</p>

  ```plantuml
<html>
    <meta charset="utf-8">
    <title>Judul halaman</title>
    <style> Style </style>
    <body>
        <h1>Heading Utama</h1>
        <p>Sebuah Paragraph.</p>
    </body>
</html>
```

<p align="justify"><b>Elemen <body></b></br>
Seluruh konten yang terdapat pada elemen ini akan ditampilkan pada halaman website. Maka dari itu, elemen ini digunakan untuk menampung seluruh konten atau elemen yang ditampilkan ke dalam jendela browser. Silakan coba tuliskan kode berikut, simpan dalam format HTML dan jalankan pada browser:

 ```plantuml
<html>
    <head>
        <title>Ini merupakan judul dari dokumen HTML</title>
    </head>
    <body>
        <h1>header yang diletakan di dalam elemen body</h1>
        <p>Ini merupakan sebuah paragraph yang juga diletakan pada sebuah konten body, sehingga konten ini dapat dilihat oleh 
        pengguna pada jendela browser.</p>
    </body>
</html>
```

Maka seluruh konten yang dituliskan di dalam elemen <body> akan nampak pada browser.</p>

<p align="center"><img src="https://github.com/yenysyafitry/Belajar-Dasar-Pemrograman-Web/blob/main/gambar2.jpeg"></p>
<p align="justify">Kecuali jika kita ingin menuliskan sebuah notes pada berkas HTML, kita perlu gunakan commenting tag (<!--   -->). Semua yang dituliskan di antara tag komentar tidak akan memberikan pengaruh apa pun, termasuk pada tampilan di jendela browser. Pada HTML, tag komentar dituliskan seperti ini:</p>

```plantuml
<!-- Ini merupakan sebuah komentar -->
<!-- Ini merupakan
  sebuah komentar yang
  terdiri lebih dari satu baris -->
  ```
  
<p align="justify">Sebuah komentar berguna untuk memberikan label dan mengorganisir sebuah dokumen yang panjang, terlebih ketika kita bekerja secara tim.</br></br>
<b>Lorem Ipsum</b></br>
Lorem ipsum adalah teks standar yang ditempatkan untuk mendemonstrasikan elemen grafis atau presentasi visual seperti font, tipografi, dan tata letak. Tujuan penggunaan lorem ipsum sebagai berikut:<ol align="justify">
<li>Sebagai pengisi sementara jika belum ada konten teks.</li>
<li>Jika ingin menunjukkan hasil website sementara di mana audiens diharapkan lebih fokus kepada elemen desain yang dipresentasikan dan bukan pada isi teks.</li></ol>
Ada berbagai cara untuk membuat teks lorem ipsum seperti berikut:
<ol align="justify">
<li>Gunakan Microsoft Word. Buat dokumen baru dan pada lembar kerja ketiklah =lorem(), kemudian tekan tombol enter pada keyboard. Secara otomatis akan muncul teks lorem ipsum. Kamu juga dapat mengatur jumlah teks yang muncul dengan cara ketik =lorem(“angka jumlah paragraf yang diinginkan”, “angka jumlah kalimat pada setiap paragraf”). Sebagai contoh jika mengetik =lorem(3,4) maka akan muncul teks sebanyak 3 paragraf dan masing-masing paragraf terdapat 4 teks.</br>
<li>Tersedia banyak situs generator lorem ipsum gratis seperti pada  https://id.lipsum.com/ dan https://loremipsum.io/</li></ol>

<b>Berikut catatan penting yang sudah kita pelajari sejauh ini:</b>
<ol align="justify">
<li>
Website : Halaman yang menampilkan informasi melalui teks atau gambar. Website dapat diakses melalui internet dengan menggunakan browser.
<li>Browser : Sebuah perangkat lunak yang dapat menerjemahkan berkas HTML, CSS, dan Javascript yang di dapat dari server untuk ditampilkan dalam bentuk halaman website.</li>
<li>HTTP Server : Server berperan pada sebuah website sebagai sebuah software yang dapat menerima transaksi dari HyperText Transfer Protocol.</li>
<li>DNS Server : Server yang dapat mengubah/mengarahkan website melalui sebuah nama domain.</li>
<li>Client : Perangkat yang meminta (request) suatu layanan tertentu ke suatu server.</li>
<li>HTML : Salah satu markup language yang digunakan untuk membuat struktur dan menampilkan konten pada World Wide Web (Website).</li>
<li>CSS : Bahasa yang digunakan untuk mengatur dan mempercantik tampilan pada website.</li>
<li>JavaScript : Bahasa pemrograman yang digunakan untuk membantu website menampilkan informasi secara dinamis.</li>
<li>Text Editor : Sebuah perangkat lunak yang digunakan untuk mengelola plain text. Kode HTML, CSS, dan Javascript dituliskan menggunakan perangkat ini.</li>
<li>Plain text : Teks yang tidak terformat. Format teks yang digunakan dalam menuliskan berkas HTML, CSS, dan Javascript.</li>
<li>Rich text : Teks terformat. Format teks yang digunakan ketika kita menulis menggunakan Microsoft Word atau teks editor berbasis WYSIWYG (What You See Is What You Get).</li>
<li>Element : Sebuah komponen pada HTML yang ditandai dengan tag pembuka dan penutup.</li></ol>
</p>
<p align="justify">
 <b>Atribut HTML</b></br>
Pada sub-modul sebelumnya kita sudah mengenal apa itu elemen. Elemen dituliskan dengan awalan tag pembuka <> dan diakhiri dengan tag penutup </>. Ada satu hal lagi yang bisa kita tuliskan pada sebuah elemen, lebih tepatnya pada sebuah tag pembuka, yaitu Attribute. Atribut ini berfungsi memberikan informasi tambahan pada sebuah elemen. Atribut dituliskan pada tag pembuka sebuah elemen setelah nama dari elemennya tersebut ditulis. Contohnya:</br></br>

```plantuml
<p lang="id">Kota metropolitan terbesar di Provinsi Jawa Barat, sekaligus menjadi ibu kota provinsi tersebut.</p>
```

Pada contoh kode tersebut, kita menetapkan artibut bahasa (dengan penulisan lang) dengan nilai “id” atau Indonesia (kode bahasa bisa kita explore pada link berikut: https://www.w3schools.com/tags/ref_language_codes.asp) pada sebuah elemen paragraf.</br></br>
Untuk menuliskan sebuah atribut kita memerlukan nama dari atribut itu diikuti dengan nilai atribut tersebut dalam bentuk string (Dituliskan dalam tanda kutip dua). Untuk lebih jelasnya, perhatikan gambar berikut:</br></br>
Atribut pada elemen juga dapat dituliskan lebih dari satu. Kita bisa menuliskan kembali seluruh struktur atribut di samping dari atribut yang sudah ada. Contohnya pada elemen paragraf di atas, kita akan memberikan sebuah atribut translate, sehingga penulisannya menjadi seperti ini:</p>

```plantuml
<p lang="id" translate="no">Kota metropolitan terbesar di Provinsi Jawa Barat, sekaligus menjadi ibu kota provinsi tersebut.</p>
```
<p align="justify">
Dengan menambahkan atribut translate dan memberikan nilai “no” pada elemen paragraf tersebut, maka konten dari elemen yang dimaksud tidak akan diterjemahkan oleh layanan sistem translate otomatis seperti Google Translate.</br></br>
Lantas atribut apa saja yang dapat digunakan pada elemen HTML? Pada elemen HTML terdapat dua jenis atribut, yaitu Global Attribute dan atribut yang hanya bisa digunakan pada elemen tertentu. Untuk atribut yang spesifik pada sebuah elemen, kita akan mengulasnya   pada pembahasan elemen tersebut. Untuk Global Attribute, berikut daftar atribut yang bisa kita gunakan di seluruh elemen HTML.</p>
<p align="justify"><table>
 <tr><td>Attribute</td><td>Description</td></tr>
<tr><td>accesskey</td><td>Menentukan tombol shortcut untuk mengaktifkan/memfokuskan pada sebuah element.</td></tr>
<tr><td>class</td><td>Menentukan satu atau lebih classname untuk sebuah elemen.</td></tr>
<tr><td>contenteditable</td><td>Menentukan konten dari elemen merupakan konten yang dapat diubah atau tidak.</td></tr>
<tr><td>data-*</td><td>Digunakan untuk menyimpan sebuah data pribadi khusus ke halaman atau aplikasi.</td></tr>
<tr><td>dir</td><td>Menentukan arah teks untuk konten pada suatu elemen.</td></tr>
<tr><td>draggable</td><td>Menentukan apakah suatu elemen dapat di-drag atau tidak.</td></tr>
<tr><td>dropzone</td><td>Menentukan apakah data yang di-drag adalah data yang disalin, dipindahkan, atau ditautkan saat dijatuhkan.</td></tr>
<tr><td>hidden</td><td>Menentukan apakah suatu elemen ditampilkan atau tidak pada browser.</td></tr>
<tr><td>id</td><td>Menetapkan id pada elemen.</td></tr>
<tr><td>lang</td><td>Menentukan bahasa pada konten elemen.</td></tr>
<tr><td>spellcheck</td><td>Menentukan apakah elemen harus diperiksa ejaannya dan tata bahasanya atau tidak.</td></tr>
<tr><td>style</td><td>Menentukan styling secara satu baris untuk suatu elemen.</td></tr>
<tr><td>tabindex</td><td>Menentukan urutan dari suatu elemen.</td></tr>
<tr><td>title</td><td>Menentukan informasi tambahan tentang suatu elemen.</td></tr>
<tr><td>translate</td><td>Menentukan apakah konten elemen harus diterjemahkan atau tidak.</td></tr></table></p>
