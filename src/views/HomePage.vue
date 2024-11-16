<template>
    <div class="container max-w-[1280px] mx-auto">
        <header class="mt-11">
            <AppHead />
        </header>
        <main>
            <AppHero />
        </main>
        <section>
            <ExplorePower />
        </section>
    </div>
</template>
<script setup>
import AppHead from '@/components/AppHead.vue'
import AppHero from '@/components/AppHero.vue'
import ExplorePower from '@/components/ExplorePower.vue';
</script>
