<template>
    <div class="container">
        <div class="card">
            <img src="/image_box_1-221x231.png" alt="">
            <div class="info-box">
                <h3>Become an Instructor</h3>
                <div>Teach what you love. Masterstudy gives you the tools to create a course.</div>
                <a href="">START TEACHING</a>
            </div>
        </div>
        <div class="card">
            <img src="/image_box_2-234x231.png" alt="">
            <div class="info-box">
                <h3>Setup For Business</h3>
                <div>Get unlimited access to 2,500 of Udemy’s top courses for your team.</div>
                <a href="">DOING BUISNESS</a>
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
.container{
    margin: 120px 100px;
    display: flex;
    justify-content: space-between;
    .card{
        display: flex;
        justify-content: space-between;
        width: 49%;
        border:  1px solid rgba(179, 178, 178, 0.538);
        padding: 60px 40px;
        .info-box{
            margin-left: 30px;
            margin-bottom: 20px;
            h3{
                font-size: 36px;
                line-height: 38px;
                font-weight: 400;
                margin-bottom: 20px;
            }
            div{
                font-size: 18px;
                font-weight: 300;
                line-height: 20px;
                margin-bottom: 40px;
            }
            a{
                text-align: center;
                color: white;
                text-decoration: none;
                padding: 18px 25px;
                background-color: #195EC8;
                border-radius: 30px;
                font-weight: 500;
                font-size: 14px;
            }
        }
    }
}

</style>