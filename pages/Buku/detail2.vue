<template>
    <div class="bg">
      <div class="row">
        <div class="col-lg-12">
          <div class="icon mt-4">
            <nuxt-link to="/Buku/">
            </nuxt-link>
            <h2 class="text-center my-4">Mariposa</h2>
          </div>
        </div>
      </div>
  
      <div class="row">
        <div class="col-4 text-white d-flex flex-column justify-contant-center">
          <h4>Detail Buku:</h4>
          <h5>Pengarang: Luluk HF</h5>
          <h5>Jumlah Halaman: 396.0</h5>
          <h5>Tanggal Terbit: 4 Februari 2022</h5>
          <h5>Penerbit: Coconut Books</h5>
          <h5>Penulis: Haykal Bukhari</h5>
        </div>
        <div class="col-4 d-flex flex-column justify-content-center align-items">
          <div class="mb-5">
            <div class="card-body">
              <img src="~/assets/img/mariposa.jpg" class="im-thumbnail" />
            </div>
          </div>
        </div>
        <div class="col-4 d-flex-column justify-content-center align-items-center">
          <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Meminjam</button>
          <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Membaca</button>
        </div>
      </div>
  
      <div class="row text-white">
        <div class="col">
          <h4 class="text-white">Deskripsi</h4>
          <h5 class="text-white">
            Mariposa adalah sebuah novel fiksi romance. Dalam bahasa Spanyol, Mariposa dapat diartikan sebagai kupu-kupu, dan kupu-kupu sendiri memiliki filosofi “semakin dikejar, akan semakin menjauh, tapi jika dibiarkan, maka akan semakin mendekat.” filosofi itulah yang kemudian menjadi ide cerita novel Mariposa
          </h5>
        </div>
      </div>
    </div>
  </template>
  
  <style sckoped>
  .bg {
    background-image: url(assets/img/yy.webp);
    
  }
  h2 {
    color: rgb(0, 0, 0);
  }
  </style>
  