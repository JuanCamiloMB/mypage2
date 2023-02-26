<script>
    import arrow_image from '../assets/down_arrow.png'
    
    export default {
        data(){
            return{
                arrow: arrow_image
            }
        }
    }
</script>

<template>
    <div id="name_section">
        <!-- Big text with name -->
        <div id="name_txt">Juan Camilo Manjarrés Baena</div> 
        <!-- Arrow image -->
        <div id="arrow">
            <img :src="arrow" alt="V">
        </div>
    </div>
</template>

<style scoped>
    #name_section {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }

    #name_txt {
        color: white;
        font-size: 15vh;
        text-align: center;
    }

    #arrow {
        display: flex; 
        margin-top: 10vh;
        align-content: center;
        justify-content: center;
    }

</style>