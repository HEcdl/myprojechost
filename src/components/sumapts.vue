<template>
    <div class="cuenta">
        <h2>Contador: {{ count }}</h2>
        <button @click="increment">Incrementar</button>
        <!--  <button @click="zero">En Cero 0</button>
 -->  <button @click="decrement">Decrementar</button>

    </div>
</template>

<script>
export default {
    data() {
        return {
            count: 0
        }
    },
    methods: {
        increment() {
            this.count+=10
        },
        decrement() {
            this.count-=10
        }
        /*   zero(){
              
          } */
    }
}
</script>

<style scoped>
h2 {
    color: black;
}
.cuenta{
    width: 100%;
    background-color: blue;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1rem;
    margin-top: 1rem;
}
</style>