<template>
    <section id="registrasi" class="registrasi">
        <div class="container">
            <div class="row">
                <div class="col text-center mb-4 mt-4">
                    <h2>REGISTRASI</h2>
                </div>
            </div>
            <div class="row justify-content-center">
                <!-- <div class ="col-md-4">
                    <div class="card text-white bg-primary mb-3" style="width: 350px;">
                        <div class="card-body text-center">
                            <h3 class="card-title">Kontak Kami</h3>
                            <h5 class="card-text">(082362574353)</h5>
                        </div>
                    </div>
                    <ul class="list-group">
                        <li class="list-group-item">Siundol Dolok Kec.Sosopan Kab. Padang Lawas / Jl. Lintas Sibuhuan - Sosopan - Padangsidempuan</li>
                        <li class="list-group-item">Nort Sumatera, Indonesia</li>
                    </ul>
                </div> -->
                <div class="col-md-6">
                    <form>
                        <div class="form-group">
                            <label for="nama">Nama</label>
                            <input type="text" class="form-control" id="nama" placeholder="Masukkan Nama">
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Masukkan Email">
                        </div>
                        <div class="form-group">
                            <label for="no.telp">No. Telp</label>
                            <input type="text" class="form-control" id="no.telp" placeholder="Masukkan No.Telp">
                        </div>
                        <div class="form-group">
                            <label for="pesan">Pesan</label>
                            <textarea name="pesan" id="pesan" class="form-control" placeholder="Masukkan Pesan"></textarea>
                        </div>
                        <div class="form-group flex-auto">
                            <button type="submit" class="btn btn-primary">submit</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
</section>
</template>

<script>
export default {

}
</script>

<style>
.registrasi {
    padding: 70px 0px;
}
.col h2 {
    font-weight: bold;
    font-size: 27px;
}
@media(max-width: 768px) {
    .registrasi {
        width: 80%;
        margin: 0px auto;
    }
}   

</style>