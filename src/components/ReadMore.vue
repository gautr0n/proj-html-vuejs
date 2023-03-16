<template>
    <div class="container">
        <div class="box">
            <h2>Limitless learning, more possibilities</h2>
            <h3>Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.</h3>
            <a href="">READ MORE</a>
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
    background-image: url(/Untitled-1-1-1-1-1.png);
    padding: 0 160px;
    margin-top: 180px;
    margin-bottom: 50px;
}
.box{
    width: 50%;
    padding: 120px 0;
    h2{
        font-size: 50px;
        font-weight: 300;
        line-height: 60px;
        margin-bottom: 40px;
    }
    h3{
        font-size: 24px;
        font-weight: 400;
        margin-bottom: 70px;
    }
    a{
        text-decoration: none;
        color: white;
        background-color: #195EC8;
        padding: 20px 30px;
        border-radius: 30px;
        font-weight: 500;
        font-size: 16px;
    }   
}

</style>