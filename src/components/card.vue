<template>
    <div class="kursi">
        <a href="" v-on:click.prevent="$emit('changepicture', cardimage, cardTitle, cardPrice )">
            <img :src="require('@/assets/img/' + cardimage + '.png')" alt="">
        </a><p></p>
        <div class="text">
        <b><center>{{cardTitle}}</center></b>
        <p> <center> IDR {{cardPrice}} </center></p>
        </div>
    </div>
  
</template>

<script>
export default {

    name : 'cardComponent',
    props : ["cardTitle", "cardPrice", "cardimage"]
}

</script>

<style scoped>
.kursi{
    background-color:antiquewhite;
    border: 1px solid;
    border-radius: 5px;
}
.text{
    align-items: center;
    
}

</style>