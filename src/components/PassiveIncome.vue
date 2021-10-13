<template>
    <h1>
        Meu nome é: {{ nome }}
    </h1>
</template>

<script>
export default {
    name: 'PassiveIncome',
    data(){
        return {
            nome: 'Ainda não sei'
        }
    },
    created(){
        this.nome = 'Tiago'
    }
}
</script>