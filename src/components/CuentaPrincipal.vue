<template>
    <h2>Saldo: {{saldo}}</h2>
    <h2>Tipo de cuenta: {{tipo}}</h2>
    <h3>Cuenta {{estado? 'activa' : 'desactivada'}}</h3>

</template> 

<script>
export default {
    name:'CuentaPrincipal',
    data() {
        return {
            saldo: 1000,
            tipo:'Visa',
            servicios:['Retiro','Abono','Transferencia'],
            estado:true
        }
    },

}
</script>

<style>

</style>