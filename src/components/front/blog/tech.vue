<template>
    <div class="blog">
        <div class="header-wrapper">
            技术
        </div>
        <div class="nav-wrapper">
        </div>
        <div>
            
        </div>
        <div>
            
        </div>
    </div>
</template>

<script>
export default {
    name: 'blog',
    data() {
        return {
            dataList: []
        }
    },
    created() {
        this.initData();
    },
    methods: {
        initData() {
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang='less'>
.header-wrapper{
    height: 100px;
    max-width: 1200px;
    margin: 0 auto;
    ul{
        overflow:hidden;
        padding-top: 39px ;
        li{
            float: left;
            cursor: pointer;
            padding: 0 10px;
        }
    }
}
</style>
