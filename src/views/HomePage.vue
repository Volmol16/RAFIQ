<template>
    <div class="">
        <header class="mt-11 container max-w-[1280px] mx-auto">
            <AppHead />
        </header>
        <main class="container max-w-[1280px] mx-auto">
            <AppHero />
        </main>
        <section class="container max-w-[1280px] mx-auto mt-11">
            <ExplorePower />
        </section>
        <section class="mt-11 flex flex-col items-center">
            <img class="absolute bg-cover bg-center mx-auto -z-10 rounded-2xl" src="/img/img_CreateOwn.png" alt="">
            <div class="relative top-[110px] container max-w-[1280px] mx-auto">
                <CreateOwn />
            </div>
        </section>
        <section class="container max-w-[1280px] mx-auto mt-40">
            <UseCasec />
        </section>
        <section class="container max-w-[1280px] mx-auto mt-40">
            <TryRafiq />
        </section>
        <section class="container max-w-[1280px] mx-auto mt-40">
            <UnlockThePower />
        </section>
        <div class="mt-40 max-w-full mx-auto bg-[#001E20] py-8">
            <section class="container max-w-[1280px] mx-auto">
                <ChoosePerfectPlan />
            </section>
        </div>
        <section class="container max-w-[1280px] mx-auto mt-16">
            <FrequentlyAsked />
        </section>
        <footer class="mt-16 bg-[#0A0A0A]">
            <div class="container max-w-[1280px] mx-auto ">
                <Footer />
            </div>
        </footer>
    </div>
</template>
<script setup>
import AppHead from '@/components/AppHead.vue'
import AppHero from '@/components/AppHero.vue'
import ExplorePower from '@/components/ExplorePower.vue';
import CreateOwn from '@/components/CreateOwn.vue';
import UseCasec from '@/components/UseCasec.vue';
import ChoosePerfectPlan from '@/components/ChoosePerfectPlan.vue';
import TryRafiq from '@/components/TryRafiq.vue';
import UnlockThePower from '@/components/UnlockThePower.vue';
import FrequentlyAsked from '@/components/FrequentlyAsked.vue';
import Footer from '@/components/Footer.vue'
</script>
