<template>
  <header class="containerHead">
        <div >
            <img id="logoHead" src="../assets/dc-logo.png" alt="">
        </div>
        <nav>
            <ul>
                <li v-for="(link, index) in links" :key="index"><a :href="link.url" :class="link.actives?'actives':''">{{link.text}}</a></li>
                               
            </ul>
        </nav>

    </header>
</template>

<script>
export default {
    name:'MyHeader',

    data (){
        return{
                links:[
                    {
                        text:'Characters',
                        url:'#',
                        actives:false
                    },
                     {
                        text:'Comics',
                        url:'#',
                        actives:true
                    },

                     {
                        text:'Movies',
                        url:'#',
                        actives:false
                    },

                     {
                        text:'TV',
                        url:'#',
                        actives:false
                    },
                      {
                        text:'Games',
                        url:'#',
                        actives:false
                    },
                    {
                        text:'Collectibles',
                        url:'#',
                        actives:false
                    },
                    {
                        text:'Videos',
                        url:'#',
                        actives:false
                    },
                    {
                        text:'Fans',
                        url:'#',
                        actives:false
                    },
                      {
                        text:'News',
                        url:'#',
                        actives:false
                    },
                      {
                        text:'Shop',
                        url:'#',
                        actives:false
                    },
                    
                ]
                
        }
    }
}
</script>

<style scoped lang="scss">

    .containerHead{
        margin: 0 15%;
        display: flex;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 0;
    }
    
    nav{
         display: flex;
         align-items: center;
        ul{
            display: flex;
            
        }
    
        li{
            list-style: none;
            margin: 0 10px;
            font-size: 12px;
            font-weight: bold;
           
        }
        a{
            text-decoration: none;
            color: #464652;
        }
    }
    
    #logoHead{
        height: 50px;
    }
    
    a.actives{
        border-bottom: 4px solid #0282f9;
        padding: 27px 0;
        color: #0282f9;
    }
    a:hover{
        border-bottom: 4px solid #0282f9;
        padding: 27px 0;
        color: #0282f9;
        
    }
    
</style>