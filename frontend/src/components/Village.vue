<template>
    <ul class="village-gallery">
        <li v-for ="(name,villager_count,index) in villagers" :key="index">
            
        </li>
    </ul>



</template>
<style>
 li{
    margin: 10px 10px 10px 10px
 }
</style>

<script>
import axios from 'axios'
export default{
    data(){
        return{
            
        }
    },
    methods: {
        getVillages(){
            
        }

    }
}

</script>

