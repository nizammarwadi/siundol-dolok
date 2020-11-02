<template>
    <section id="program" class="program bg-light">
        <div class="program-title text-center">
            <h2>VISI DAN MISI</h2>
            <hr>
        </div>
        <div class="program-content">
            <div class="visi-content">
                <h4 class="title text-center">VISI</h4>
                <p><b><i>"Mewujudkan Masyarakat Desa Siundol Dolok Yang Sejahtera, Mandiri, Beriman, Cerdas, Beradat, Damai dan Harmonis"</i></b>
                </p>
            </div>
            <div class="misi-content">
                <h4 class="title text-center">MISI</h4>
                <ol>
                    <li>Meningkatkan Pendapatan Masyarakat Yang Mandiri</li>
                    <li>Meningkatkan Usaha Pertanian</li>
                    <li>Membuka Lapangan Kerja</li>
                    <li>Mewujudkan Pemerintahan Yang Bersih</li>
                    <li>Meningkatkan dan Mengelola Pendapatan Asli Daerah</li>
                </ol>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
    .program{
        padding: 20px 0px;
    }
    .program-content {
        display: flex;
        justify-content: space-around;
        margin: 0px auto;
        max-width: 70rem;
    }
    .visi-content{
        max-width: 450px;
    }
    .misi-content{
        max-width: 450px;
    }
    @media (max-width: 992px) {
        .program-content {
            display: block;
            max-width: 70%;
        }
    }
    @media (max-width: 992px) {
        p,li{
            font-size: 14px;
        }
    }
</style>