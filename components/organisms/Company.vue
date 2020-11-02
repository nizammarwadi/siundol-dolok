<template>
    <footer>
        <section class="contact">
            <div class="container">
                <div class="row">
                    <div class="col-md-4 col-sm-6 about-us">
                        <div class="about-us-title">
                            <h4>Tentang kami</h4>
                        </div>
                        <p>Layanan Penjualan Madu Asli Melalui Online. Madu Langsung kami ambil dari Hutan</p>
                        <div class="about-us-media">                     
                            <a href="https://www.facebook.com/nizam.marwadi" target="_blank"><img src="../assets/image/icon fb.png" style="width:40px"></a>
                            <a href="https://www.instagram.com/nizammarwadi/?hl=en" target="_blank"><img src="../assets/image/icon ig.png" style="width:40px"></a>
                            <a href="https://www.facebook.com/nizam.marwadi" target="_blank"><img src="../assets/image/icon fb.png" style="width:40px"></a>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 contact-us">
                        <div class="contact-us-title">
                            <h4 style="list-style-type: none;">kontak kami</h4>
                        </div>
                        <li class="phone"><a href="https://wa.me/6282362574353" target="_blank">+62823-6257-4353</a></li>
                        <li style="list-style-type: none;">Jl. Prambanan No. 25 Medan Tembung</li>
                        <li style="list-style-type: none;">cs <a href="https://www.instagram.com/nizammarwadi/?hl=en" target="_blank">@madustore</a></li><br>
                        <li style="list-style-type: none;"><b>Jam Operasional</b></li>
                        <li style="list-style-type: none;">Setiap Hari :</li>
                        <li style="list-style-type: none;">08.00 - 20.00</li>
                    </div>
                    <div class="col-md-4 col-sm-6 email-us">
                        <div class="email-us-title">
                            <h4>Kirim Email</h4>
                        </div>
                        <p>Kirim Email Anda di bawah ini, untuk mendapatkan informasi lebih lanjut tentang produk dan layanan kami</p>
                        <form>
                            <div class="form-group">
                                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="your email">
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>
        <section class="patent">
            <p>Copyright ©2020 madustore.id</p>
        </section>
    </footer>
    
</template>

<script>
export default {

}
</script>

<style>
    .form-group{
        width: 70%;
        margin: 0px auto;
    }
    .form-control{
        border: 1px transparent #bbb;
        height: 45px;
        border-radius: 17px;
        background-color: transparent;
    }
    .contact{
        background-color: #131313;
        color: #bbb;
        padding: 120px 0px;

    }
    .about-us, .contact-us, .email-us{
        text-align: center;
    }
    h4{
        color: #fff;
    }
    .about-us .about-us-title h4::after {
        content: '_____';
        display: block;
        color: #4abeed;
        font-size: 30px;
        margin: -10px 0px 15px 0px;
    }
    .contact-us .contact-us-title h4::after{
        content: '_____';
        display: block;
        color: #4abeed;
        font-size: 30px;
        margin: -10px 0px 15px 0px;
    }
    .email-us .email-us-title h4::after{
        content: '_____';
        display: block;
        color: #4abeed;
        font-size: 30px;
        margin: -10px 0px 15px 0px;
    }
    .phone{
        list-style-type: none;
        
    }
    .patent{
        /* border-top: 1px solid #bbb; */
        background-color: #0B090A;
        text-align: center;
        height: 50px;
    }
    .patent p{
        padding: 12px 0px;
        color: #bbb;
    }
    @media(max-width: 578px) {
        .contact-us, .email-us{
            margin-top: 30px;
        }
    }

</style>