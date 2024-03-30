<template>
<nav class="navbar navbar-expand-lg sticky-top p-3" style="background-color: #3a1772;">
    <div class="container-fluid mx-auto">
        <a class="navbar-brand text-light fs-5 ms-4 me-5 mt-3" href="#home">
            <img src="profile-user.png" alt="Portfolio Icon" width="30" height="30" style="filter: brightness(0) invert(1);">
            <p style="font-size: 0.75rem;">Reynaldo</p>
        </a>
        <a class="nav-link text-light fs-6 me-5 ms-4" aria-current="page" href="#about">About</a>

        <a class="me-3 ms-4" href="https://web.facebook.com/reynaldo.1102" target="_blank">
            <img src="facebook.png" width="30px" title="Facebook" class="zoom-in-effect">
        </a>
        <a href="mailto:andalesr11@gmail.com" class="text-dark text-decoration-none me-3" target="_blank">
            <img src="gmail.png" width="30px" title="Gmail" class="zoom-in-effect">
        </a>
        <a href="https://www.tiktok.com/@kil9648?_t=8l6fHAbfHwl&_r=1" class="text-dark text-decoration-none" target="_blank">
            <img src="tik-tok.png" width="30px" title="TikTok" class="zoom-in-effect">
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
            <ul class="navbar-nav me-4">

            </ul>
        </div>
    </div>
</nav>

<div id="home" class="container-fluid p-5" style="background-color: #5398be;">
    <div class="container">
        <div class="row">
            <div class="col-md-6">
                <h2 class="fw-bold text-light">Reynaldo Andales</h2>
                <div class="mb-5 text-white" style="font-size: 0.67rem;">Student of Cordova Public College</div>
                <div class="row">
                    <div class="col-md-12">
                        <h5 class="text-light">
                            Welcome to my portfolio! I'm a BSIT student specializing in programming, 
                            showcasing my expertise through innovative projects that demonstrate my 
                            skills and passion for technology.
                        </h5>
                    </div>
                </div>
                <div class="mt-5 text-white">
                    <img src="telephone.png" width="30px" title="Telephone" class="zoom-in-effect">
                    0916-1393-365
                </div>
            </div>

            <div class="col-md-6">
                <img class="img-fluid rounded mb-5" alt="Portrait" src="/test.jpg" style="max-width: 50%; height: auto;">
            </div>

        </div>
    </div>
</div>

    <div id="about"></div>
        
        <h2 class="text-center mt-5 mb-5 fw-bold">About Me</h2>

        <div class="container-fluid" style="background-color: #f2cd5d;">
            <div class="row p-5">
                <div class="col-md-12 text-dark p-5 mx-auto">
                    <p class="fs-5">
                        I'm Reynaldo Andales, a BSIT student majoring in programming, 
                        dedicated to developing innovative digital solutions. With expertise 
                        in both frontend and backend development, I focus on crafting engaging user experiences. 
                        My proficiency includes Javascript, SQL, PHP, Bootstrap, and more, offering comprehensive services 
                        to enhance digital presence.
                    </p>
                </div>
                <div class="col-md-12 p-5 mt-5">
                    <div class="container">
                        <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
                            <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                                <img src="bootstrap.png" width="80px" title="Bootstrap" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                                <img src="css.png" width="80px" title="CSS" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                                <img src="php.png" width="140px" title="PHP" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                                <img src="html.png" width="80px" title="HTML" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                                <img src="sql.png" width="80px" title="SQL" class="zoom-in-effect">
                            </div>
                            <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                                <img src="js.png" width="80px" title="JS" class="zoom-in-effect">
                            </div>
                        </div>
                    </div>

                        <a class="btn btn-dark btn-lg zoom-in-effect mt-3" href="https://github.com/andales143/MyProjects" target="_blank">Repositories</a>
                </div>
            </div>
        </div>


</template>

<script>

</script>


<style>

.navbar-brand, .nav-link {
  font-family: sans-serif;
  font-size: 10px; 
}

body {
  font-family: 'Times New Roman', Times, serif;
}

h1,
h5 {
  font-size: 15px; /* You can adjust the font size as needed */
}

</style>
