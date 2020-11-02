<template>
    <footer class="footer">
        <section class="contact">
            <div class="address">
                <div class="address-title">
                    <h2>Alamat</h2>
                    <p>
                        Pemerintah Desa Siundol Dolok<br>
                        Jl. Lintas Sosopan Desa Siundol Dolok<br>
                        Kecamatan Sosopan Kabupaten Padang Lawas, Sumatera Utara, Indonesia
                    </p>
                </div>
                <div class="address-image">
                    <h2>Media Sosial</h2>
                    <a href="https://www.instagram.com/nizammarwadi/?hl=en" target="_blank"><img src="~/assets/image/icon ig.png" alt="#"></a>
                    <a href="https://www.facebook.com/nizam.marwadi/" target="_blank"><img src="~/assets/image/icon fb.png" alt="#"></a>
                    <img src="~/assets/image/icon tw.png" alt="#">
                </div>
            </div>
                <div class="contact-phone">
                    <h2>Phone</h2>
                    <p><a href="https://wa.me/082166777234" target="_blank">0821-6677-7234 </a>| H. Raden Saleh Hasibuan,SH<br>
                    <a href="https://wa.me/082362574353" target="_blank">0823-6257-4353 </a>| H. Nizam M Hasibuan,S.Kom</p>
                </div>
                <div class="contact-email">
                    <h2>Email</h2>
                    <p>@adminsiundolok.com</p>
                </div>
        </section>
        <section class="patent">            
            <div class="copyright">
                <p>©Copyright 2020 SIUNDOL DOLOK. All right reserved. Crafted with love by Engineer</p>
            </div>     
        </section>
    </footer>
   
</template>

<script>
export default {

}
</script>

<style>
    .address{
        display: flex;
        justify-content: space-between;
        align-items: baseline;
    }
    .contact {
        background-color: #131313;
        padding: 20px 80px;
        color: #bbb;
        /* color: #333; */
        
    
    }
    .copyright {
        height: 45px;
        padding-top: 8px;
        margin-top: -1rem;
        color: white;
        text-align: center;
        font-size: 11px;
        background-color: #0B090A;
        font-style: italic;
       
    }
    .copyright p{
        margin-top: 5px;
    }
    .address img {
        width: 30px;
        height: 30px;
        object-fit: cover   ;
    }
    .address img:hover {
        width: 35px;
        height: 35px;
        
    } 
    @media (max-width: 768px) {
        .address{
            display: block;
            align-items: baseline;
            margin-bottom: 15px;
        }
        .contact{
            padding: 20px 10px;
            max-width: 100%;

        }
        .copyright p{
            max-width: 100%;
            text-align: center;
            font-size: 7px;
        
        }
        .contact h2{
            font-size: 23px;
        }
        .contact p{
            font-size: 14px;
        }
    }
        
        
    

</style>