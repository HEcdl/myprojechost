<template>
    <div class="boton">
        <button v-on:click="$event => isVisible = !isVisible">Visibilidad de Informacion</button>
    </div>
    <div class='mimostrador'>
        <div v-if="isVisible" class="msg">

            {{ message }}

            <div class="imagen">
                <img src="/src/img/me.jpg" alt="Esta es mi foto">
            </div>
        </div>
    </div>

</template>

<script>
export default{
    name: "mostrar",
    data(){
        return {
            message: 'Hector Enrique Diaz Lira Carnet: 21-01517-1',
            isVisible: false
        }
    }
}
</script>

<style scoped>
.mimostrador{
    display: flex;
    justify-content: center;
}
.msg{
    width: 100%;
    display: grid;
    justify-content: center;
    align-items: center;
}
 .imagen{
    width: 250px;
    height: 350px;
    object-fit: cover;
    margin-top: 1rem;
    display: flex;
   
 }
  .boton{
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: rgb(43, 54, 76);
    margin-top: 1rem;
    margin-bottom: 1rem
 } 
 button{
    background-color: blue;
    
 }
</style>