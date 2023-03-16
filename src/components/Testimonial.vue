<template>
    <div class="background">
        <div class="container">
            <div class="box">
                <h2>Paints of the Future</h2>
                <p>The response to your MasterStudy has been really overwhelming! Those who participated in the workshop are spreading the word here on campus and the “buzz” is on. The VP of Instruction wants you to come back! Her goal is to have more faculty trained. She also wants to attend a workshop herself. Our President told me Masterstudy needs to be the cornerstone of our success program.”</p>
                <div>
                    <h4>Xatashi Froust</h4>
                    <div>SEO, Froust Inc</div>
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
    background-image: url(/testimonial-1-1917x640.jpg);
    height: 640px;
    .container{
        padding: 85px 180px;
        .box{
            width: 50%;
            background-color: white;
            padding: 50px 80px;
            h2{
                font-size: 36px;
                margin-bottom: 30px;
                font-weight: 400;
            }
            p{
                font-size: 15px;
                margin-bottom: 50px;
            }
        }
    }
}
</style>