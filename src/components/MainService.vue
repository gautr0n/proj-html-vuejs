<template>
    <div class="container">
        <div class="card">
            <font-awesome-icon class="icon" icon="fa-solid fa-earth-europe" />
            <h4>Worldwide Trends</h4>
            <p>Our services and collections adhere to cutting-edge solutions in the design world.</p>
        </div>
        <div class="card">
            <font-awesome-icon class="icon" icon="fa-solid fa-display" />
            <h4>Complex Online Education</h4>
            <p>We have everything for effective learning and delivery of assignments by students.</p>
        </div>
        <div class="card">
            <font-awesome-icon class="icon" icon="fa-regular fa-calendar-check" />
            <h4>Brand certificate</h4>
            <p>After completing the course, you will receive a certificate confirming your knowledge.</p>
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
        .card{
            width: 32%;
            background-color: #F2F6FB;
            padding: 30px;
            .icon{
                font-size: 50px;
                color: #195EC8;
                margin-bottom: 20px;
            }
            h4{
                font-size: 16px;
                margin-bottom: 20px;
            }
        }
    }
    *{
        font-size: 14px;
    }
</style>
