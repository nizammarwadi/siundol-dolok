<template>
    <section id="program" class="program bg-light">
        <div class="program-title text-center">
            <h2>PROGRAM</h2>
            <hr>
        </div>
        <div class="program-content">
            <div class="visi-content">
                <h4 class="title text-center">VISI</h4>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.  
                    quae est consequuntur eaque. Nemo amet quae est consequuntur eaque. consequuntur eaque
                </p>
            </div>
            <div class="misi-content">
                <h4 class="title text-center">MISI</h4>
                <ul>
                    <li>Ketuhanan yang maha esa</li>
                    <li>Kemanusian yang adil dan beradab</li>
                    <li>Persatuan Indonesia</li>
                    <li>Kerakyatan yang di pimpin oleh hikmat kebijaksanan dalam permusyawaratan/ perwakilan</li>
                    <li>Keadilan sosial bagi seluruh rakyat Indonesia</li>
                </ul>
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
</style>