<!--  -->
<template>
    <div>
        <div>
            <span v-for="key in data" :key="key">
                {{item.text}}
            </span>
        </div>
    </div>
</template>

<script>
export default {
  data () {
    return {
        data:[
            {text:'学习 javascript'},
            {text:'学习 vue'},
            {text:'整个项目'}
        ]
    };
  },

 
}

</script>
<style lang='scss' scoped>

</style>