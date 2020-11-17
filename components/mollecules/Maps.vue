<template>
    <div class="maps">
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d60666.10965668447!2d99.56897692090689!3d1.157285667002564!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x302b8af3a3c097fd%3A0x19fb294f4dfef94b!2sSiundol%20Dolok%2C%20Sosopan%2C%20Padang%20Lawas%20Regency%2C%20North%20Sumatra!5e1!3m2!1sen!2sid!4v1605581998066!5m2!1sen!2sid" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
    </div>
</template>

<script>
export default {
}
</script>

<style>
    .maps {
        text-align: center;
        padding: 80px 0px 40px 0px;
    }
    .maps iframe {
       width: 400px;
       height: 350px;
    }
    @media(max-width: 768px) {
        .maps iframe {
            width: 100%;
            padding: 30px 30px 0px;
        }
    }

</style>