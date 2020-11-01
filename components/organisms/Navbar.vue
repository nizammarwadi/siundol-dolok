<template>
  <div>
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <img class="navbar-brand palas" src="~/assets/image/padang-lawas.png" width="50px" height="60px">
            <div class="logo mr-auto">
                <label for="siundol" style="font-weight:bold">SIUNDOL DOLOK</label>
                <p>Kabupaten Padang Lawas</p>
            </div>
            <button class="navbar-toggler " type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                        <a class="nav-link js-scroll-trigger" href="#beranda">BERANDA <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger text-white" href="login">PROFIL</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle text-white" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        PEMDES
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#">Kepala Desa</a>
                        <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="#">Struktur Desa</a>
                        <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="#">Perangkat desa</a>
                        </div>
                    </li>
                    <li class="nav-item dropdown ">
                        <a class="nav-link dropdown-toggle text-white" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            PROGRAM
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item" href="#">Visi dan Misi</a>
                        <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="#">Future</a>
                        <div class="dropdown-divider"></div>
                            <a class="dropdown-item" href="#">Planning</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger text-white" href="#keuangan">KEUANGAN</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link js-scroll-trigger text-white" href="#suratonline">SURAT ONLINE</a>
                    </li>
                    <li class="nav-item">
                         <ButtonElement
                            titleBtn="LOGIN"
                        />
                    </li>
                </ul>
            </div>
        </div>
    </nav>
  </div>
</template>

<script>
import Button from '~/components/atoms/Button.vue' 
export default {
    components: {
        ButtonElement: Button,
    }
}
</script>

<style>
    .palas {
        object-fit: contain;
    }
    .logo {
        color: #f8f9fa;
        display: block;
        margin-top: 13px;
        line-height: 10px;
    }
    @media (max-width: 768px) {
        .logo {
            font-size: 13px;
        }
    }
</style>