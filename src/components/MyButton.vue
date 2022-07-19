<template>
    <div>
        <h2>{{msg}}</h2>
        <button @click="count++">砸了{{count}}次</button>
    </div>
</template>
<script>
    export default{
        name:'',
        data() {
            return {
                msg:'铁锤妹妹~',
                count:0
            }
        }
    }
</script>
<style scoped>
    h2{
        color: hotpink;
    }
    button{
        color: aqua;
    }
</style>
