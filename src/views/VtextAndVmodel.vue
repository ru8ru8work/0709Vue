<script>
export default{
    data(){ 
        return{
            text:"This is Text Code",
            modelTxt:"",
            modelRadio:"",
            modeCheck:[],
            modelSelect:"",
        }
    }
}
</script>

<template>

    <h1>Test</h1>

    <!--Vtext-->
    <p v-text="this.text"></p>
    <p>{{ this.text }}</p>

    <input type="text" v-model="this.modelTxt">
    <h3>{{ this.modelTxt }}</h3>

    <!--單選-->
    <label for="cool1">這是1</label>
    <input type="radio" id="cool1" v-model="this.modelRadio" value="這是1">
    <label for="cool2">這是2</label>
    <input type="radio" id="cool2" v-model="this.modelRadio" value="這是2">
    <label for="cool3">這是3</label>
    <input type="radio" id="cool3" v-model="this.modelRadio" value="這是3">
    <h3>{{ this.modelRadio }}</h3>

    <!--複選-->
    <label for="meat1">肉1</label>
    <input type="checkbox" id="meat1" v-model="this.modeCheck" value="肉1">
    <label for="meat2">肉2</label>
    <input type="checkbox" id="meat2" v-model="this.modeCheck" value="肉2">
    <label for="meat3">肉3</label>
    <input type="checkbox" id="meat3" v-model="this.modeCheck" value="肉3">
    <h1>{{ this.modeCheck }}</h1>


    <!--Select-->
    <select name="" id="" v-model="this.modelSelect">
        <option value="">請選擇</option>
        <option value="Tea">茶</option>
        <option value="coffee">咖啡</option>
        <option value="milk">牛奶</option>
    </select>
    <h3>{{ this.modelSelect }}</h3>




</template>

<style>

</style>
