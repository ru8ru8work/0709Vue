<script>
import { RouterLink } from 'vue-router'
export default{

    components:{
        RouterLink
    }
}
</script>

<template>
    <div class="headerArea">
        <RouterLink class="routeItem" to="/">Home</RouterLink>
        <RouterLink class="routeItem" to="/VtextAndVmodel">VtextAndVmodel</RouterLink>
        <RouterLink class="routeItem" to="/VforAndVbind">VforAndVbind</RouterLink>
    </div>
</template>

<style scoped lang="scss">
.headerArea{
    width: 100%;
    height: 100%;
    background-color: #3f73b6;
    display: flex;

    .routeItem{
        font-size: 24px;
        color: white;
        text-decoration: none;
        cursor: pointer
    }
}

</style>