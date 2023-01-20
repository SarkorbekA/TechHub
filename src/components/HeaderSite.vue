<template>

    <header>
        <div class="header_under"></div>
        <div class="header">
            <div class="container">
                <div class="nav_bar">
                    <div class="logo">
                        <a class="logo__item" href="#">
                            Tech<span>Hub</span>
                        </a>
                    </div>
                    <ul class="nav">
                        <li><a href="#">About</a></li>
                        <li><a href="#">Goals</a></li>
                        <li><a href="tel:+998991001879">Contact</a></li>
                    </ul>
                    <div class="search">
                        <input placeholder="Search..." type="search" name="search" id="search">
                        <label class="search__label" for="search"> <i class="fa-solid fa-magnifying-glass"></i></label>
                    </div>
                </div>
            </div>
        </div>


        <div class="banner__bg">
            <div class="banner">
                <div class="container">
                    <h1 class="banner__h1">Coding simple with us</h1>
                    <h2 class="banner__h2">TechHub jamoasi sizni o'z kurslariga taklif qiladi !</h2>
                    <ul class="btn__list">
                        <li><a href="#">Demo lesson</a></li>
                        <li><a class="ofter__btn" href="#">Yozilish</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </header>

</template>




<script>
export default {
    name: "HeaderSite"
}
</script>



<style scoped>
header {
    width: 100%;
    -webkit-box-shadow: 0px 10px 50px 0px #0e213f;
    -moz-box-shadow: 0px 10px 50px 0px #0e213f;
    box-shadow: 0px 10px 50px 0px #0e213f;
}

.header {
    width: 100%;
    background: #ffd700;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 100;
    border-bottom: 1px solid black;
}

.header_under {
    width: 100%;
    height: 44px;
}

.nav_bar {
    width: 100%;
    align-items: center;
    display: flex;
    justify-content: space-between;
    height: 46px;
}

.logo__item {
    font-weight: 600;
    font-size: 28px;
    color: black;
    line-height: 30px;
}

.logo__item span {
    color: #1b440c;
}

.nav {
    display: flex;
    font-size: 20px;
}

.nav li a {
    display: inline-block;
    padding: 10px 20px;
    font-size: 25px;
    color: black;
    line-height: 26px;
    font-family: 'Alumni Sans', sans-serif;
}

.nav li a:hover {
    transition: .3s;
    background: #e9ba00;
    color: white;
}

#search {
    padding: 8px 5px 8px 32px;
}

.search__label {
    position: absolute;
    left: 53%;
    top: 8px;
    font-size: 14px;
    transition: .5s;
}

.search {
    width: 300px;
    position: relative;
}

.search input:focus+.search__label {
    left: 8px;
    transition: .5s;
}

.search input {
    float: right;
    width: 50%;
    transition: .5s;
    border-radius: 6px;
    outline: none;
    border: none;
    background-color: white;
}

.search input:focus {
    transition: .5s;
    width: 100%;
    background-color: #e0fff0;
}


/* .btn {
    padding: 10px 35px;
    line-height: 26px;
    color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 8px;
    font-weight: 500;
    font-size: 20px;
    transition-duration: .3s;
}

.btn:hover {
    color: white;
    transition: .3s;
    background-color: #ffcf10;
    transition: all 0.5s;
} */

.contact span {
    font-size: 18px;
}

.contact i {
    opacity: 0;
    display: none;
}

.contact:hover i {
    display: block;
    opacity: 1;
}

.banner__bg {
    width: 100%;
    background: url(../assets/banner1.jpg);
}

.banner {
    height: calc(100vh - 46px);
    display: flex;
    align-items: center;
    width: 100%;
    background: rgba(0, 0, 0, 0.4);
}

.banner .container {
    width: 100%;
    max-width: 700px;
    display: flex;
    flex-direction: column;
    gap: 25px;
    /* padding: 40px 25px 50px;
    background: rgba(0, 0, 0, 0.5);
    border-radius: 10px;
    -webkit-box-shadow: 19px 21px 30px 0px black;
    -moz-box-shadow: 19px 21px 30px 0px black;
    box-shadow: 19px 21px 30px 0px rgb(0, 0, 0); */
}

.banner__h1 {
    text-transform: uppercase;
    text-align: center;
    letter-spacing: 1.5px;
    font-size: 52px;
    color: gold;
}

.banner__h2 {
    text-align: center;
    color: white;
}

.btn__list {
    display: flex;
    justify-content: space-evenly;
    margin-top: 15px;
    gap: 15px;
}

.btn__list li {
    width: 40%;
}

/* 
.btn__list li a {
    font-weight: 500;
    text-align: center;
    width: 100%;
    display: inline-block;
    padding: 20px;
    background: #0b0b0b;
    color: white;
    text-transform: uppercase;
    transition-duration: .5s;
}

.btn__list li a:hover {
    transition: .3s;
    transform: scale(1.05);
    background: white;
    color: black;
} */

.btn__list li a {
    border: 3px solid white;
    font-weight: 500;
    text-align: center;
    width: 100%;
    display: inline-block;
    padding: 15px;
    color: white;
    text-transform: uppercase;
    transition-duration: .5s;
}

.ofter__btn {
    background: white;
    color: black !important;
}

.btn__list li a:hover {
    transition: .3s;
    transform: scale(1.05);
    background: white;
    color: black;
}
</style>