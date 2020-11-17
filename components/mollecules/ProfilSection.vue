<template>
  <section id="profil" class="profil">
        <div class="title">
            <h3>PROFIL</h3>
        </div>
        <div class="content">
            <p>Desa Siundol Dolok didirikan sekitar tahun 1600 oleh <b>Japanongonan Hasibuan</b> yang berasal
                dari Desa <i>Paringgonan Julu Luhut Paringgonan</i>, penamaan Desa Siundol Dolok berasal dari kata Siundol
                yang artinya <i>"Dangkal"</i> dan kata Dolok yang artinya <i>"di Atas"</i>. Dengan demikian 
                Siundol Dolok dapat diartikan <b>"di atas desa yang ada di sekitarnya"</b>.
                Terletak di Kec. Sosopan Kab. Padang Lawas. Luas pemukiman 2ha memiliki
                penduduk 352 jiwa serta mata pencaharian di sektor pertanian dan perkebunan
            </p>
        </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
    .profil .title h3{
        text-align: center;
        font-weight: bold;
        font-size: 27px;
        padding: 10px 0px;
    }
    .profil{
        margin: 0px auto;
        padding: 70px 0px;
        text-align: center;
    }
    .content p{
        font-size: 18px;
        text-align: center;
        width: 1000px;
        margin: 0px auto;
        font-weight: bold;
    }
    @media only screen and (max-width: 992px) {
        .profil .content p{
            max-width: 90%;
            font-size: 15px;
            font-weight: bold;
            text-align: center;
        }
        .profil {
            padding: 70px 0px 0px;
        }
    }

</style>