<template>
  <div style="background-color: white">
    <!-- META -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;1,100;1,300;1,400;1,500;1,700&display=swap"
      rel="stylesheet"
    />
    <!-- <link rel="stylesheet" href="~/assets/css/webkec.css" /> -->
    <!-- NAVBAR SATART -->

    <div id="navbar" style="position: fixed; width: 100%; z-index: 12">
      <b-navbar toggleable="lg" class="navbar-2">
        <b-navbar-brand href="./"
          ><img src="~/assets/img/CERDAS - IKHLAS -LUAS.png" alt="" height="50" width="300"/></b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item><NuxtLink :to="('profil')">Profil</NuxtLink></b-nav-item>
              <b-nav-item><NuxtLink :to="('galeri')">Galeri</NuxtLink></b-nav-item>
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <script src="https://static.elfsight.com/platform/platform.js" data-use-service-core defer></script>
    <div class="elfsight-app-7bdf5161-1708-4728-83d5-1f8745dd565d" data-elfsight-app-lazy></div>
    <!-- NAVBAR END -->

    <!-- BACK TO TOP -->
    <!-- <a href="#slider" id="myBtn" title="Go to top" style="scroll-behavior: auto"
      ><i class="fa-solid fa-angles-up"></i
    ></a> -->
    <!-- BACK TO TOP END -->

    <!-- HERO SECTION -->
    <div id="slider">
      <div class="slides">
        <div class="slider">
          <div class="image">
            <img src="~/assets/img/4.png"/>
          </div>
        </div>

        <div class="slider">          
          <div class="image">
            <img src="~/assets/img/2.png" />
          </div>
        </div>

        <div class="slider">         
          <div class="image">
            <img src="~/assets/img/5.png" />
          </div>
        </div>

        <div class="slider">         
          <div class="image">
            <img src="~/assets/img/1.png" />
          </div>
        </div>

        <div class="slider">         
          <div class="image">
            <img src="~/assets/img/3.png" />
          </div>
        </div>
      </div>
      <div class="switch">
        <ul>
          <li>
            <div class="on"></div>
          </li>
          <li></li>
          <li></li>
          <li></li>         
        </ul>
      </div>
    </div>
    <!-- HERO SECTION END-->

    <!-- PROFIL START -->
    <div class="profil">
      <b-tabs content-class="mt-3" justified>
        <!-- profil Pesantren -->
        <b-tab title="Profile Pesantren" class="tabs" active>
          <h2>Ponpes<span> Manba’ul Hisan</span></h2>

          <!-- <p>
            - Pesantren Salaf, Pesantren Salafi, atau Pesantren Salafiyah adalah sebutan bagi pondok pesantren yang mengkaji kitab-kitab kuning. Pesantren salaf identik dengan pesantren tradisional yang berbeda dengan pesantren modern dalam hal metode pengajaran dan infrastrukturnya.
          </p> -->

          <div class="tabwil">
            <div class="batwil">
              <h5></h5>
              <p>
                Pondok pesantren manbaul hisan adalah lembaga pendidikan islam swasta di rintis sejak 2016 di dirikan pondok pesantren pada tanggal 25 mei 2016 oleh KH. Ahmad Yusin Al-haqiqi dengan sistem kurikulum formal dan non-formal dan selalu mengedepankan kitab kuning klasik pondok pesantren manbaul hisan terletak di kaumpandak Rt02/12 Kel. Karadenan Kec. Cibinong Kab. Bogor Jawa barat ,Lokasi pesantren sangat menguntungkan di dekat kota yang mana hal hal tersebut memudahkan komunikasi baik dengan instansi pemerintah maupun masyarakat luas dengan di dukung lingkunagn yang asri ponpes manbaul hisan berusaha mencetak kader-kader generasi yang memiliki jiwa keikhlasan,kesederhanaa,kemandirian,ukhuwah islamiah,keluasan berpikir secara modern dan tidak anti kritik, dan berperilaku atas dasar Al-qur'an, Sunah Rasul dan Ijma para ulama ahli sunnah wal jamaah, dalam rangka untuk meningkatkan taqwa kepada Allah Swt
              </p>

              <p>
              Pengasuh Pondok Pesantren Manba'ul Hisan <br> - KH. Ahmad Yusin haqiqi <br> - Umi Hj. Enok Omah Hayati <br> 
              </p>

              <p>
                Pembimbing Pondok Pesantren Manba'ul Hisan <br> - Ustadz Ahmad Haqiqi S.E <br> - Ustadzah Robiatun Nidhomiyah S.Pd
              </p> 

              <p>
                Pengajar Pondok Pesantren Manba’ul Hisan <br> - Ustadz Mansyuri <br> - Ustadz Syafikul Cholqi <br> - Ustadz Wahyu Nugraha <br> - Ustadz Dede Mubarok <br> - Ustadz Mohammad Ilham
              </p>
            
            </div>
          </div>
        </b-tab>

        <!-- Visi dan Misi -->
        <b-tab title="Visi dan Misi">
          <h2>Visi <span>dan</span> Misi</h2>
          <div class="vs">
            <div class="visi">
              <h5>Visi :</h5>
              <p>
                "Visi dari Ponpes Manba’ul Hisan adalah Mewujudkan Insan yang
                bertaqwa, berakhlaqul karimah, kuat, mandiri, dan berintelektual."
              </p>
            </div>

            <div class="misi">
              <h5>Misi :</h5>
              <p>
                1. Meneruskan semangat belajar dan pengamalan sesuai dengan ajaran
                ahlussunah wal jama’ah dan Ulama salafussholih.
              </p>

              <p>2. Membina budaya keshalihan baik individu maupun sosial dan asketisme
                intelektual dikalangan santri dan masyarakat.</p>

              <p>
                3. Mengembangkan, dan melestarikan Ilmu-ilmu agama Islam klasik yang
                tertuang dalam kitab kuning maupun litelatur-litelatur modern.
              </p>
            </div>
          </div>
        </b-tab>

        <!-- Data Pengajar -->
        <!-- <b-tab title="Data Pengajar">
          <h2>Data <span>Pengajar</span></h2>
          <div class="table">
              <b-table
                striped
                hover
                :items="items"
                :fields="fields"
                outlined
              ></b-table>
            </div>
        </b-tab> -->

        <!-- struktur organisasi -->
        <b-tab title="Struktur Organisasi">
          <h2>Struktur <span>Organisasi</span></h2>
          <div class="img-so">
            <img
              src="~/assets/img/MH ST.png"
              alt="Struktur Organisasi Gambar"
            />
          </div>
        </b-tab>
      </b-tabs>
    </div>
    <!-- PROFIL START END -->

    <!-- FOOTHER -->
    <footer>
      <div class="all-footer">
        <div class="footer-1">
          <div class="foot-cont">
            <i class="fa-solid fa-envelope fa-xl"></i>
            <h3>KONTAK KAMI</h3>
          </div>
          <div class="foot-almt" style="margin-top: 20px">
            <h5>Alamat Pondok Pesantren :</h5>
            <p style="margin-bottom: 20px; font-size: 14px">
              Jl. Karadenan Kaumpandak Cibinong Bogor, Bogor, Indonesia
            </p>
          </div>

          <div class="foot-almt" style="margin-top: 30px">
            <h5>Email :</h5>
            <p style="margin-bottom: 20px; font-size: 14px">
              kec.bout@kotabogor.go.id
            </p>
          </div>

          <div class="foot-almt" style="margin-top: 30px">
            <h5>No Telopn :</h5>
            <p style="margin-bottom: 20px; font-size: 14px">+62895613170166</p>
          </div>
        </div>
        <div class="line"></div>
        <div class="sosmed">
          <a href="https://www.instagram.com/manbaulhisan.official?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw=="> <i class="fa-brands fa-instagram fa-xl"></i></a>
          <!-- <a href="#"> <i class="fa-brands fa-x-twitter fa-xl"></i></a> -->
          <a href="https://www.facebook.com/ponpesmanbaulhisan"> <i class="fa-brands fa-facebook fa-xl"></i></a>
          <a href="#"> <i class="fa-brands fa-youtube fa-xl"></i></a>
        </div>
        <div class="copyright">
          
          <span class="text-muted d-block text-center text-sm-left d-sm-inline-block">Copyright © 2024 Ponpes Manba'ul Hisan</span>
					<span class="float-none float-sm-right d-block mt-1 mt-sm-0 text-center developer">Developed by MH Tech</span>
        </div>
      </div>
    </footer>
    <!-- FOOTHER END -->
  </div>
</template>

<style>
body {
  font-family: "Roboto", sans-serif;
  scroll-behavior: smooth;
}

/* BACK TO TOP  */
#myBtn {
  /* Hidden by default */
  position: fixed; /* Fixed/sticky position */
  bottom: 20px; /* Place the button at the bottom of the page */
  right: 30px; /* Place the button 30px from the right */
  z-index: 9999999; /* Make sure it does not overlap */
  border: 1px solid #3375cc; /* Remove borders */
  /* outline: none;  */
  background-color: rgba(0, 4, 244, 0); /* Set a background color */
  color: #3375cc; /* Text color */
  cursor: pointer; /* Add a mouse pointer on hover */
  padding: 10px 15px 10px 15px; /* Some padding */
  border-radius: 50px; /* Rounded corners */
  font-size: 18px; /* Increase font size */
  scroll-behavior: auto;
}

#myBtn:hover {
  background-color: #3375cc; /* Add a dark-grey background on hover */
  color: white;
  scroll-behavior: smooth;
}

/* NAVBAR */
#navbar {
  color: black;
  font-weight: bold;
  background-color: white;
  text-decoration: none;
}


.navbar-2 {
  padding: 5px 60px 5px 60px;
}

/* HERO SECTION */
#slider {
  width: 100%;
  height: 500px;
  padding-top : 30px;
  position: relative;
  overflow: hidden;
}
@keyframes load {
  from {
    left: -100%;
  }
  to {
    left: 0;
  }
}
.slides {
  width: 400%;
  height: 100%;
  margin-top: 20px;
  position: relative;
  -webkit-animation: slide 30s infinite;
  -moz-animation: slide 30s infinite;
  animation: slide 30s infinite;
}
.slider {
  width: 25%;
  height: 100%;
  float: left;
  position: relative;
  z-index: 1;
  overflow: hidden;
}
.slide img {
  width: 100%;
  height: 100%;
}
.slide img {
  width: 100%;
  height: 10%;
}
.image {
  width: 100%;
  height: 100%;
}
.image img {
  width: 100%;
  height: 100%;
}

.ml-auto{
  text-decoration: none;
}

/* Legend */
.legend {
  border: 500px solid transparent;
  border-left: 800px solid #3574cc2b;
  border-bottom: 0;
  position: absolute;
  bottom: 0;
}

/* Contents */
.content {
  width: 100%;
  height: 100%;
  position: absolute;
  overflow: hidden;
}
.content-txt {
  width: 400px;
  height: 150px;
  float: left;
  position: relative;
  top: 50px;
  -webkit-animation: content-s 7.5s infinite;
  -moz-animation: content-s 7.5s infinite;
  animation: content-s 7.5s infinite;
}
.content-txt h1 {
  text-transform: uppercase;
  font-size: 24px;
  color: #1eb355;
  text-align: left;
  margin-left: 30px;
  padding-bottom: 10px;
  font-weight: bold;
}

.content-txt h1 span {
  color: #1eb355;
  font-weight: bold;
}

/* .content-txt h3 {
  text-transform: uppercase;
  font-size: 18px;
  color: black;
  text-align: left;
  margin-left: 30px;
  padding-bottom: 10px;
  font-weight: bold;
} */

.content-txt p {
  font-weight: normal;
  font-size: 14px;
  font-style: italic;
  font-weight: bold;
  color: #fff;
  text-align: left;
  margin-left: 30px;
}

/* Switch */
.switch {
  width: 120px;
  height: 10px;
  position: absolute;
  bottom: 50px;
  z-index: 99;
  left: 30px;
}
.switch > ul {
  list-style: none;
}
.switch > ul > li {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #333;
  float: left;
  margin-right: 5px;
  cursor: pointer;
}
.switch ul {
  overflow: hidden;
}

.on {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  background: #3375cc;
  position: relative;
  -webkit-animation: on 30s infinite;
  -moz-animation: on 30s infinite;
  animation: on 30s infinite;
}

/* Animation */
@-webkit-keyframes slide {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: -100%;
  }
  46% {
    margin-left: -100%;
  }
  50% {
    margin-left: -200%;
  }
  71% {
    margin-left: -200%;
  }
  75% {
    margin-left: -300%;
  }
  96% {
    margin-left: -300%;
  }
}
@-moz-keyframes slide {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: -100%;
  }
  46% {
    margin-left: -100%;
  }
  50% {
    margin-left: -200%;
  }
  71% {
    margin-left: -200%;
  }
  75% {
    margin-left: -300%;
  }
  96% {
    margin-left: -300%;
  }
}
@keyframes slide {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: -100%;
  }
  46% {
    margin-left: -100%;
  }
  50% {
    margin-left: -200%;
  }
  71% {
    margin-left: -200%;
  }
  75% {
    margin-left: -300%;
  }
  96% {
    margin-left: -300%;
  }
}

@-webkit-keyframes content-s {
  0% {
    left: -420px;
  }
  10% {
    left: 0px;
  }
  30% {
    left: 0px;
  }
  40% {
    left: 0px;
  }
  50% {
    left: 0px;
  }
  60% {
    left: 0px;
  }
  70% {
    left: 0;
  }
  80% {
    left: -420px;
  }
  90% {
    left: -420px;
  }
  100% {
    left: -420px;
  }
}
@-moz-keyframes content-s {
  0% {
    left: -420px;
  }
  10% {
    left: 0px;
  }
  30% {
    left: 0px;
  }
  40% {
    left: 0px;
  }
  50% {
    left: 0px;
  }
  60% {
    left: 0px;
  }
  70% {
    left: 0;
  }
  80% {
    left: -420px;
  }
  90% {
    left: -420px;
  }
  100% {
    left: -420px;
  }
}
@keyframes content-s {
  0% {
    left: -420px;
  }
  10% {
    left: 20px;
  }
  15% {
    left: 0px;
  }
  30% {
    left: 0px;
  }
  40% {
    left: 0px;
  }
  50% {
    left: 0px;
  }
  60% {
    left: 0px;
  }
  70% {
    left: 0;
  }
  80% {
    left: -420px;
  }
  90% {
    left: -420px;
  }
  100% {
    left: -420px;
  }
}

@-webkit-keyframes on {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: 15px;
  }
  46% {
    margin-left: 15px;
  }
  50% {
    margin-left: 30px;
  }
  71% {
    margin-left: 30px;
  }
  75% {
    margin-left: 45px;
  }
  96% {
    margin-left: 45px;
  }
}

@-moz-keyframes on {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: 15px;
  }
  46% {
    margin-left: 15px;
  }
  50% {
    margin-left: 30px;
  }
  71% {
    margin-left: 30px;
  }
  75% {
    margin-left: 45px;
  }
  96% {
    margin-left: 45px;
  }
}

@keyframes on {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: 15px;
  }
  46% {
    margin-left: 15px;
  }
  50% {
    margin-left: 30px;
  }
  71% {
    margin-left: 30px;
  }
  75% {
    margin-left: 45px;
  }
  96% {
    margin-left: 45px;
  }
}

/* PROFIL STYLE */
.profil {
  margin-top: 30px;
  font-weight: 600;
  padding: 50px;
  /* height: 1000px; */
}

/* profil kec */

.tabs h2 {
  text-align: center;
  margin-top: 50px;
  font-size: 25px;
}

.tabs p {
  padding: 10px 40px 10px 20px;
  font-weight: 400;
}

.tabwil {
  font-family: arial, sans-serif;
  /* border-collapse: collapse; */
  text-align: center;
  display: flex;
  justify-content: center;
  gap: 20px;
}

.batwil h5 {
  text-align: center;
  margin-bottom: 7px;
}

.batwil p {
  border-bottom: 1px solid black;
  text-align: start;
}

.inov {
  margin-top: 50px;
}

/* visi misi  */

.vs {
  display: flex;
  gap: 15px;
  justify-content: center;
  margin-top: 20px;
}

.misi p {
  border-bottom: 1px solid black;
}

.vs-img {
  margin-top: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

/* data pejabat */
.table{
  width: 100%;
}

/* struktur organisasi */
.img-so {
  margin: 40px 200px 20px 200px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.admin-kec-img img {
  width: 100%;
}

.admin-kota-img img {
  width: 100%;
}

/* FOOTER */

.all-footer {
  background-color: #145858;
  margin-top: 80px;
  padding: 50px 80px 10px 80px;
  text-align: center;
  color: rgba(255, 255, 255, 0.4);
}

.foot-cont {
  display: flex;
  justify-content: center;
  color: black;
  gap: 13px;
}

.foot-cont h3 {
  font-size: 20px;
}

.foot-cont h5 {
  color: black;
}

.foot-cont i {
  padding-top: 10px;
}

.footer-1 p {
  font-size: 15px;
  color: black;
  font-style: italic;
  margin-top: 10px;
}

.line {
  display: flex;
  justify-content: center;
  width: 100%;
  height: 1px;
  background-color: black;
  text-align: center;
  margin-top: 40px;
}

.sosmed {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 30px;
}

.sosmed a {
  color: black;
}

.sosmed a i:hover {
  font-size: 30px;
  color: #3575cc;
}

.copyright {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 13px;
  text-align: center;
  padding: 5px;
  padding-top: 25px;
}

/* RESPONSIVE MOBILE */

@media (max-width: 550px) {
  .navbar-2 {
    padding: 20px;
  }

  #slider {
    width: 100%;
    height: 350px;
    position: relative;
    overflow: hidden;
  }

  .legend {
    display: none;
  }

  .content {
    display: none;
  }
  /* PROFIL STYLE */
  .profil {
    width: 100%;
    margin-top: 20px;
    padding: 30px;
  }

  .tabwil {
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .table {
    width: 100%;
    justify-content: center;
    text-align: center;
  }

  .vs {
    display: flex;
    flex-direction: column;
  }

  .img-so {
    margin: 15px 1px 1px 1px;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .all-map {
    display: flex;
    justify-content: center;
    flex-direction: column;
  }
}
</style>

<!-- --------- -->
<!--ALL SCRIPT -->
<!-- --------- -->

<!-- script slide card -->
<script>
const prev = document.getElementById("prev-btn");
const next = document.getElementById("next-btn");
const list = document.getElementById("item-list");

const itemWidth = 150;
const padding = 10;

prev.addEventListener("click", () => {
  list.scrollLeft -= itemWidth + padding;
});

next.addEventListener("click", () => {
  list.scrollLeft += itemWidth + padding;
});
</script>
<!-- script slide card end -->

<!-- script vue -->
<script>
import Slider from "@/components/web/slider.vue";

export default {
  components: {
    Slider,
  },

  layout: "empty",

  //meta
  head() {
    return {
      title: "PROFIL | PP. Manba'ul Hisan",
    };
  },

  data() {
    return {
      // Note `isActive` is left out and will not appear in the rendered table
      fields: ["No", "Nama_Pengajar","Mengajar"],
      items: [
        {
          isActive: true,
          No: "1",
          Nama_Pengajar: "KH. Yusin Haqiqi",
          Mengajar: "Kitab Kuning",
        },
        {
          isActive: true,
          No: "2",
          Nama_Pengajar: "Ust. Ahmad Haqiqi",
          Mengajar: "Kitab Kuning",
        },
        {
          isActive: true,
          No: "3",
          Nama_Pengajar: "Ust. Syafikul Kholqi",
          Mengajar: "Kitab Kuning",
        },
        {
          isActive: true,
          No: "4",
          Nama_Pengajar: "Ust. Dede Mubarok",
          Mengajar: "Kitab Kuning",
        },
      ],
    };
  },
  

  // data() {
  //   return {
  //     daftar: [
  //       { age: 40, first_name: "Dickerson", last_name: "Macdonald" },
  //       { age: 21, first_name: "Larsen", last_name: "Shaw" },
  //       { age: 89, first_name: "Geneva", last_name: "Wilson" },
  //       { age: 38, first_name: "Jami", last_name: "Carney" },
  //     ],
  //   };
  // },

  // data() {
  //   return {
  //     value: "",
  //     context: null,
  //   };
  // },
  // methods: {
  //   onContext(ctx) {
  //     this.context = ctx;
  //   },
  // },
};
</script>
<!-- script end -->
