<template>
  <section class="profil">
        <div class="title">
            <h3>PROFIL</h3>
        </div>
        <div class="content">
            <p>Desa Siundol Dolok terletak di Kec. Sosopan Kab. Padang Lawas, yang memiliki
                penduduk ... jiwa serta mata pencarian di sektor pertanian dan perkebunan karet.
                Untuk wilayah memiliki luas ... & dalam meningkatkan kualitas pendapatan Desa.
                saat ini, masyarakat sedang fokus ke dalam sektor ekonomi kreatif dengan harapan
                meningkatkan tarap pendapatan masyarakat. sementara, dalam sektor perkebunan terus
                di laksanakan pembukaan jalan sebagai jalan utama bagi masyarakat untuk tujuan 
                memudahkan akses dalam mengelola perkebunan terutama karet dan kelapa sawit
            </p>
        </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
    .profil{
        margin: 30px auto 40px;
        max-width: 850px;
        text-align: center;
    }
    .content{
        font-size: 20px;
    }
    @media only screen and (max-width: 680px) {
        .profil .content p{
            max-width: 100%;
            font-size: 14px;
            text-align: justify;
            padding: 0px 20px;
            

        }
       /*  .content p {
            font-size: 18px;
            width: 100%;
            margin: 0px 0px;
            padding: 0px 20px;
            
            

        } */
    }

</style>