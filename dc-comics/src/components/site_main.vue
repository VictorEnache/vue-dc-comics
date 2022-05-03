<template>
    <main id="site_main">
        <div class="container">
            CONTENT GOES HERE
        </div>
    </main>
</template>

<script>
    export default{
        name:'site_main'
    }
    
</script>

<style lang="scss">
#site_main{
    height: 90px;
    background-color: black;
    color: white;
    
    .container{
        height: 100%;
        width: 1080px;
        margin: auto;
        display: flex;
        align-items: center;
    }
}
</style>
