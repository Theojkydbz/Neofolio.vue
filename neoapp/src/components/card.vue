<template>
    <article class="card">

        <div>
            <h2>{{title}}</h2>
        </div>
        <div>
            <p>{{exerpt}}</p>
        </div>

    </article>
</template>

<script>
    export default {
        props : {
            title :{
                type :String,
                required : true,
            },
            exerpt :{
                type : String,
                required : true,
            }
        },
        data() {
            return {

            }
        }
    }
</script>

<style lang="scss">
    .card {
        background-color: #cfcfcf;
        height: 300px;
        width: 200px;
        border-radius: 3px;
        display: grid;
        grid-template-rows: 2fr 2fr;
        box-shadow: 0 20px 40px rgba(20, 20, 20, 0.2)
    }
</style>