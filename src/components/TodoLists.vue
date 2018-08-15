<template>
    <div class='todos'>
        <div class="main-title">
            <div class="tips">
                <span>Mvp</span>
            </div>
            <h1>Design</h1>
        </div>
        <div class="todo-lists">
            <ul>
                <li></li>
                <li></li>
                <li></li>
                <li></li>
            </ul>
            <div>
                <ul>
                    <li></li>
                    <li></li>
                    <li></li>
                </ul>
            </div>
        </div>
        <div class="done-lists"></div>
        <div class="more"></div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="sass" scoped>
    .todos
        height: 100vh
        flex-grow: 1
        // border: 1px solid red
        .main-title,.todo-lists,.done-lists
            height: 18vh
            border-bottom: 1px solid #CAC9CA
        .main-title
            
            padding: .3rem
            .tips
                display: flex
                height: .2rem
                margin-bottom: .2rem
                span
                    font-size: .2em;

            h1
                font-size: .5em

</style>
