<script setup>
    const props = defineProps(['tarefasPendentes']);
</script>

<template>
    <header class="p-5 my-4 bg-light rounded">
        <h1>Tarefas</h1>
        <p>Você possui {{ props.tarefasPendentes }} tarefas pendentes</p>
    </header>
</template>