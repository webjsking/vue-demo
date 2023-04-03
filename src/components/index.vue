<template>
    <div>
        第一次修改
        {{ msg }}
    </div>
</template>

<script setup>
import { ref } from "vue";


 const msg = ref('修改第二次')
</script>