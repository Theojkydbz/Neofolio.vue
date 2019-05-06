<template>

    <div>

        <transition name="fade" appear mode="out-in">
            
            <div class="ui message sucess" v-if="visible" key="visible">

                Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae commodi quae, minus incidunt autem illo? Quis porro deleniti earum non at recusandae quo, perferendis accusamus quia, similique quisquam molestiae repudiandae.

            </div>

            <div class="ui message sucess" v-else key="invisible">

                Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae commodi quae, minus incidunt autem illo? Quis porro deleniti earum non at recusandae quo, perferendis accusamus quia, similique quisquam molestiae repudiandae.

            </div>

        </transition>

        <button @click="toggle"> Toggle </button>

        <ul>
            <transition-group name="fade" tag="ul">

                <li v-for="item in items" :key="item"> {{ item }} </li>

            </transition-group>

        </ul>

        <button @click="add"> Add </button>

    </div>

</template>

<script>

export default {

    data() {
        
        return {

            visible:true,

            items:[1,2,3,4,5]

        }

    },

    methods: {
        add: function() {

            this.items.push(Math.random())

        },

        toggle: function () {

            this.visible = !this.visible

        }

    }
    
}

</script>

<style>

.fade-enter-active, .fade-leave-active{

    transition: opacity .5s, transform .5s;

}

.fade-enter, .fade-leave-active{

   opacity: 0;
   
   transform: translateX(20px);
}

</style>
