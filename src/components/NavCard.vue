<template>
    <li class="card">
        <a href="" >{{ this.store.navBar[el] }}</a>
    </li>
  </template>
    
  <script>
  import store from '../store'
    export default {
        props: {
            el: {
                type: Number,
                required: true
            }
        },
        data() {
            return  {
                store,
            }
        }
    }
  </script>
  
  <style lang="scss" scoped>
    li{
      list-style-type: none;
      a{
        text-decoration: none;
        color: #777777;
      }
    }
  </style>