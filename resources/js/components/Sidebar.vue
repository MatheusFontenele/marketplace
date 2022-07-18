<template>
    <aside class=" z-10 top-0 mt-10 lg:mt-0 lg:h-screen  lg:fixed ml-4 gap-2 flex items-center justify-center lg:flex-col">
        <a href="" class="bg-[#F36300] flex justify-center items-center w-12 h-12 rounded-full">
            <ph-film-slate :size="32" color="#f7f7f7" weight="bold" />
        </a>
        <a href="" class="flex justify-center items-center bg-[#126D97]  w-12 h-12 rounded-full">
            <ph-newspaper :size="32" color="#f7f7f7" />
        </a>
        <a href="" class="flex justify-center items-center bg-[#B30000] w-12 h-12 rounded-full">
            <ph-fork-knife :size="32" color="#f7f7f7" />
        </a>
        <a href="" class="flex justify-center items-center bg-[#383D9E]  w-12 h-12 rounded-full">
            <ph-scales :size="32" color="#f7f7f7" />
        </a>
        <a href="" class="flex justify-center items-center bg-[#728A00]  w-12 h-12 rounded-full">
            <ph-soccer-ball :size="32" color="#f7f7f7" />
        </a>
        <a href="" class="flex justify-center items-center bg-[#622181]  w-12 h-12 rounded-full">
            <ph-apple-podcasts-logo :size="32" color="#f7f7f7" />
        </a>
    </aside>
</template>
<script>
import {PhFilmSlate, PhNewspaper, PhForkKnife, PhScales, PhSoccerBall, PhApplePodcastsLogo} from 'phosphor-vue'

export default {
    name: 'App',
    components: {
        PhFilmSlate,
        PhNewspaper,
        PhForkKnife,
        PhScales,
        PhSoccerBall,
        PhApplePodcastsLogo
    }
}
</script>
