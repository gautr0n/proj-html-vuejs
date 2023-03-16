<template>
    <div class="footer">
        <ul class="footer-box">
            <li class="footer-section"><div class="title">About</div>
                <div class="fs-13"><a class="link-about" href="">Masterstudy</a> is Education WordPress theme featured by Learning Management System (LMS) for online education.
                    Developed by <a class="link-about" href="">StylemixThemes.</a></div>
                <div class="icon-box">
                    <font-awesome-icon class="social-icon" icon="fa-brands fa-facebook" />
                    <font-awesome-icon class="social-icon" icon="fa-brands fa-twitter" />
                    <font-awesome-icon class="social-icon" icon="fa-brands fa-instagram" />
                </div>
            </li>
            <li class="footer-section"><div class="title">Contact</div>
                <div class="fs-13 m-b-20">USA, Callifornia 20, First Avenue, Callifornia</div>
                <div>+1 212 458 300 32</div>
                <div class="m-b-20">+1 212 375 24 14</div>
                <a class="gray-color" href="">info@masterstudy.com</a>
            </li>
            <li class="footer-section"><div class="title">Pages</div>
                <div class="d-flex js-space-around">
                    <ul>
                        <li class="fs-14">Blog</li>
                        <li class="fs-14">Courses</li>
                        <li class="fs-14">Home</li>
                    </ul>
                    <ul>
                        <li class="fs-14">Shortcodes</li>
                        <li class="fs-14">Typography</li>
                        <li class="fs-14">Memberships</li>
                    </ul>                    
                </div>
            </li>
            <li class="footer-section"><div class="title">Blog</div>
                <div class="d-flex m-b-20">
                    <img src="/photo-1517520287167-4bbf64a00d66-69x69.jpeg" alt="">
                    <div>
                        <span class="fs-14 font-bolder">Our main target is to “Developing Yourself as a Leader”</span>
                        <br>
                        <span class="gray-color fs-14">-August 9, 2018</span>
                    </div>
                </div>
                <div class="d-flex">
                    <img src="/photo-1490376840453-5f616fbebe5b-50x50.jpeg" alt="">
                    <div>
                        <span class="fs-14 font-bolder">Those Other College Expenses You Aren`t Thinking About</span>
                        <br>
                        <span class="gray-color fs-14">-June 3, 2015</span>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
</script>

<style lang="scss" scoped>
.footer{
    padding: 63px 0 25px;
    margin: 0 160px;
    .footer-box{
        display: flex;
        justify-content: space-between;
        .title{
            font-weight: bolder;
            margin-bottom: 21px;
            font-size: 18px;
        }          
    }
}
li{
    list-style-type: disc;
    margin-bottom: 10px;
}
img{
    margin-right: 20px;
    height: 75px;
    width: 75px;
}
.footer-section{
    width: 23%;
    list-style-type: none;
}
.fs-13{
    font-size: 13px;
}
.fs-14{
    font-size: 14px;
}
.d-flex{
    display: flex;
    justify-content: space-between;
}
.icon-box{
    margin-top: 20px;
}
.social-icon{
    font-size: 25px;
    color: #AAAAAA;
    margin-right: 15px;
}
.link-about{
    text-decoration: none;
    color: #195EC8;
}
.gray-color{
    color: #D9D9D9;
    text-decoration: none;
}
.js-space-around{
    justify-content: space-around;
}
.m-b-20{
    margin-bottom: 20px;
}
.font-bolder{
    font-weight: bolder;
}
</style>