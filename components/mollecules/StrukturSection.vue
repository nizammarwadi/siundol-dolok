<template>
    <section class="struktur">
        <div class="title">
            <h3>PEMERINTAHAN DESA</h3>
        </div>
        <div class="content">
            <img src="~/assets/image/struktur desa.jpg" class="image" alt="#">
            <img src="~/assets/image/bpd.jpg" class="image" alt="#">
        </div>
       
    </section>
</template>

<script>
export default {

}
</script>

<style>
    .struktur {
        margin: 0px auto;
        padding: 70px 0px;
        max-width: 100%;
        text-align: center;
    }
    .struktur .title h3 {
        padding: 10px 0px;
        font-weight: bold;
        font-size: 27px;
    }
    .content img{
        margin-top: 10px;
        width: 650px;
        height: 450px;
    }
    @media (max-width: 992px) {
        .content img {
            height: 300px;
            width: 100%;
        }
        .struktur {
            padding: 0px 20px;
        }
    }
   /*  @media (min-width: 768px) {
        .struktur .row .image {
            width: 800px;
            height: 400px;
    }
    }
    @media (min-width: 992px) {
        .struktur .row .image {
            width: 800px;
            height: 400px;
    }
    }
    @media (min-width: 1200px) {
        .struktur .row .image {
            width: 800px;
            height: 400px;
    }
    } */
    
</style>