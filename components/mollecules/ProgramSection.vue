<template>
    <section id="program" class="program">
        <div class="program-title text-center">
            <h2>PROGRAM</h2>
        </div>
        <div class="program-content">
            <div class="visi-left">
                <h2>VISI</h2>
                <p>"Mewujudkan Masyarakat Desa Siundol Dolok Yang Sejahtera, Mandiri, Beriman, Cerdas, Beradat, Damai dan Harmonis"</p>
            </div>
            <div class="visi-right">
                <img src="~/assets/image/visi.svg">
            </div>
        </div>
        <div class="program-content">
            <div class="misi-left">
                <h2>MISI</h2>
                <ol>
                    <li>Meningkatkan Pendapatan Masyarakat Yang Mandiri</li>
                    <li>Meningkatkan Usaha Pertanian</li>
                    <li>Membuka Lapangan Kerja</li>
                    <li>Mewujudkan Pemerintahan Yang Bersih</li>
                    <li>Meningkatkan dan Mengelola Pendapatan Asli Daerah</li>
                </ol>        
            </div>
            <div class="misi-right">
                <img src="~/assets/image/bisnis.svg">
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
    .program-title h2 {
        margin-bottom: 30px;
    }
    .program{
        padding: 80px 0px;
        background-color: #f8f9fa;
    }
    .program-title h2 {
        font-weight: bold;
        font-size: 27px;
    }
    .program-content {
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: 0px auto;
        max-width: 70rem;
        padding: 120px 0px;
    }
    .program-content h2 {
        text-align: center;
        font-weight: bold;
        font-size: 27px;
    }
    .visi-left{
        max-width: 450px;
    }
    .visi-left p {
        font-size: 20px;
        font-weight: bold;
    }
    .visi-right img {
        max-width: 350px;
        border-radius: 90px 10px 20px 0px;
    }
    .misi-right img {
        max-width: 500px;
        padding-left: 120px;
    }
    .misi-left {
        max-width: 600px;
    }
    .misi-left ol li {
        font-weight: bold;
        font-size: 20px;
    }
    @media (max-width: 992px) {
        .program-content {
            display: block;
            width: 80%;
            padding: 0px 0px;
        }
        .visi-right img {
            width: 80%;
            margin: 20px auto 100px;
           margin-left: 30px;
            
        }
        .misi-right img {
            width: 100%;
            margin-top: 30px; 
            margin-left: 20px;
            padding: 0px 0px;
        }
        .visi-left p {
            width: 100%;
            text-align: center;
            padding: 0px 0px;
            font-size: 15px;
            font-style: italic;
        }
        .misi-left ol li {
            width: 100%;
            padding: 0px 0px;
            margin: 0px 0px;
        }
        .misi-left ol li {
            font-size: 15px;
        }
        .program-content h2 {
            text-align: center;
            font-size: 20px;
            font-weight: bold;
        }
    }
    
</style>