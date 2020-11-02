<template>
  <section class="profil">
        <div class="title">
            <h3>PROFIL</h3>
        </div>
        <div class="content">
            <p>Desa Siundol Dolok didirikan sekitar tahun 1600 oleh <b>Japanongonan Hasibuan</b> yang berasal
                dari Desa <i>Paringgonan Julu Luhut Paringgonan</i>, penamaan Desa Siundol Dolok berasal dari kata Siundol
                yang artinya <i>"Dangkal"</i> dan kata Dolok yang artinya <i>"di Atas"</i>. Dengan demikian 
                Siundol Dolok dapat diartikan <b>"di atas desa yang ada di sekitarnya"</b>.
                Terletak di Kec. Sosopan Kab. Padang Lawas, yang memiliki
                penduduk ... jiwa serta mata pencarian di sektor pertanian dan perkebunan
                Untuk wilayah memiliki luas ... 
            </p>
        </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
    h3{
        text-align: center;
    }
    .profil{
        margin: 30px auto 40px;
        max-width: 1000px;
        text-align: justify;
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