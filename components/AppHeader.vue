<template>
  <div>
    <!--   Header Section going here-->
    <section class="header_section">
        <div class="container-fluid">

        <div class="row">
            <div class="col-md-3">
                    <nav class="navbar navbar-expand-lg navbar-light">
                    <!-- <a class="navbar-brand" href="index.html">
                            <img src="~/assets/img/logo.png" width="100%" class="img-fluid" alt="Logo">   
                        </a> -->
                        <nuxt-link to='/' class="navbar-brand">
                        <img src="~/assets/img/logo.png" width="100%" class="img-fluid" alt="Logo"> 
                        </nuxt-link>
                </nav>

            </div>
            
            <div class="col-md-6 ">
            
            <div class="search_box mt-4">
            
                <div class="input-group mb-3">
                <div class="input-group-prepend">
                    <button class="btn dropdown-toggle border_left" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><b>Products</b> </button>
                    
                    <div class="dropdown-menu">
                    <a class="dropdown-item" href="#">Action</a>
                    <a class="dropdown-item" href="#">Another action</a>
                    <a class="dropdown-item" href="#">Something else here</a>
                    <div role="separator" class="dropdown-divider"></div>
                    <a class="dropdown-item" href="#">Separated link</a>
                    </div>
                </div>
                <span class="break_search mt-1">|</span>
                <input type="text" class="form-control" aria-label="Text input with dropdown button" placeholder="What you are looking here......">
                <div class="input-group-append">
                    <button class="btn btn_bg_danger text-white" type="button">Search</button>
                </div>
                </div>
                </div>
                
            </div>
            <div class="col-md-3">
                <div class="login_register mt-5">
                    <nuxt-link to='/login'  class="btn_danger text-decoration-none"><strong>Login / Register</strong></nuxt-link>
                </div>
            </div>
        </div>
        <hr>
        
        </div>
    </section>
    <!--   Header Section end here-->

    <!--Navbar Section going here-->
    <section class="navbar_section">
        <div class="container-fluid">
            <div class="row">
                <div class="col">
                    <nav class="navbar navbar-expand-lg navbar-light">

                        <button class="navbar-toggler ml-auto" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>

                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav mr-auto">
                                <li class="nav-item active">
                                    <a class="nav-link" href="#"><b>Ready to Ship</b> <span class="sr-only">(current)</span></a>
                                </li>

                                <li class="nav-item">
                                    <a class="nav-link text-dark" href="#"><b>Tread Show</b></a>
                                </li>

                                <li class="nav-item">
                                    <a class="nav-link text-dark" href="#"><b>Become a Seller</b></a>
                                </li>

                                <li class="nav-item">
                                    <a class="nav-link text-dark" href="#"><b>Help</b></a>
                                </li>

                                <li class="nav-item">
                                    <a class="nav-link text_color" href="#"><b><i class="far fa-edit"></i> Post your Requirement</b></a>
                                </li>


                            </ul>

                        </div>
                    </nav>

                </div>
            </div>
            <!--row end-->
        </div>
        <!--container end-->
        <hr>
    </section>
    <!--Navbar Section end here-->

  </div>
</template>

<script>
export default {
    name : 'AppHeader'
}
</script>

<style>

</style>