<template>
    <div class="aside">
        <ul>
            <li>
                <i class="iconfont icon-logs"></i>
            </li>
            <li>
                <i class="iconfont icon-done"></i>
            </li>
            <li>
                <i class="iconfont icon-share"></i>
            </li>
            <li>
                <i class="iconfont icon-delete"></i>
            </li>
            
        </ul>
        <div class="icon">
            <img :src="iconUrl" >
        </div>
        <div class="menu">
            <span></span>
             <span></span>
        </div>
    </div>
</template>
<script>
import '../assets/common/css/icons.css'
export default {
    data(){
        return{
            iconUrl:require('../assets/common/img/defaulte.png')
        }
    },
    beforeMount(){
        // this.iconUrl 
    }
}
</script>
<style lang="sass" scoped>
    .aside
        width: 1rem
        height: 100vh
        display: flex
        flex-direction: column
        justify-content: space-between
        background-color: #198CFF
        border-radius: 0 3% 3% 0
        box-shadow: 0 0 12px #198CFF;
        ul
            height: 5rem
            

        ul li
            width: .3rem
            height: .3rem
            color: #FEFEFF
            margin: .3rem auto
        .icon
           
            height: 1rem
            border-radius: 50%
            display: flex
            justify-content: center
            align-itmes: center
            img
                display: inline-block
                width: 1rem
                border-radius: 50%
        .menu
            width: 1rem
            height: 1rem
            
            margin-bottom: .2rem
            display: flex
            flex-direction: row
            align-items: center
            justify-content: center
            span::before
                content: ''
                width: .1rem
                height: .1rem
                display: block
                border-radius: 50%
                background-color: #FEFEFF
                
            span::after
                content: ''
                width: .1rem
                height: .1rem
                display: block
                border-radius: 50%
                background-color: #FEFEFF
                
    
</style>
