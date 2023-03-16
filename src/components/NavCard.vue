<template>
    <li class="card">
        <a href="" >{{ this.store.navBar[i] }}</a>
    </li>
  </template>
    
  <script>
  import store from '../store'
    export default {
        props: {
            i: {
                type: Object,
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