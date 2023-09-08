<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ayurveda and homeopathic awreness</title>
    <link rel="stylesheet" href="desktop.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <header>
    <nav id="navbar">
        <div id="logo">
            <img src="ayurved_logo-removebg-preview.png" alt="ayurved and homeopathic logo">
        </div>
        <ul>
            <li class="item"><a href="#home">HOME</a></li>
            <li class="item"><a href="#about-section">ABOUT</a></li>
            <li class="item"><a href="#services-container">SERVICES </a></li>
            <li class="item"><a href="#branch-section"> BRANCHES</a><li>
            <li class="item"><a href="#contact">CONTACT</a></li>
            
        </ul>
        <a href="#" class="action-btn">GET STARTED</a>
        <div class="toogle_btn">
            <i class="fa-solid fa-bars"></i>
        </div>
    </nav>

    <div class="dropdown_menu ">
        <li class="item"><a href="#home">HOME</a></li>
        <li class="item"><a href="#about-section">ABOUT</a></li>
        <li class="item"><a href="#services-container">SERVICES</a><li>
        <li class="item"><a href="#branch-section"> BRANCHES</a><li>
        <li class="item"><a href="#contact">CONTACT</a></li>
        <li><a href="#" class="action-btn">GET STARTED</a></li>
    </div>
</header>

<main>
    <section id="hero">
        <h1>WELCOME</h1>
        <video id="video" src="What Is Ayurveda How to Get Started.mp4" width="300px" height="400px" autoplay></video>
        <p>UNLEASH THE AYURVEDIC & HOMEOPATHIC WORLD</p>
    </section>
</main>

<section id="ayurvedic">

</section>

<!-- JAVASCRIPT  -->
<script>
    const toggleBtn = document.querySelector('.toogle_btn')
    const toggleBtnIcon = document.querySelector('.toogle_btn i')
    const dropDownmenu = document.querySelector('.dropdown_menu')

    toggleBtn.onclick =function(){
        dropDownmenu.classList.toggle('open')
        const isOpen = dropDownmenu.classList.contains('open')

        toggleBtnIcon.classList = isOpen
        ? 'fa-solid fa-xmark'
        : 'fa-solid fa-bars'
    }
</script>

</body>
</html>
