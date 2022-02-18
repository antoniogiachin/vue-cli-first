<template>
    <div class="img-jumbo">
        <img src="../assets/jumbo.png" >
        <button>C'e' tanto da imparare!</button>
    </div>
</template>

<script>
export default {

    name : 'newJumbo',

}

</script>

<style scoped>

    .img-jumbo{
        width: 100vh;
        height: 300px;
        min-width: 500px;
        position: relative;
    }

    .img-jumbo img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 60px;
        filter: opacity(0.8);
    }

    .img-jumbo button{
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        display: inline-block;
        border: none;
        background-color: #fff;
        padding: 20px;
        border-radius: 40px;
        cursor: pointer;
        font-weight: bold;
    }

    .img-jumbo button:hover{
        padding: 22px;
        box-shadow: 2px 2px 6px #000;
    }

</style>