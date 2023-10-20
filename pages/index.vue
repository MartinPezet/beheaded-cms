<template>
    <div>
        <h1>Hello world</h1>
        <button @click="addCount(1)">Count: {{ count }}</button>
    </div>
</template>



<script setup lang="ts">
let count = ref(0);

function addCount(amount: number) {
    count.value += amount;
}
</script>