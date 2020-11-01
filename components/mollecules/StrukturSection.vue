<template>
    <section class="struktur">
        <div class="title">
            <h3>PEMERINTAHAN DESA</h3>
        </div>
        <div class="content">
            <img src="~/assets/image/struktur.jpg" class="image" alt="#">
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
    /* .struktur {
        margin-top: 70px;
    } */
    .struktur {
        margin: 10px auto 20px ;
        max-width: 100%;
        text-align: center;
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