<template>
    <div class="container">
        <div>
            <h1>Start Investing in Yourself</h1>
            <h3>With over 1200 courses in 18 subjects, you're guaranteed to find something that's right for you.</h3>
            <a class="button" href="">JOIN FOR FREE</a>
        </div>
        <div>
            <img class="base" src="/base.png" alt="">
            <img class="book1" src="/book1.png" alt="">
            <img class="book2" src="/book2.png" alt="">
            <img class="bubble" src="/bubblespeech.png" alt="">
            <img class="magnifier" src="/magnifier.png" alt="">
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
    margin: 0 160px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    h1{
        font-size: 64px;
        font-weight: 300;
        margin-bottom: 20px;
        line-height: 68px;
    }
    h3{
        font-size: 24px;
        font-weight: 400;
        margin-bottom: 50px;
    }
    .button{
        padding: 20px 40px;
        background-color: #195EC8;
        color: white;
        border-radius: 30px;
        text-decoration: none;
        font-weight: bold;
        font-size: 14px;
    }
    .book1{
        left: 380px;
        bottom: 250px;
    }
    .book2{
        left: 50px;
        bottom: 130px;
    }
    .base{
        top: 120px;
    }
    .bubble{
        bottom: 410px;
        left: 80px;
    }
    .magnifier{
        bottom: 170px;
        right: 40px;
    }
}
img{
    position: relative;
}
*{
    color: #273044;
}
</style>