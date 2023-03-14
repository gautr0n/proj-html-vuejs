<template>
    <header>
        <div>
            <select name="Language" id="lang">
                <option value="en">English</option>
                <option value="it">Italian</option>
                <option value="de">Deusch</option>
            </select>
            <ul>
                <li v-for="el in navBar">hello</li>
            </ul>            
        </div>
    </header>
</template>
  
  <script>
    import store from '../store'
    export default {
      data() {
        return  {
          store,
        }
      },
    }
  </script>
  
  <style lang="scss" scoped>
    header{
        padding: 15px 10px;
        div{        
        display: flex;
        justify-content: space-between;
            #lang{
            border: none;
            }          
        }

    }

  </style>