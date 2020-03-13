<template>

    <div class="tarjeta">
        <img :src= 'imagen'/>
        <p>{{nombre}}</p>
    </div>

</template>
<script>
    export default {
    name: "tarjetaComponente",
     props: {
        nombre: String,
        imagen: String
      },
};

</script>

<style scoped>
    .tarjeta{
        display: flex;
        align-items: center;
        padding: 10px 50px;
    }
    .tarjeta img{
        border-radius: 50%;
        width: 100px;
    }
    .tarjeta p{
        font-size: 30px;
        color: green;
        margin-left: 30px;
    }
    </style>
