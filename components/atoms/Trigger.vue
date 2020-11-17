<template>
  <div class="container">
    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#myModal">
    Open modal
    </button>
    <div class="modal" id="myModal">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-body">
                    <form>
                        <div class="form-group">
                            <input type="email" class="form-control" id="inputEmail1" aria-describedby="emailHelp" placeholder="Email atau Username">
                        </div>
                        <div class="form-group">
                            <input type="password" class="form-control" id="inputPassword1" placeholder="Kata Sandi">
                        </div>
                    
                        <div class="form-group">
                            <a href="#" class=" btn btn-primary">Login</a>
                        </div>
                        <div class="account form-group">
                            <a href="#" class="btn btn-success">Buat Akun Baru</a>
                        </div>
                    </form>
                </div>
                <!-- <div class="modal-footer">
                    <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
                </div> -->
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style> 
    .form-control{
        height: 50px; 
    }
    .modal {
        background-color: white;
    }
    .modal-content {
        background-color: transparent;
        border: 8px solid #eaeaea;
        border-radius: 5px;
        max-width: 350px;
        margin: 80px auto 0px;
    }
    a {
       width: 100%; 
    }
    .account {
        width: 50%;
        margin: 0px auto;
    }
   
/* .form {
        max-width: 400px;
        margin: 100px auto;
        background-color: transparent;
        padding: 30px 20px;
        border-radius: 8px;
    } */
    /* .login {
        width: 360px;
        height: 45px;
        font-weight: bold;
        font-size: 18px;
    }
    .akun{
        width: 180px;
        margin: 0px 90px;
    } */

</style>