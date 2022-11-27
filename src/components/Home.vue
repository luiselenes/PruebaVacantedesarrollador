<template>
    <div id="principal"> 
        <span class="textpri">Descubre lo más nuevo en moda para mujer </span>
        <br>
        <span class="textsec">Renueva tu guardarropa con los tonos, diseños y tendencias de la temporada otoño-invierno.</span>
        <br>
        <img src="../assets/logo.jpg" class="imgprincipal">
    </div>
</template>
<script>
export default {
  name: 'app-home',
}
</script>
<style>
    #principal{
        margin-left: 20%;
        margin-top: 4%;
        font-family:Sans-serif;
    }
    .textpri{
        font-weight: bold;
        font-size: 30px;
    }

    .textsec{
        padding-top: 30px;
    }
    .imgprincipal{
        margin-top: 10px;
        height: 300px;
        width: 1300px;
        border-color: black;
    }
  
</style>