<script>
import { RouterLink, RouterView } from 'vue-router'
export default{
    components:{
        RouterLink
    }
}
</script>

<template>
    <div class="headerArea">
        <RouterLink to="/">HomeView</RouterLink>
    </div>
</template>

<style scoped lang="scss">
.headerArea{
  widows: 100%;
  height: 100%;
}
</style>