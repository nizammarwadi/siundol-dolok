<template>
    <div class="form">
        <form>
            <div class="form-group">
                <input type="email" class="form-control" id="inputEmail1" aria-describedby="emailHelp" placeholder="Email atau Username">
            </div>
            <div class="form-group">
                <input type="password" class="form-control" id="inputPassword1" placeholder="Kata Sandi">
            </div>
           
            <div class="form-group">
                <button type="submit" class="login btn btn-primary">Login</button>
            </div>
            <div class="form-group">
                <button type="submit" class="akun btn btn-success">Buat Akun Baru</button>
            </div>
           
        </form>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .form {
        max-width: 400px;
        margin: 100px auto;
        background-color: white;
        padding: 30px 20px;
        border-radius: 8px;
    }
    .form-control{
        height: 50px; 
    }
    .login {
        width: 360px;
        height: 45px;
        font-weight: bold;
        font-size: 18px;
    }
    .akun{
        width: 180px;
        margin: 0px 90px;
    }
    /* body {
        background-color:  #eaeaea;
    } */
    

</style>