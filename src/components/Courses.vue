<template>
    <div class="container">
        <div class="item1">
            <div><img src="/cat_1-770x375.jpg" alt=""></div>
            <div class="description"><span class="category">Software Development</span><span class="courses">4 Courses</span></div>
        </div>
        <div class="item2 small">
            <div><img src="/cat_2-370x155.jpg" alt=""></div>
            <div class="description"><span class="category">Art</span><span class="courses">8 Courses</span></div>
        </div>
        <div class="item3 small">
            <div><img src="/cat_3-370x155.jpg" alt=""></div>
            <div class="description"><span class="category">Material Design</span><span class="courses">4 Courses</span></div>
        </div>
        <div class="item4 small">
            <div><img src="/cat_5-370x155.jpg" alt=""></div>
            <div class="description"><span class="category">Music</span><span class="courses">5 Courses</span></div>
        </div>
        <div class="item5 small">
            <div><img src="/cat_4-370x155.jpg" alt=""></div>
            <div class="description"><span class="category">Exercise</span><span class="courses">7 Courses</span></div>
        </div>
        <div class="item6 small">
            <div><img src="/cat_6-370x155.jpg" alt=""></div>
            <div class="description"><span class="category">Photography</span><span class="courses">4 Courses</span></div>
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
    .item1 { 
        grid-area: big-card;
        img{
            width: 780px;
            height: 380px;
            margin-bottom: 10px;
        }
        .courses{
            padding-right: 22px;
        } 
    }
    .item2 { 
        grid-area: art;
        .courses{
            padding-right: 12px;
        } 
    }
    .item3 { 
        grid-area: material-design;
        .courses{
            padding-right: 12px;
        } 
    }
    .item4 { 
        grid-area: music; 
        .courses{
            padding-right: 23px;
        } 
    }
    .item5 { 
        grid-area: exercise; 
        .courses{
            padding-right: 23px;
        } 
    }
    .item6 { 
        grid-area: photography;
        .courses{
            padding-right: 12px;
        } 
    }
    .container{
        margin: 0 160px;
        margin-top: 120px;
        display: grid;
        grid-template-areas:
          'big-card big-card art'
          'big-card big-card material-design'
          'music exercise photography';
        gap: 10px 20px;
    }
    .small{
        margin: 0;
        padding: 0;
        img{
            height: 165px;
            width: 369px;
            margin-bottom: 10px;
        }
    }
    .category{
        font-size: 16px;
        font-weight: 500;
    }
    .description{
        display: flex;
        justify-content: space-between;
    }
    .relative{
        position: relative;
        left: 68%;
        bottom: 400px;
    }
    *{
        font-size: 14px;
    }
</style>