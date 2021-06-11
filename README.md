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
        <p>Ini merupakan sebuah paragraph yang juga diletakan pada sebuah konten body, 
        sehingga konten ini dapat dilihat oleh pengguna pada jendela browser.</p>
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
<p align="justify"><b>Atribut HTML</b></br>
Pada sub-modul sebelumnya kita sudah mengenal apa itu elemen. Elemen dituliskan dengan awalan tag pembuka <> dan diakhiri dengan tag penutup </>. Ada satu hal lagi yang bisa kita tuliskan pada sebuah elemen, lebih tepatnya pada sebuah tag pembuka, yaitu Attribute. Atribut ini berfungsi memberikan informasi tambahan pada sebuah elemen. Atribut dituliskan pada tag pembuka sebuah elemen setelah nama dari elemennya tersebut ditulis. Contohnya:</p>

```plantuml
<p lang="id">Kota metropolitan terbesar di Provinsi Jawa Barat, sekaligus menjadi ibu kota 
provinsi tersebut.</p>
```

<p align="justify">
Pada contoh kode tersebut, kita menetapkan artibut bahasa (dengan penulisan lang) dengan nilai “id” atau Indonesia (kode bahasa bisa kita explore pada link berikut: https://www.w3schools.com/tags/ref_language_codes.asp) pada sebuah elemen paragraf.</br></br>
Untuk menuliskan sebuah atribut kita memerlukan nama dari atribut itu diikuti dengan nilai atribut tersebut dalam bentuk string (Dituliskan dalam tanda kutip dua). Untuk lebih jelasnya, perhatikan gambar berikut:</br></br>
Atribut pada elemen juga dapat dituliskan lebih dari satu. Kita bisa menuliskan kembali seluruh struktur atribut di samping dari atribut yang sudah ada. Contohnya pada elemen paragraf di atas, kita akan memberikan sebuah atribut translate, sehingga penulisannya menjadi seperti ini:</p>

```plantuml
<p lang="id" translate="no">Kota metropolitan terbesar di Provinsi Jawa Barat, sekaligus 
menjadi ibu kota provinsi tersebut.</p>
```

<p align="justify">
Dengan menambahkan atribut translate dan memberikan nilai “no” pada elemen paragraf tersebut, maka konten dari elemen yang dimaksud tidak akan diterjemahkan oleh layanan sistem translate otomatis seperti Google Translate.</br></br>
Lantas atribut apa saja yang dapat digunakan pada elemen HTML? Pada elemen HTML terdapat dua jenis atribut, yaitu Global Attribute dan atribut yang hanya bisa digunakan pada elemen tertentu. Untuk atribut yang spesifik pada sebuah elemen, kita akan mengulasnya   pada pembahasan elemen tersebut. Untuk Global Attribute, berikut daftar atribut yang bisa kita gunakan di seluruh elemen HTML.</p>
<table align="justify">
 <tr align="center"><td><b> Attribute</b></td><td><b> Description</b></td></tr>
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
<tr><td>translate</td><td>Menentukan apakah konten elemen harus diterjemahkan atau tidak.</td></tr></table>

<p align="justify"><b>Paragraf</b></br>
Paragraf adalah elemen paling mendasar dari sebuah dokumen teks. Pada HTML, kita bisa menunjukkan sebuah paragraf dengan menggunakan elemen <p>. Contohnya seperti ini:</p>

```plantuml
<p>Kata Bandung berasal dari kata bendung atau bendungan karena terbendungnya sungai Citarum 
oleh lava Gunung Tangkuban Parahu yang lalu membentuk telaga...</p>
   
<p>Berdasarkan filosofi Sunda, kata Bandung juga berasal dari kalimat Nga-Bandung-an Banda 
Indung, yang merupakan kalimat sakral dan luhur karena mengandung nilai ajaran Sunda. 
Nga-Bandung-an artinya menyaksikan atau bersaksi...</p>
```

<p align="justify">Ketika menggunakan paragraf pada browser, teks selalu ditampilkan dengan garis baru dan terdapat sedikit jarak (space) antar elemennya. Jarak tersebut nantinya bisa kita atur ketika sudah menerapkan styling.</p>

<table><tr align="justify"><td>Output :</br></br>Kata Bandung berasal dari kata bendung atau bendungan karena terbendungnya sungai Citarum  oleh lava Gunung Tangkuban Parahu yang lalu membentuk telaga...</br></br>
   Berdasarkan filosofi Sunda, kata Bandung juga berasal dari kalimat Nga-Bandung-an Banda Indung, yang merupakan kalimat sakral dan luhur karena mengandung nilai ajaran Sunda. Nga-Bandung-an artinya menyaksikan atau bersaksi...</td></tr></table>

<p align="justify">Paragraf dapat terdiri dari teks, elemen gambar, dan inline element lainnya. Tetapi hindarilah penggunaan element paragraf untuk konten seperti heading atau list, karena terdapat elemen lain yang lebih tepat untuk digunakan.</br></br>
“Pastikan kita selalu menggunakan elemen (tags) dalam seluruh teks yang ada pada dokumen. Teks yang berada pada dokumen HTML tanpa tags disebut “anonymous text” dan ini dapat menyebabkan dokumen HTML menjadi tidak valid.”</br></br>
<b>Heading</b></br>
Pada sub-modul sebelumnya, kita sudah melihat contoh penggunaan header yang diterapkan pada konten yang kita siapkan. Kita menggunakan < h1 > dan < h2 > dalam mengindikasi judul dan sub judul di dalam kontennya. Pada HTML terdapat < h1 > hingga < h6 > elemen heading yang dapat kita gunakan.</br></br>
Ketika kita menambahkan heading pada konten, Heading ini merepresentasikan garis besar halaman pada sebuah browser. Alat bantu baca seperti screen reader membaca garis besar halaman untuk bantu memetakan dan mengarahkan pengguna selama menjelajahi halaman. Selain itu, heading juga merupakan elemen yang dicari oleh mesin pencarian contohnya Google Search.</br></br>
 <b>List</b></br>
Seperti yang sudah disebutkan pada pembahasan paragraf, tidak semua teks dibungkus oleh paragraf, salah satunya list. Kita pun terbiasa membuat list dalam kehidupan sehari-hari, baik membuat to-do list atau daftar yang struktur sekalipun. </br></br>
Pada HTML terdapat tiga tipe list:</b></p><ol align="justify">
<li> Unordered lists : daftar yang ditampilkan tidak memiliki urutan. </li>
<li> Ordered lists : daftar yang ditampilkan secara terurut.</li>
<li> Description lists : daftar yang terbuat dari beberapa istilah diikuti dengan deskripsi dari istilah tersebut.</li></ol>

<p align="justify"><b>Unordered List</b></br>
Seperti namanya, unordered list merupakan daftar yang tidak mementingkan urutan. Standarnya, unordered list menampilkan bullet pada tiap item list-nya (tetapi kita bisa mengubahnya dengan styling). Untuk menetapkan konten sebagai unordered list kita gunakan <ul></ul> kemudian di dalam elemen tersebut kita gunakan tags < li >< /li > untuk menetapkan item pada list tersebut. Contoh penerapannya sebagai berikut:
 
 ```plantuml
 <ul>
   <li>Item 1</li>
   <li>Item 2</li>
   <li>Item 3</li>
   <li>Item 4</li>
</ul>
 ```
 
 Ketika kita membukanya pada browser, maka akan nampak seperti ini:
 <ul>
   <li>Item 1</li>
   <li>Item 2</li>
   <li>Item 3</li>
   <li>Item 4</li>
</ul>
Di antara tag elemen < li >, kita dapat mengisikan konten apapun termasuk elemen HTML lain. Contohnya kita dapat memasukan sebuah heading atau paragraf pada item.
 
  ```plantuml
 <ul>
   <li><h1>Sebuah Heading sebagai item list</h1></li>
   <li><h2>Sebuah Heading level 2 sebagai item list</h2></li>
   <li><p>Sebuah paragraf sebagai item list</p></li>
</ul>
 ```
 
 Seperti yang kita sudah ketahui, maka list item akan menampilkan seperti format header.
 
 <table><tr><td>Output :</br>
  <ul>
   <li><h1>Sebuah Heading sebagai item list</h1></li>
   <li><h2>Sebuah Heading level 2 sebagai item list</h2></li>
   <li><p>Sebuah paragraf sebagai item list</p></li>
</ul>
 </td></tr></table>
Kita juga bisa menyimpan kembali elemen < ul > untuk membuat sebuah nested list.
 
 ```plantuml
 <ul>
   <li>List item 1</li>
   <li>List item 2</li>
   <li>List item 3
       <ul>
           <li>List item 3.1</li>
           <li>List item 3.2</li>
           <li>List item 3.3</li>
       </ul>
   </li>
   <li>List item 4</li>
</ul>
```

<table><tr><td> <b>Output :</b></br></br>
<ul>
   <li>List item 1</li>
   <li>List item 2</li>
   <li>List item 3
       <ul>
           <li>List item 3.1</li>
           <li>List item 3.2</li>
           <li>List item 3.3</li>
       </ul>
   </li>
   <li>List item 4</li>
</ul>
</td></tr>
</p>

<p align="justify"><b>Ordered List</b></br>
Ordered list digunakan untuk membuat list yang mementingkan urutan. Contohnya, membuat daftar instruksi langkah demi langkah sehingga dibutuhkan urutan yang sesuai. Ordered list bekerja seperti unordered list, namun perbedaanya pada tiap item menampilkan angka bukan sebuah bullet. Angka yang ditampilkan, otomatis berurut tiap itemnya, sehingga kita tidak perlu menuliskan secara kasar urutan nomornya. Hal ini tentu mempermudah kita untuk mengorganisir tiap itemnya. Untuk menetapkan konten sebagai ordered list kita gunakan < ol >< /ol >. Sama seperti Unordered list, tiap item dalam list ditetapkan dengan menggunakan tags < li >< /li >.</p>

```plantuml
<ol>
   <li>Langkah pertama</li>
   <li>Langkah kedua</li>
   <li>Langkah ketiga</li>
   <li>Langkah selanjutnya</li>
</ol>
```

Ketika kita membukanya pada browser, maka akan nampak seperti ini:
<ol>
   <li>Langkah pertama</li>
   <li>Langkah kedua</li>
   <li>Langkah ketiga</li>
   <li>Langkah selanjutnya</li>
</ol>

<p align="justify">Sama seperti pada unordered list, di antara tag elemen <li> kita dapat mengisikan konten apapun termasuk elemen HTML lain. Pada ordered list, tipe urutan angkanya dapat kita atur melalui sebuah atribut type. Contohnya, selain nomor urutan angka dapat menggunakan alfabet ataupun angka romawi.</p>

```plantuml
<ol type="I">
   <li>Langkah pertama</li>
   <li>Langkah kedua</li>
   <li>Langkah ketiga</li>
   <li>Langkah selanjutnya</li>
</ol>
 
<ol type="A">
   <li>Langkah pertama</li>
   <li>Langkah kedua</li>
   <li>Langkah ketiga</li>
   <li>Langkah selanjutnya</li>
</ol>
```

<table><tr><td><ol type="I">
   <li>Langkah pertama</li>
   <li>Langkah kedua</li>
   <li>Langkah ketiga</li>
   <li>Langkah selanjutnya</li>
</ol>
<ol type="A">
   <li>Langkah pertama</li>
   <li>Langkah kedua</li>
   <li>Langkah ketiga</li>
   <li>Langkah selanjutnya</li>
 </ol> </td></tr></table>
 
 Berikut nilai - nilai yang dapat digunakan pada atribut type pada elemen < ol >:

<table><tr align="center"><td><b>Nilai</b></td><td><b>Deskripsi</b></td></tr>
<tr><td>1</td><td>Menggunakan angka dalam urutan item (default)</td></tr>
<tr><td>a</td><td>Menggunakan huruf kecil dalam urutan item</td></tr>
<tr><td>A</td><td>Menggunakan huruf besar dalam urutan item</td></tr>
<tr><td>i</td><td>Menggunakan huruf romawi kecil dalam urutan item</td></tr>
<tr><td>I</td><td>Menggunakan huruf romawi besar dalam urutan item</td></tr></table>

<p align="justify">Selain tipe angka pada urutan, kita juga bisa menetapkan nilai awal pada sebuah ordered list dengan menggunakan atribut start. Contohnya, jika kita ingin memulai sebuah list dari angka 7, maka kita tetapkan atribut start dengan nilai 7 pada elemen < ol >.</p>

```plantuml
<ol start="7">
   <li>Langkah ketujuh</li>
   <li>Langkah kedelapan</li>
   <li>Langkah kesembilan</li>
   <li>Langkah selanjutnya</li>
</ol>
```

Maka hasilnya list akan dimulai dengan nilai urutan ke-7.
<table><tr><td><ol start="7">
   <li>Langkah ketujuh</li>
   <li>Langkah kedelapan</li>
   <li>Langkah kesembilan</li>
   <li>Langkah selanjutnya</li>
 </ol> </td></tr></table>
 
 <p align="justify"><b>Menambahkan List pada Halaman Profil</b></br>
Setelah mempelajari penerapan list pada HTML, sekarang kita coba terapkan elemen list yang berperan sebagai navigasi pada halaman profil yang sebelumnya sudah kita buat.  “Pada langkah ini dan selanjutnya, Sebaiknya gunakanlah teks editor yang disarankan pada materi text editor agar proses penulisan dan pengelolaan berkas HTML dapat lebih cepat”.</br></br>
Silakan buka kembali berkas index.html pada teks editor. Tambahkan elemen unordered list di bawah dari elemen paragraf pertama pada berkas HTML sebagai berikut.</p>

```plantuml
…………..
<body>
<h1>Bandung</h1>
<p>Kota metropolitan terbesar di Provinsi Jawa Barat, sekaligus menjadi ibu kota provinsi tersebut.</p>
<ul>
   <li>Sejarah</li>
   <li>Geografis</li>
   <li>Wisata</li>
</ul>
<h2>Sejarah</h2>
……...
```

Sehingga pada browser akan menampilkan list seperti ini.
<table><tr><td>
 

<body>
<h1>Bandung</h1>
<p>Kota metropolitan terbesar di Provinsi Jawa Barat, sekaligus menjadi ibu kota provinsi tersebut.</p>
<ul>
   <li>Sejarah</li>
   <li>Geografis</li>
   <li>Wisata</li>
</ul>
<h2>Sejarah</h2>

 
 </td></tr></table>

<p align="justify"><b>Gambar</b></br>
Pada HTML untuk menampilkan sebuah gambar kita bisa menggunakan tag <img>. Berbeda dengan elemen lain, elemen <img> tidak menuliskan konten di antara tag pembuka dan tag penutup. Tetapi untuk menetapkan gambar yang ditampilkan kita gunakan sebuah atribut. Contohnya seperti ini: </p>

```plantuml
<img src="https://github.com/yenysyafitry/Belajar-Dasar-Pemrograman-Web/blob/main/gambar2.jpeg" alt="gambar2">
```

<p align="justify">Pada contoh kode di atas, perlu kita perhatikan bahwa element <img> merupakan sebuah elemen kosong (tidak memiliki konten sehingga tidak ada closing tag).</br></br> 
Selain itu, yang perlu kita perhatikan adalah atribut yang ada pada elemen tersebut, terdapat dua elemen yang harus kita gunakan ketika menerapkan elemen <img>.</br></br>
Yang pertama, atribut src. Atribut ini berfungsi sebagai sumber dari gambar yang ditampilkan. Atribut ini dapat bernilai url gambar atau path gambar lokal dari gambar yang digunakan.</br></br> 
Selanjutnya adalah atribut alt. Atribut ini sebenarnya tidak wajib untuk diterapkan, hanya saja atribut ini akan sangat berguna ketika gambar tidak berhasil ditampilkan. Nilai atribut ini merupakan gambaran dari gambar yang ditampilkan dalam bentuk tulisan. Sehingga ketika gambar gagal ditampilkan maka akan memunculkan teks alternatif yang dapat mewakili arti dari gambar tersebut.  </br></br> 
Selanjutnya terdapat atribut lain yang bisa Anda gunakan pada elemen ini, contohnya title. Title berfungsi sebagai informasi tambahan untuk sebuah gambar. Informasi tersebut akan muncul ketika kita mengarahkan sebuah cursor pada gambar yang ditampilkan.</br></br> 
<b>Jenis format gambar</b></br>
Berikut adalah jenis format gambar yang umum digunakan pada pembuatan website.</p>

<table align="justify"><tr align="center"><td><b>Nama</b></td><td>  <b>Ekstensi Format File  </b></td><td><b>Keterangan</b></td></tr>
<tr><td>Graphics Interchange Format </td><td> .gif </td><td>Dapat digunakan untuk gambar animasi.</br>Ukuran file biasanya kecil.</br>Kualitas gambar terbatas.</td></tr>
<tr><td>Joint Photographic Expert Group image</td><td> .jpg, .jpeg, .jfif, .pjpeg, .pjp </td><td>Kualitas text pada gambar dapat menjadi buruk.</br>Ukuran file lumayan kecil.</br>Pada website biasanya digunakan untuk gambar yang tidak banyak text.</td></tr>
<tr><td>Portable Network Graphics</td><td>.png</td><td>Text lebih bisa terbaca dibandingkan jenis Jpeg.
Ukuran file dapat menjadi besar sehingga mengurangi kecepatan memuat situs.</td></tr>
<tr><td>WebP</td><td>.webp</td><td>Dibandingkan dengan gambar berkualitas sama pada jpeg atau png, ukuran file pada webp dapat menjadi lebih kecil.</br>
Namun tidak semua web browser dapat membaca webp.</td></tr>
<tr><td>Scalable Vector Graphics</td><td>.svg</td><td>Kualitas gambar terjaga dan ukuran file kecil.</br>Namun tidak cocok untuk gambar yang terlalu kompleks seperti foto.</br>Pada website biasanya digunakan untuk logo atau icon.</td></tr></table>
<p align="justify"><b>Mengatur ukuran pada gambar</b></br>
Untuk mengatur ukuran gambar yang ditampilkan juga tentunya menggunakan sebuah atribut. Untuk menentukan lebar gambar kita gunakan atribut width, dan untuk menentukan tinggi tentu gunakan atribut height.</br></br>
Ketika menggunakan atribut ini disarankan hanya gunakan salah satunya. Terkecuali kita menentukan nilai lebar dan tingginya sesuai dengan rasio dari ukuran gambar aslinya.</br></br>
Contohnya, jika kita tetap memaksa untuk menentukan ukuran panjang dan lebar sebuah gambar tanpa menyesuaikan rasionya, maka gambar yang ditampilkan tidak akan proporsional.</p>

```plantuml
<!-- Menetapkan ukuran gambar berdasarkan lebar -->
<img src="https://i.imgur.com/EUUXQcf.png" alt="dicoding" width="500px">

<!-- Menetapkan ukuran gambar berdasarkan tinggi -->
<img src="https://i.imgur.com/EUUXQcf.png" alt="dicoding" height="100px">
```

<p align="justify"><b>Menambahkan Gambar pada Halaman Profil</b></br>
Setelah mempelajari penerapan list pada HTML, sekarang kita coba terapkan elemen gambar konten yang terdapat di halaman profil yang sebelumnya sudah kita buat. Sebelum menerapkannya, silakan unduh resource gambar yang digunakan pada latihan melalui tautan berikut: assets.zip </br>
Pindahkan berkas yang sudah diunduh pada folder yang sama dengan berkas index.html.</br>
Kemudian lakukan ekstraksi pada berkas assets.zip tersebut dengan melakukan Klik Kanan -> Extract Here. </br>
Jika berhasil, akan terbentuk folder dengan nama assets. Sampai langkah ini, berkas assets.zip sudah tidak digunakan. Kita bisa menghapusnya.</br>
Pastikan di dalam folder assets -> image terdapat empat berkas gambar yang akan kita gunakan pada latihan.</br>
Silakan buka kembali berkas index.html pada teks editor. Tambahkan elemen gambar di bawah elemen heading sesuai kontennya masing-masing.</p>

```plantuml
<body>
  ……
 
   <h2>Sejarah</h2>
   <img src="assets/image/history.jpg" alt="sejarah">
 
  …….
 
   <h2>Geografis</h2>
   <img src="assets/image/geografis.jpg" alt="geografis">
 
  …….
 
   <h2>Wisata</h2>
 
  …….
 
 
   <h3>Farm House Lembang</h3>
   <img src="assets/image/farm-house.jpg" alt="farm house">

 
  …….
   <h3>Observatorium Bosscha</h3>
   <img src="assets/image/bosscha.jpg" alt="bosscha">
  …….
</body>
```

<p align="justify">Perhatikan penulisan nilai dari atribut src. Penulisan sedikit berbeda dengan yang telah kita pelajari. Penulisan alamat gambar tidak dimulai dengan https://www, karena kita menggunakan gambar lokal yang ada pada project kita. Sehingga untuk penulisan path-nya mengarah ke lokasi dari berkas gambar tersebut.</br></br>
<b>Teks Terformat</b></br>
Sejauh ini, kita sudah mengenal paragraf, heading dan juga list pada HTML. Tapi masih ada beberapa lagi yang merupakan spesial teks format yang dapat kita gunakan yaitu < blockquote >, < pre >, dan < figure >.</br></br>
<b>Long quotations</b></br>
Jika pada konten kita memiliki sebuah kutipan ataupun sebuah testimonial, kita dapat gunakan format long quotations dengan menggunakan tags < blockquote >. Konten di dalam elemen < blockquote > ini dapat berupa sebuah paragraf, heading, ataupun list. 
</p>

```plantuml
<blockquote>
   <p>Situs web (bahasa Inggris: website) adalah sekumpulan halaman web yang 
   saling berhubungan yang umumnya   berada pada peladen yang sama berisikan 
   kumpulan informasi yang disediakan secara perorangan, kelompok, atau organisasi.</p>
</blockquote>
```

<p align="justify">Berikut tampilan standar ketika kita sebuah konten berada di dalam < blockquote >.</p>

<blockquote>
   <p>Situs web (bahasa Inggris: website) adalah sekumpulan halaman web yang saling berhubungan yang umumnya   berada pada peladen yang sama berisikan kumpulan informasi yang disediakan secara perorangan, kelompok, atau organisasi.</p>
</blockquote>

<p align="justify">Pada elemen ini kita dapat menggunakan atribut cite untuk menentukan sumber URL dari sebuah kutipan (Jika kutipan tersebut bersumber dari sebuah situs website).</p>

```plantuml
<blockquote cite="https://id.wikipedia.org/wiki/Situs_web">
   <p>Situs web (bahasa Inggris: website) adalah sekumpulan halaman web yang saling 
   berhubungan yang umumnya berada pada peladen yang sama berisikan kumpulan informasi
   yang disediakan secara perorangan, kelompok, atau organisasi.</p>
</blockquote>
```

<p align="justify"><b>Preformatted text</b></br>
Pada sub-modul sebelumnya, kita sudah mengetahui bahwa HTML akan mengabaikan penulisan spasi yang dituliskan secara berulang dan juga line breaks (baris baru). Tetapi pada beberapa tipe konten seperti contoh kode atau puisi hal tersebut sangat berarti. Dengan begitu, terdapat sebuah elemen yang dapat kita gunakan untuk menampilkan konten sesuai yang kita tulis pada text editor. Untuk menggunakannya, kita gunakan elemen < pre > sebagai pembungkus kontennya. Perhatikan contoh berikut:</p>

```plantuml
<pre>
   SAJAK PUTIH
 
Bersandar pada tari warna pelangi
Kau depanku bertudung sutra senja
Di hitam matamu kembang mawar dan melati
Harum rambutmu mengalun bergelut senda
 
Sepi menyanyi, malam dalam mendoa tiba
Meriak muka air kolam jiwa
Dan dalam dadaku memerdu lagu
Menarik menari seluruh aku
 
Hidup dari hidupku, pintu terbuka
Selama matamu bagiku menengadah
Selama kau darah mengalir dari luka
Antara kita Mati datang tidak membelah...
 
                   Karya : Chairil Anwar
</pre>
```

<p align="justify">Sehingga pada browser akan menampilkan hasil yang sama seperti yang kita tuliskan.</p>

<pre>
   SAJAK PUTIH
 
Bersandar pada tari warna pelangi
Kau depanku bertudung sutra senja
Di hitam matamu kembang mawar dan melati
Harum rambutmu mengalun bergelut senda
 
Sepi menyanyi, malam dalam mendoa tiba
Meriak muka air kolam jiwa
Dan dalam dadaku memerdu lagu
Menarik menari seluruh aku
 
Hidup dari hidupku, pintu terbuka
Selama matamu bagiku menengadah
Selama kau darah mengalir dari luka
Antara kita Mati datang tidak membelah...
 
                   Karya : Chairil Anwar
</pre>

<p align="justify"><b>Figure</b></br>
Elemen ini digunakan untuk merepresentasikan konten tersendiri (self-contained content) seperti ilustrasi, diagram, foto atau bisa juga sebuah baris kode. Banyak hal yang dapat digunakan dalam elemen ini. Elemen ini digunakan untuk mengkelompokkan blok konten yang dapat dipindahkan posisinya dari blok utama sebuah dokumen tanpa mempengaruhi arti dari induk dokumen. Di dalam elemen figure kita dapat menuliskan elemen <figcaption> sebagai sebuah caption (judul) untuk konten tersebut. Berikut contoh penggunaan figure pada sebuah konten gambar.</p>

```plantuml
<p>Dicoding adalah sebuah perusahaan startup yang bertujuan mengembangkan ekosistem developer di Indonesia.
    Berdiri sejak 5 Januari 2015, Dicoding memiliki platform pembelajaran elektronik di laman Dicoding.com.</p>
<figure>
    <img src="https://i.imgur.com/cs2BJzw.jpg" alt="dicoding" width="200px">
    <figcaption>Dicoding</figcaption>
</figure>
<p>Materi perdana yang menjadi magnet dari awal berdirinya Dicoding hingga kini adalah kelas Menjadi Android Developer
    Expert. Kelas ini dikembangkan oleh Google Developer Expert in Android, Sidiq Permana dan Head of Dicoding Academy,
    Ahmad Imaduddin. Seperti halnya kelas Picodiploma lain, modul online-nya juga hadir dalam bentuk buku berjudul sama
    yang telah mendapatkan ijin dan ISBN.</p>
   ``` 
   
   <p align="justify">Contoh lainnya, figure ini dapat kita gunakan untuk markup sebuah konten puisi.</p>
   
   ```plantuml
   <figure>
   <pre>
           SAJAK PUTIH
 
       Bersandar pada tari warna pelangi
       Kau depanku bertudung sutra senja
       Di hitam matamu kembang mawar dan melati
       Harum rambutmu mengalun bergelut senda
 
       Sepi menyanyi, malam dalam mendoa tiba
       Meriak muka air kolam jiwa
       Dan dalam dadaku memerdu lagu
       Menarik menari seluruh aku
 
       Hidup dari hidupku, pintu terbuka
       Selama matamu bagiku menengadah
       Selama kau darah mengalir dari luka
       Antara kita Mati datang tidak membelah...
   </pre>
   <figcaption>Sajak Putih oleh Charil Anwar</figcaption>
</figure>
   ``` 
   
   <table><tr><td><figure>
   <pre>
           SAJAK PUTIH
 
       Bersandar pada tari warna pelangi
       Kau depanku bertudung sutra senja
       Di hitam matamu kembang mawar dan melati
       Harum rambutmu mengalun bergelut senda
 
       Sepi menyanyi, malam dalam mendoa tiba
       Meriak muka air kolam jiwa
       Dan dalam dadaku memerdu lagu
       Menarik menari seluruh aku
 
       Hidup dari hidupku, pintu terbuka
       Selama matamu bagiku menengadah
       Selama kau darah mengalir dari luka
       Antara kita Mati datang tidak membelah...
   </pre>
   <figcaption>Sajak Putih oleh Charil Anwar</figcaption>
</figure></td></tr></table>


<p align="justify"><b>Inline Formatting Text</b></br>
Kita sudah belajar mengidentifikasi penggunaan elemen pada konten yang major (besar) dengan menerapkan semantic HTML untuk mengorganisasikan kontennya. Sekarang kita akan mengenal beberapa formatting text yang digunakan dalam sebuah baris teks (inline text). </br></br>
Sebelum menjelaskan elemen inline untuk formatting text yang dapat digunakan, sepertinya kita perlu membahas sekilas mengenai block dan inline. Standarnya elemen HTML memiliki dua sifat yaitu block dan inline. Elemen yang memiliki sifat block selalu membuat baris baru ketika menampilkannya, contohnya seperti elemen paragraf, list, heading, dan lainnya. Berlawanan dengan elemen yang memiliki sifat inline, elemen ini tidak menambahkan baris baru ketika dibuat. Apa saja elemen tersebut? Mari kita bahas satu persatu.</br></br>
<b>Anchor</b></br>
Apa itu anchor? Anchor (jangkar) merupakan elemen yang digunakan untuk membuat sebuah hyperlink ke halaman atau website lain, file, alamat email, atau URL lainnya. Untuk menggunakan elemen ini kita gunakan tag <a>...</a> bersama dengan atribut href untuk menetapkan sebuah target yang akan dituju.</p>

 ```plantuml
 <p>Hubungi kami di</p>
<ul>
   <li><a href="https://example.com">Website</a></li>
   <li><a href="mailto:info@example.com">Email</a></li>
   <li><a href="tel:+62123456">Telepon</a></li>
   <li><a href="#address">Alamat</a></li>
</ul> 
```

<p align="justify">Selain atribut href, terdapat beberapa atribut khusus yang dapat digunakan pada elemen ini, antara lain:</p>
<table><tr><th width="100px">Atribut</th><th width="100px">Nilai</th><th width="300px">Deskripsi</th></tr>
<tr><td>download</td><td>filename</td><td>Menginstruksikan browser untuk mengunduh pada URL yang ditetapkan daripada mengarahkannya. </td></tr> 
<tr><td>href</td><td>URL</td><td>Menetapkan target yang akan diarahkan/unduh ketika pengguna menekan hyperlink.</td></tr>
<tr><td>hreflang</td><td>language_code</td><td>Menetapkan bahasa dari dokumen target.</td></tr>
<tr><td>ping</td><td>list_of_URLs</td><td>Menetapkan URL yang akan diberitahu dengan mengirimkan post request ping pada body oleh browser (berjalan di belakang layar) ketika target URL pada hyperlink ditekan. Biasanya atribut ini digunakan untuk pelacakan.</td></tr>
<tr><td>referrerpolicy</td><td>no-referrer, no-referrer-when-downgrade, origin, origin-when-cross-origin, unsafe-url</td><td>Menetapkan referensi untuk dikirim pada target.</td></tr>
<tr><td>rel</td><td>alternate,author,bookmark, external, help, license, next, nofollow, noreferrer, noopener, prev, search, tag</td><td>Menetapkan hubungan antara halaman yang ditampilkan dengan target.</td></tr>
<tr><td>target</td><td>_blank,_parent,_self,_top</td><td>Menetapkan lokasi ketika membuka target contohnya pada sebuah tab, window atau pada tab itu sendiri.</td></tr>
<tr><td>media</td><td>media_type</td><td>Menetapkan tipe media yang digunakan pada target.</td></tr><table>
