<template>
    <div>
<div class="row">

        <div class="col-md-12">
            <div id="infoatas">
                <i class="bi bi-calendar"> Senin - Jumat (09.00-18.00 WIB)</i>
                <i class="bi bi-chat-right-fill"> +62811 1122 015</i>
                <i class="bi bi-envelope"> cs@triasse.com</i>
            </div>
        </div>
    </div>



    <!-- LOGO TRIASSE ? NAVBAR -->
    <div id="logobar" class="container-fluid" >

        <div class="row">
            <div class="col-md-6">
                <img class="posisilogotri" src="../assets/img/img-logo2x.png" width="130" height="60" alt="">

            </div>


            <div class="col-md-6">

                <nav class="navbar navbar-expand-lg navbar-light ">

                    <div id="navbarNav" class="collapse navbar-collapse" >
                        <ul class="navbar-nav">
                            <li class="nav-item active">
                                <a class="nav-link" href="#">Paket Test Darah <span class="sr-only">(current)</span></a>
                            </li>
                            <li class="nav-item">
                                <a id="tmbolposisi2" class="nav-link" href="#">Laboratorium</a>
                            </li>
                            <li class="nav-item">
                                <a id="tmbolposisi2" class="nav-link" href="#">Artikel</a>
                            </li>
                            <button id="tmbolposisi" type="button" class="btn btn-primary btn-md" >Masuk</button>
                            <button id="tmbolposisi" type="button" class="btn btn-primary btn-md" >Daftar</button>

                        </ul>
                    </div>
                </nav>
            </div>


        </div>
    </div>

    <!-- BIG BANNER -->

    <div class="row">
        <div class="col-lg-12">
            <div class="topbanner">
                <img src="../assets/img/img-big-banner@2x.jpg" alt="">

            </div>
        </div>
    </div>


    <!-- Pilih Jenis Pemeriksaan -->
    <div class="menupemeriksaan">
        <div class="container-fluid">
            <div class="row">
                <div id="bgpilihjenis" class="col-md-8" >
                    <h2 style="font-weight: bold;">Pilih Jenis Pemeriksaan</h2>
                    <h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</h5>
                </div>
                <div id="imgdoctor" class="col-md-4" >
                    <img src="../assets/img/img-doctor.svg" alt="">
                </div>
            </div>
            <!-- Option -->
            <div id="optionposisi2" class="row" >



                <div id="optionposisi" class="col-md-3" >
                    <label for="exampleFormControlSelect1">Pilih Provinsi</label>
                    <div class="input-group mb-2">
                        <div class="input-group-prepend">
                            <div class="input-group-text">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                        </div>

                        <select  id="exampleFormControlSelect1" class="form-control">
                            <option>Jawa Barat</option>
                            <option>DKI Jakarta</option>
                            <option>3</option>
                            <option>4</option>
                            <option>5</option>
                          </select>
                    </div>
                </div>

                <div class="col-md-3">
                    <label for="exampleFormControlSelect1">Kota/Kabupaten</label>
                    <div class="input-group mb-2">
                        <div class="input-group-prepend">
                            <div class="input-group-text">
                                <i class="fas fa-map-marked"></i>
                            </div>
                        </div>

                        <select id="exampleFormControlSelect1" class="form-control" >
                            <option>Jawa Barat</option>
                            <option>DKI Jakarta</option>
                            <option>3</option>
                            <option>4</option>
                            <option>5</option>
                          </select>
                    </div>
                </div>

                <div class="col-md-3">
                    <label for="exampleFormControlSelect1">Paket/Jenis Pemeriksaan</label>
                    <div class="input-group mb-2">
                        <div class="input-group-prepend">
                            <div class="input-group-text">
                                <i class="fas fa-stethoscope"></i>
                            </div>
                        </div>

                        <select id="exampleFormControlSelect1" class="form-control" >
                            <option>Jawa Barat</option>
                            <option>DKI Jakarta</option>
                            <option>3</option>
                            <option>4</option>
                            <option>5</option>
                          </select>
                    </div>
                </div>




            </div>
            <div class="col-md-12">
                <button id="tombolcari" type="button" class="btn btn-warning" >Cari Lab</button>

            </div>


        </div>
    </div>

    </div>
</template>