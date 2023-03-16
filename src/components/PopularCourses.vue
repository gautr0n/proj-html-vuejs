<template>
    <div class="container">
        <div>
            <h2>Popular Courses</h2>
            <div class="description">Discover our most popular courses for self learning</div>
        </div>
        <div class="card-container">
            <div class="card">
                <img src="/course-preview-272x161.jpg" alt="">
                <div class="info">
                    <div class="type"><span>Software Development</span><span class="banner hot">HOT</span></div>
                    <h4 class="card-title">Basic of MasterStudy Education Theme</h4>
                    <div class="d-flex justify-between">
                        <div class="star-bar">
                            <div class="mr-5">
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                            </div>
                            5
                        </div>
                        <div class="price">Free</div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="/cat_2-272x161.jpg" alt="">
                <div class="info">
                    <div class="type"><span>Art</span><span class="banner new">NEW</span><!-- <span class="featured-banner">FEATURED</span> --></div>
                    <h4 class="card-title">Real Things Art Paintings by Jason Ni</h4>
                    <div class="d-flex justify-between">
                        <div class="star-bar">
                            <div class="mr-5">
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                            </div>
                            5
                        </div>
                        <div class="price-box">
                            <div class="discounted">$60.99</div>
                            <div class="price">$45.99</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="/book-internet.jpg" alt="">
                <div class="info">
                    <div class="type"><span>Art</span><span class="banner hot">HOT</span><!-- <span class="featured-banner">FEATURED</span> --></div>
                    <h4 class="card-title">Minimalism, How to make things simplier</h4>
                    <div class="d-flex justify-between">
                        <div class="star-bar">
                            <div class="mr-5">
                                <font-awesome-icon icon="fa-regular fa-clock" />
                            </div>
                            5 Hours
                        </div>
                        <div class="price-box">
                            <div class="discounted">$79.99</div>
                            <div class="price">$39.99</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="/photo-1496307042754-b4aa456c4a2d-272x161.jpeg" alt="">
                <div class="info">
                    <div class="type"><span>Electronic</span><span class="banner special">SPECIAL</span></div>
                    <h4 class="card-title">How to be a DJ? Make Electronic Music</h4>
                    <div class="d-flex justify-between">
                        <div class="star-bar">
                            <div class="mr-5">
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                                <font-awesome-icon class="star" icon="fa-solid fa-star" />
                            </div>
                            5
                        </div>
                        <div class="price-box">
                            <div class="discounted">$59.99</div>
                            <div class="price">$49.99</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="/photo-1416339134316-0e91dc9ded92-scaled-272x161.jpeg" alt="">
                <div class="info">
                    <div class="type"><span>Communication</span></div>
                    <h4 class="card-title">Graphic Design Basics Masterclass</h4>
                    <div class="d-flex justify-between">
                        <div class="star-bar">
                            <div class="mr-5">
                                <font-awesome-icon icon="fa-regular fa-clock" />
                            </div>
                            8 Hours
                        </div>
                    </div>
                </div>
            </div>
            <div class="card">
                <img src="/photo-1461749280684-dccba630e2f6-272x161.jpeg" alt="">
                <div class="info">
                    <div class="type"><span>Apache</span><span class="banner hot">HOT</span><!-- <span class="featured-banner">FEATURED</span> --></div>
                    <h4 class="card-title">Web Coding and Apache asics theory</h4>
                    <div class="d-flex justify-between">
                        <div class="star-bar">
                            <div class="mr-5">
                                <font-awesome-icon icon="fa-regular fa-clock" />
                            </div>
                            10 Hours
                        </div>
                        <div class="price">Free</div>
                    </div>
                </div>
            </div>
        </div>
        <div class="nav-button">
            <button class="button1"><span> &lt; </span></button>
            <button class="button2"><span> > </span></button>
        </div>
    </div>

</template>

<script>
  import store from '../store'

export default{
    data() {
      return {
        store
      }
    },
}
</script>

<style lang="scss" scoped>
.container{
    padding: 35px 15px 0;
    margin-bottom: 75px;
    background-color: #F0F4FA;
    .card-container{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        .card{
            position: relative;
            width: 15.5%;
            border: 1px solid rgba(147, 147, 147, 0.538);
            margin-bottom: 50px;
            background-color: white;
            img{
                width: 100%;
                height: 150px;
                margin-bottom: 10px;
            }
            .info{
                padding: 0 20px 7px;
                .type{
                    color: #AAAAAA;
                    font-size: 13px;
                    margin-bottom: 10px;
                }
                .card-title{
                    border-bottom: 1px solid rgba(147, 147, 147, 0.538);
                    padding-bottom: 20px;
                    font-size: 15px;
                    margin-bottom: 20px;
                    font-weight: 500;
                    line-height: 20px;
                }
            }
        }
        .featured-border{
            border: 1px solid #1DB874;
        }
    }
    
}
.d-flex{
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}
.justify-center{
    justify-content: center;
}
.justify-between{
    justify-content: space-between;
}
.star-bar{
    font-size: 14px;
    display: flex;
    align-items: center;
}
.star{
    color: #EFB467;
}
.mr-5{
    margin-right: 5px;
}
.price{
    font-weight: 600;
    font-size: 15px;
}
.featured-banner{
    position: absolute;
    padding: 5px 50px;
    border-radius: 5px;
    top: 20px;
    right: 110px;
    color: white;
    background-color: #17D292;
    rotate: (-45deg);
}
.banner{
    position: absolute;
    padding: 5px 10px;
    border-radius: 5px;
    top: 8px;
    right: 8px;
    color: white;
}
.hot{
    background-color: red;
}
.new{
    background-color: #1DB874;
}
.special{
    background-color: #F09B23;
}
.discounted{
    color: #AAAAAA;
    text-decoration: line-through;
    font-size: 12px;
    line-height: 8px;
}
.price-box{
    text-align: end;
}
.nav-button{
    text-align: center;
    padding-bottom: 100px;
    button{
        background-color: white;
        color: rgba(147, 147, 147, 0.538);
        padding: 14px 20px;
        span{
            font-size: 20px;
            font-weight: 500;
        }
    }
    .button1{
        border: 1px solid rgba(147, 147, 147, 0.538);
    }
    .button2{
        border-top: 1px solid rgba(147, 147, 147, 0.538);
        border-right: 1px solid rgba(147, 147, 147, 0.538);
        border-bottom: 1px solid rgba(147, 147, 147, 0.538);
        border-left: none;
    }
}
button:hover{
    background-color: #195EC8;
    border: none;
    color: white;
    transition: background-color 0.8s;
}
h2{
    font-size: 50px;
    text-align: center;
    font-weight: 300;
    padding-top: 100px;
    margin-bottom: 30px;
}
.description{
    font-size: 18px;
    font-weight: 300;
    text-align: center;
    margin-bottom: 50px;
}
</style>