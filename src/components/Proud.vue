<template>
    <div class="background">
        <div class="container">
            <h2 class="title">We are Proud</h2>
            <p>Certificate courses are instructed by highly educated and qualified instructors who hold doctoral and master’s level degrees.</p>
            <div class="box">
                <div class="box-info border-right">
                    <div class="number">2000</div>
                    <div class="info">STUDENTS</div>
                </div>
                <div class="box-info border-right">
                    <div class="number">950</div>
                    <div class="info">COURSES</div>
                </div>
                <div class="box-info border-right">
                    <div class="number">1600</div>
                    <div class="info">HOURS VIDEO</div>
                </div>
                <div class="box-info">
                    <div class="number">150</div>
                    <div class="info">COUNTRIES REACHED</div>
                </div>
            </div>
        </div>
    </div>
    <div class="box-green">
        <div class="container-green">
            <div class="card-left">
                <div class="newsletter">Subscribe our newsletter</div>
                <p class="paragraph">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words</p>
            </div>
            <div class="card-right">
                <div class="e-mail">YOUR E-MAIL ADDRESS</div>
                <div class="email-input">
                    <input type="email" placeholder="Enter your E-mail">
                    <button><span>SUBSCRIBE</span></button>
                </div>
            </div>
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
.background{
    background-color: #F0F4FA;
    background-image: url(/we_proud.png);
    height: 600px;
    background-repeat: no-repeat;
    background-position: bottom;
    height: 800px;
    .container{
        margin: 160px;
        .title{
            font-size: 50px;
            font-weight: 300;
            text-align: center;
            padding-top: 100px;
        }
        p{
            font-size: 18px;
            margin: 0 auto;
            text-align: center;
            width: 80%;
            margin-top: 30px;
            margin-bottom: 100px;
            font-weight: 300;
        }
        .box{
            display: flex;
            justify-content: center;
            .border-right{
                border-right: 1px solid rgba(147, 147, 147, 0.538);
            }
            .box-info{
                text-align: center;
                width: 300px;
                padding: 20px 10px;
                .number{
                    font-size: 70px;
                    font-weight: 300;
                }
                .info{
                    font-size: 20px;
                    font-weight: 300;
                }
            }
        }
    }    
}
.box-green{
    background-color: #4ED7A8;
    color: white;
    .container-green{
        margin: 0 160px;
        padding: 60px 0;
        display: flex;
        justify-content: space-between;
    }
}
.d-flex{
    display: flex;
}
.card-left{
    width: 55%;
    margin-right: 30px;
}
.card-right{
    width: 40%;
}
.newsletter{
    font-size: 19px;
    font-weight: 500;
    margin-bottom: 10px;
}
.paragraph{
    font-size: 15px;
}
.e-mail{
    font-size: 14px;
    margin-bottom: 10px;
}
input{
    border: none;
    padding: 15px;
    font-size: 15px;
    width: 350px;
}
button{
    background-color: #195EC8;
    border: none;
    padding: 16px;
    color: white;
}
.email-input{
    display: flex;
}
</style>