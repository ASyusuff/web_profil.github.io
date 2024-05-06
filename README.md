# web_profil.github.io
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <style>
        *{
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    scroll-behavior: smooth;
}
ul>li>a:hover{
    color: #ffffff;
    font-size: 1.1em;
}
body{
    background: linear-gradient( #fff, #e0e7ff);
    background-image: url(img/background.png);
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
}
.container{
    margin-top: 0;
    padding: 5px;
    width: 100%;
    height: 40px;
    position:fixed;
    background-color: #5927e5;
    box-shadow: 5px;
    box-shadow: 10px 10px 10px 10px  rgba(30, 29, 29, 0.4);
}
.wrapper{
    margin-top: 0;
    padding:10px 10vh 0 10vh;
    display: flex;
    justify-content: center;
    justify-content: space-between;
    font-size: 20px;
    font-weight: bold;
}
ul{
    display: flex;
    align-items: center;
    gap: 19px;
    padding-right: 5px;
    list-style-type: none;
}
ul li a{
    text-decoration: none;
    color: black;
}
#Tentang-Saya{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background:linear-gradient( to right, #1e006f,#5927e5);
    gap: 15px;
}
.deskripsi{
    font-size: 25px;
    padding-left: 20px;
}
.BakatMinat{
    padding: 1vh 10vh 0 10vh;
    margin-top: 10px;
    font-size: 18px;
}
.aku{
    height: 400px;
    border-radius: 50%;
    padding-right: 25px;
}
p{
    text-align: justify;
}
.Kegemaran{
    padding: 50px ;
    width: auto;
    height: 60vh;
    background-color: #e0e7ff;
}
.title{
    width: auto;
    height: 25px;
    justify-content: center;
    text-align: center;
    font-size: 20px;
    color: #5927e5;
}
.containerbox{
    margin-top: 0;
    width: auto;
    height: 48vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 15px;
}
.box{
    height: auto;
    width: 30%;
    border: 3px solid #5927e5;
    padding: 0 10px 10px 10px;
}
.left{
    border-radius: 30px 0 0 30px;
}
.mid{
    border-radius: 0 0 40px 40px;
}
.right{
    border-radius: 0 30px 30px 0;
}
.box>h4{
    text-align: center;
    border-bottom:3px solid #5927e5;
}
.Keseharian{
    padding: 10vh 20px 0 20px;
    width: auto;
    height: 50vh;
    background-color: #e0e7ff;
    box-shadow: 10px 10px 10px 10px  rgba(30, 29, 29, 0.4);
}
 article >h3{
    text-align: center;
}
.blank{
    width: 100%;
    height: 50vh;
}
.transsition{
    width: 100%;
    height: 10vh;
    background: linear-gradient( #e0e7ff ,#5927e5);
}
footer{
    width: 100%;
    height: 20vh;
    background: linear-gradient( #5927e5 ,#1e006f);
    /* display: flex;
    justify-content: center;
    align-items: center; */
}
.link{
    padding: 5vh;
    display: flex;
    justify-content: center;
}
.creator{
    padding:  0 0 0;
    text-align: center;
}
section{
    min-width: auto;
}
    </style>
<body>
    <nav class="container">
        <div class="wrapper">
            <div>
                <span>PROFIL</span>
            </div>
            <ul>
                <li><a href="#Tentang-Saya">Tentang Saya</a></li>
                <li><a href="#Kegemaran">Kegemaran</a></li>
                <li><a href="#Keseharian">Keseharian</a></li>
            </ul>
        </div>
    </nav>
    <section class="color" id="Tentang-Saya">
    <aside class="deskripsi">
        <h1>Hi,Nama Saya <br> AHMAD SYARIFUDIN YUSUF</h1>
        <P>Saya adalah seorang Siswa SMK Negeri 1 Doko yang mengambil <br>
        bidang studi keahlian Teknik Komputer Jaringan dan Tekominikasi (TKJT)  </P>
        <Div class="BakatMinat">
            <P>Bakat saya ialah Menggambar dengan pensil. saya mulai menggambar
                dengan membuat sketsa gambar kemudian saya memberi garis yang tebal. <br>
                Agar gambar menjadi realistis saya mengunakan teknik 
                 arsir dan blending. </P>
                 <p>Saya berminat untuk dengan hal yang berbau teknologi
                    itulah mengapa saya belajar bahasa pemrogaman </p>
        </Div>
    </aside>
        <img class="aku" src="img/aku.jpg" alt="Foto Saya" >
    </section>
    <section class="color Kegemaran" id="Kegemaran">
        <h3 class="title">KEGEMARAN</h3>
        <div class="containerbox">
            <div class="box left">
                <h4>Menonton film & Series</h4>
                <p>Dari kisah-kisah epik yang memikat hati hingga karakter-karakter yang mendebarkan, serial film memanjakan penggemarnya dengan beragam emosi dan petualangan yang tak terduga.</p>
            </div>
            <div class="box mid">
                <h4>Bermain Game Setrategi</h4>
                <p>Bermain game strategi tidak hanya menghibur, tetapi juga mengasah pikiran. 
                Dalam dunia virtual yang penuh tantangan, pemain diajak untuk merencanakan,
                 mengambil keputusan, dan menyesuaikan strategi dalam waktu yang singkat. Ini adalah latihan mental yang sempurna yang memperkuat kemampuan analitis dan pemecahan masalah.</p>
            </div>
            <div class="box right">
                <h4>Belajar Hal baru</h4>
                <p>Belajar hal baru adalah proses yang tak pernah berakhir dan merupakan
                     bagian penting dari pertumbuhan pribadi. Dengan belajar, kita tidak hanya
                      meningkatkan diri kita sendiri, tetapi juga meningkatkan potensi kita untuk memberikan
                       kontribusi positif kepada masyarakat.</p>
        </div>
         </div>
    </section>
        <div class="blank">
        </div>
        <article class="Keseharian" id="Keseharian">
        <h3>KESEHARIAN</h3>
            <P>Saya biasanya memulai aktivitas dengan bangun tidur kemudian mengambil air wudhu untuk
            salat subuh. Kemudian saya mulai mandi, memakai seragam, dan menyiapkan apa saja yang 
            perlu dibawa kesekolah pada pukul 05.15 dan setelah itu saya berangkat sekitar pukul 06.00.
            Sesampainya di sekolah biasanya saya meletakkan tas di bangku menegah atau agak depan. <br>
            Saat waktu jam Pembelajaran saya mengikuti sesuai dengan jadwal seperti yang sudah di
            jadwalkan. Saya berusaha untuk meraih nilai sebaik mungkin walaupun terkadang hasilnya 
            tidak sesuai 
            dengan apa yang saya inginkan. Pada saat istirahat saya biasanya membeli makanan dan minuman.
            Dan di istirahat kedua saya melaksanakan salat dzuhur di awal waktu.</P>
            <p>Saya pulang pada pukul 15.20 dan sampai dirumah pada pukul lebih 16.00. Saat pulang
            seko>lah dirumah saya beristirahat sejenak. Setelah itu pada waktu sore saya mandi 
            kemudian mendirika  salat ashar. Kemudian say pergi kemasjid untuk melaksanakan salat 
            maghrib. Setelah itu saya biasanya mengaji sembari menuggu waktu isyak tiba. Saya pulang 
            setelah melaksanakan salat isyak dan kemudian saya mengerjakan PR dirumah dan saya tidur 
            pukul 21.30.</p>
            <p>Pada setiap sabtu biasanya saya menyempatkan waktu untuk ikut klub Bahasa inggris untuk 
            melatih kemampuan Bahasa inggris saya yang dimana saya 
            cukup bagus dalam Bahasa inggris. Dan pada minggunya saya sebisa mungkin untuk bersantai 
            agar tidak lelah untuk melakukan kegiatan disekolah. Kegitan akhir pekan saya tergantung 
            juga pada PR.</p>
        </article>
    </section>
</body>
<div class="transsition"></div>
<footer>
    <div class="link">
        <ul>
            <li><a href="https://github.com/ASyusuff">Git Hub</a></li>
            <li><a href="https://youtube.com/@AhmadSyarifudinY?si=QQdUZDMYESDxUwNy">You Tube</a></li>
            <li><a href="https://www.instagram.com/a_syarif_uy?igsh=MTkxNjlsejU0Z29ncQ==">Instagram</a></li>
        </ul>
    </div>
    <div class="creator">
        <h5>Oleh Ahmad Syarifudin Yusuf. Tahun 2024 </h5>
    </div>
</footer>
</html>
