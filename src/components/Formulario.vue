<script setup>
</script>

<template>
    <div class="md:w-1/2">
        <h2 class="font-black text-3xl text-center">Seguimiento Pacientes</h2>
        <p class="text-lg mt-5 text-center mb-10">
            Añade pacientes y
            <span class="text-indigo-600">Adminístralos</span>
        </p>
        <form class="bg-white shadow-md rounded-lg py-10 px-5 mb-10">
            <label 
                for="mascota"
                class="block text-gray-700 uppercase font-bold">
                Nombre mascota
            </label>
            <input
                id="mascota"
                type="text"
                placeholder="Nombre de la mascota"
                class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md"
            />
        </form>
    </div>
</template>