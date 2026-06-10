# Rafli-Personel
Web
<html>
    <head></head>
    <title>RAFLI WEBSITE</title>
    <link rel="stylesheet" href="style.css" />
    <body>
       <!-- Navigation Bar -->
        <div class="container-navigation">
            <ul class="ul-navbar">
                <li class="li-navbar">
                    <a href="https://www.instagram.com/mochrafliiia/" class="a-navbar">SELAMAT DATANG DI MY PROFILE</a>
                <li class="li-navbar">
            </ul>
        </div>
        <!-- Navigation Bar selesai -->
        
        <!-- Content 1 -->
        <div class="container-content">
            <a href="https://www.youtube.com/@Golik112"><IMG src="rafli foto.jpeg" class="img-content"/></a>
        </div>

        <!-- content 1 end -->

        <!-- Footer  -->
         <div class="container-footer">
            <a href="https://discord.com/channels/@me/1483711851102736568" class="h1-footer">INI AKUN DISCORD SAYA</a>
         </div>
        <!-- Footer end -->
    </body>
</html>


*,
html {
    padding: 0%;
    margin: 0;
}

body {
    height: 100vh;
}

.container-navigation {
background-color: rgb(238, 135, 0);
}

.ul-navbar {
display: flex;
justify-content: center;
align-items: center;
height: 10vh;
}

.li-navbar {
padding: 20px;;
list-style-type: none;  
margin: 5px;
}

.li-navbar:hover {
    background-color:wheat;
    transition-delay: .4s;
    border-radius: 5px;
    transition: .5s ease-in-out
}

.a-navbar {
    color: black;
    text-decoration: none;
    font-size: 20px;
    font-style: italic;
}

.container-content {
background-color:rgb(231, 21, 21) ;
display: flex;
height: 80vh;
align-items: center;
justify-content: center
}

.img-content {
width: 100%;
height: 80%;
}

.container-footer {
justify-content: center;
align-items: center;
display: flex;
height: 10vh;
}

.h1-footer {
text-decoration: none;
}

.container-footer:hover {
background-color:wheat;
transition-delay: .4s;
border-radius: 5px;
transition: .5s ease-in-out
}
