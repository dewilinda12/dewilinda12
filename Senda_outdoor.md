<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.menu {
  float: left;
  width: 20%;
}
.menuitem {
  padding: 8px;
  margin-top: 7px;
  border-bottom: 1px solid #FFFAF0;
}
.main {
  float: left;
  width: 60%;
  padding: 0 20px;
  overflow: hidden;
}
.right {
  background-color: lightblue;
  float: left;
  width: 20%;
  padding: 10px 15px;
  margin-top: 7px;
}

@media only screen and (max-width:800px) {
  /* For tablets: */
  .main {
    width: 80%;
    padding: 0;
  }
  .right {
    width: 100%;
  }
}
@media only screen and (max-width:500px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;">

<div style="background-color:#008080;padding:15px;">
  <h1 style= "color: white">SENDA OUTDOOR</h1>
  <h3> Menjual perlengkapan outdoor</h3>
</div>

<div style="overflow:auto">
  <div class="menu">
    <div class="menuitem">BERANDA</div>
    <div class="menuitem">PROFILE</div>
    <div class="menuitem">DAFTAR PEGAWAI</div>
    <div class="menuitem">DATA BARANG</div>
    <div class="menuitem">DAFTAR PENGUJUNG</div>
  </div>

  <div class="main">
    <h2>WELLCOME TO SENDA OUTDOOR</h2>
    <p>Toko ini menyediakan berbagai macam perlengkapan outdoor yang anda perlukan ,banyak sekali berbagai jenis barang yang anda cari mulai dari tenda,carrier,nesting,sepatu dll.</p>
    <img src="pendaki.JPG" style="width:100%">
  </div>

  <div class="right">
    <h2>ALAMAT?</h2>
    <p>jl.jambu no 2kompleks transpamen abri, Gedong Meneng, Kec. Rajabasa, Kota Bandar Lampung, Lampung 35141.</p>
    <h2>email?</h2>
    <p>info@sendaoutdoor.ac.id.</p>
    <h2>Contact Person</h2>
    <p>08999678803</p>
  </div>
</div>


<div style="background-color:#008080;text-align:center;padding:10px;margin-top:7px;font-size:12px;"> @kendiloutdoor.ac.id.</div>
</body>
</html>
