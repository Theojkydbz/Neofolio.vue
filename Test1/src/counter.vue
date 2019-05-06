<template>
    
    <div class="counter">

        {{ count }}

        <div class="counter__button" @click="increment"> + </div>
         
    </div>

</template>


<script>
export default {
    
    data() {

        return{

            count: 0

        }
        
    },

    methods: {
        
        increment(){

            this.count++
        }

    }

}
</script>

<style>

    .counter{

        font-weight: bold;

        width: 10vh;

        height: 3vh;

        background-color: beige;

        text-align: center;

    }

    .counter__button{

        border-radius: 5px;

        background-color: blueviolet;

        border: 2px solid blue;

    }

</style>

