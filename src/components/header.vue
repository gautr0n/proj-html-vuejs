<template>
    <header>
        <div>
            <select name="Language" id="lang">
                <option value="en">English</option>
                <option value="it">Italian</option>
                <option value="de">Deusch</option>
            </select>
            <div>
                <ul>
                    <NavCard v-for="(el, index) in this.store.navBar" :key="index" :i="index"/>
                </ul>
                <div>
                    <font-awesome-icon icon="fa-brands fa-twitter" />
                    <font-awesome-icon icon="fa-brands fa-instagram" />
                    <font-awesome-icon icon="fa-brands fa-behance" />
                    <font-awesome-icon icon="fa-brands fa-dribbble" />
                    <font-awesome-icon icon="fa-brands fa-flickr" />
                    <font-awesome-icon icon="fa-brands fa-git" />
                    <font-awesome-icon icon="fa-brands fa-linkedin" />
                    <font-awesome-icon icon="fa-brands fa-pinterest" />
                </div>
            </div>
        </div>
    </header>
    <div class="secondHeader">
        <img src="../../MasterStudy_logo.svg" alt="">
        <div class="middle-search">
            <span class="category">
                <font-awesome-icon icon="fa-solid fa-bars" />
                CATEGORY
            </span>
            <span class="search-bar">
                <input class="search" type="text" placeholder="Search courses">
                <button class="btn">
                    <font-awesome-icon class="glass" icon="fa-solid fa-magnifying-glass" />
                </button>
            </span>
            <span class="header-group">
                <font-awesome-icon class="header-icon" icon="fa-solid fa-bullhorn" />
                <span class="dark-gray">Become an instructor</span> 
            </span>
            <span class="header-group">
                <font-awesome-icon class="header-icon" icon="fa-solid fa-briefcase" />
                <span class="dark-gray">For Enterprise</span> 
            </span>
        </div>
        <div>
            <span>
                <font-awesome-icon class="header-icon" icon="fa-regular fa-user" />
                <span class="log-in">Log in</span>
            </span>
            <a href="">SIGN UP</a>
            <font-awesome-icon class="header-heart" icon="fa-regular fa-heart" />
        </div>
    </div>
</template>
  
<script>
    import store from '../store'
    import NavCard from './NavCard.vue'
    export default {
        components: {
            NavCard,
        },
        data() {
            return  {
                store,
            }
        }
    }
</script>

<style lang="scss" scoped>
    header{
        color: #777777;
        padding: 18px 12px;
        border-bottom: 1px groove #b9b9b949;
        div{        
        display: flex;
        justify-content: space-between;
        align-items: center;
            #lang{
            border: none;
            }
            div{
                width: 62%;
                ul{
                    width: 65%;
                    display: flex;
                    justify-content: space-between;
                }
                div{
                    width: 30%;
                    display: flex;
                    justify-content: space-around;
                    * {
                        font-size: 16px;
                    }
                }
            }
        }
    }
    .secondHeader{
        padding: 18px 12px;
        display: flex;
        color: #385bce;
        align-items: center;
        line-height: 14px;
        width: 98vw;
        justify-content: space-between;
        div{
            display: flex;
            justify-content: space-between;
            align-items: center;
            a{
                text-decoration: none;
                color: white;
                background-color: #385bce;
                border-radius: 30px;
                padding: 15px 40px;
                font-weight: 600;
                font-size: 14px;
                margin: 0 30px;
            }
        }
    }
    .category{
        font-weight: 600;
        color: #777777;
        font-size: 14px;
        margin-right: 15px;
    }
    .search{
        height: 45px;
        width: 300px;
        padding: 10px 15px;
        font-size: 14px;
        border: none;
        background-color: #f0f2f5;
        font-weight: lighter;
    }
    .btn{
        height: 45px;
        background-color: #385bce;
        color: white;
        width: 60px;
        border: none;
    }
    .middle-search{
        padding: 0 30px;
    }
    .search-bar{
        padding-right: 50px;
    }
    .dark-gray{
        color: #273044;
        font-size: 14px;
    }
    .glass{
        font-size: 18px;
    }
    .header-icon{
        font-size: 16px;
        padding-right: 10px;
    }
    .header-heart{
        font-size: 24px;
    }
    .header-group{
        margin-right: 20px;
    }
    .log-in{
        font-size: 14px;
    }
</style>