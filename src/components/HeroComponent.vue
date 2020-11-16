<template>
    <header id="home-section">
        <div class="dark-overlay">
            <div class="home-inner container">
                <div class="row">
                    <div class="col-lg-8 d-none d-lg-block">
                        <h1 class="display-4">
                            Build <strong>social profiles</strong> and gain revenue <strong>profit</strong> 
                        </h1>
                        <div class="d-flex">
                        <div class="p-4 align-self-start">
                            <i class="fa fa-check fa-2x"></i>
                        </div>
                        <div class="p4 align-self-end">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia explicabo provident exercitationem voluptate nobis animi!</div>
                    </div>
                    <div class="d-flex">
                        <div class="p-4 align-self-start">
                            <i class="fa fa-check fa-2x"></i>
                        </div>
                        <div class="p4 align-self-end">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia explicabo provident exercitationem voluptate nobis animi!</div>
                    </div>
                    <div class="d-flex">
                        <div class="p-4 align-self-start">
                            <i class="fa fa-check fa-2x"></i>
                        </div>
                        <div class="p4 align-self-end">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia explicabo provident exercitationem voluptate nobis animi!</div>
                    </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="card bg-primary text-center card-form">
                            <div class="card-body">
                                <h3>Sign Up Today</h3>
                                <p>Please fill out this form to register</p>
                                <form action="">
                                    <div class="form-group">
                                        <input type="text" class="form-control form-control-lg" placeholder="username">
                                    </div>
                                     <div class="form-group">
                                        <input type="email" class="form-control form-control-lg" placeholder="email">
                                    </div>
                                     <div class="form-group">
                                        <input type="password" class="form-control form-control-lg" placeholder="password">
                                    </div>
                                     <div class="form-group">
                                        <input type="password" class="form-control form-control-lg" placeholder="confirm password">
                                    </div>
                                    <input type="submit" value="submit" class="btn btn-outline-light btn-block">
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
    export default {
        
    }
</script>

<style  scoped>
#home-section{
    background:url('../assets/home.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: fixed;
    min-height: 700px;
    color: white;
}

#home-section .dark-overlay{
    position:absolute;
    top:0;
    left:0;
    width: 100%;
    min-height: 700px;
    background:rgba(0,0,0,0.7)
}

#home-section .home-inner{
    padding-top:150px;
}

#home-section .card-form{
    opacity:0.8;
}

#home-section .fa{
    color: #008ed6;
    background: #fff;
    padding: 5px;
    border-radius:5px;
}
</style>