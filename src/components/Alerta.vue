<script setup>
import {computed} from 'vue';

const props= defineProps({
    alerta:{
        type: Object,
        required:true
    }
})

const isError = computed(()=>{
    console.log("sawd ",  props.alerta.tipo);
    return props.alerta.tipo === 'error'
})
</script>

<template>
    <div 
        :class="[isError ? ['bg-red-500', 'cursor-not-allowed'] : 'bg-green-500' ,'cursor-not-allowed']" 
        class="text-white text-center p-3 uppercase font-boldmn-3 rounded-md">
        {{alerta.mensaje}}
    </div>
</template>