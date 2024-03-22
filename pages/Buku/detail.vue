<template>
  <div class="bg">
    <div class="row">
      <div class="col-lg-12">
        <div class="icon mt-4">
          <nuxt-link to="/Buku/">
          </nuxt-link>
          <h2 class="text-center my-4">Yang Telah Lama Pergi</h2>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-4 text-white d-flex flex-column justify-contant-center">
        <h4>Detail Buku:</h4>
        <h5>Pengarang: Tere Liye</h5>
        <h5>Jumlah Halaman: 444</h5>
        <h5>Tanggal Terbit: 28 Agustus 2023</h5>
        <h5>Penerbit: Sabaghrib</h5>
      </div>
      <div class="col-4 d-flex flex-column justify-content-center align-items">
        <div class="mb-5">
          <div class="card-body">
            <img src="~/assets/img/12.jpg" class="im-thumbnail" />
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
          Dalam perjalanan ini, tokoh utama bertemu dengan berbagai karakter yang menginspirasi dan membantunya memahami dirinya sendiri serta mengatasi rasa sakit yang dirasakannya. Dia mungkin menemukan kekuatan dalam kenangan tentang
          orang yang telah pergi, atau dia mungkin menemukan kedamaian dalam menerima kenyataan yang tidak bisa diubah. adalah sebuah kisah tentang bagaimana seseorang menghadapi kehilangan dan menemukan cara untuk melanjutkan hidup
          meskipun rasa sakit yang mendalam. Ini adalah kisah tentang harapan, kesembuhan, dan kekuatan dalam menghadapi tantangan hidup yang pahit.
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
