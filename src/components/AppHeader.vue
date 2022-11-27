<template>
    <header>
        <div  id="tiraazul">
            <span id="letter">Descuentos exclusivos en línea</span>
        </div>
        <div id="tiraaramarilla">
            <img src="../assets/logo.jpg" class="imglogo">
            <select name="select" class="buscar">
                <option value="todo">Todo el sitio</option>
                <option value="juguetes" selected>Juguetes</option>
                <option value="hogarmuebles">Hogar y Muebles</option>
            </select>
                <input type="text" name="buscar" class="buscar" placeholder="Busca tus productos"/>
            </div>
    </header> 

</template>

<script>
export default {
  name: 'app-header',
}
</script>
<style>
    #letter{
        color: white;
       
    }
    #tiraazul{
        background-color: #006fb9;
        padding: 10px;
        text-align: center;
    }
    #tiraaramarilla{
        background-color: #FFDD2F;
    }
    .imglogo{
        height: 40px;
        width: 150px;
        margin: 10px;
        margin-left: 2% ;
    }
    .buscar{
        padding-top: 15px;
    }



</style>