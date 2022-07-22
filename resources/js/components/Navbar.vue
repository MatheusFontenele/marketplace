<template>
    <header class="w-screen h-20 bg-[#03ABF8] ">
        <div class=" h-full md:px-20 px-5 flex items-center justify-between max-w-7xl mx-auto">
            <button
                type="button"
                @click="openMenu"
                class="p-2 rounded-lg hover:brightness-125 hover:bg-slate-600" >
                <ph-list :size="38" weight="bold" color="#FFF"  />
            </button>

            <img src="../../images/logo.png" alt="">

            <button class="p-2 rounded-lg hover:brightness-125 hover:bg-slate-600" >
                <ph-magnifying-glass :size="38" color="#f7f7f7" weight="bold"/>
            </button>

        </div>
        <div
            style="background: linear-gradient(90deg,#f36300 50%,#622181 0)" class="w-full h-4"
        >
            <div class="w-full px-20 max-w-7xl mx-auto">
                <ul class="flex mx-auto justify-between ">
                    <li class="bg-[#f36300] w-full h-4 hover:h-8 transition-[height]">
                        <a class="opacity-0 h-full flex items-center justify-center hover:opacity-100 text-xl text-slate-200 font-medium" href="">Na mira</a>
                    </li>
                    <li class="bg-[#126D97] w-full h-4  hover:h-8 transition-[height]">
                        <a class="opacity-0 h-full flex items-center justify-center hover:opacity-100 text-xl text-slate-200 font-medium" href="">Noticias</a>
                    </li>
                    <li class="bg-[#B30000] w-full h-4 hover:h-8 transition-[height]">
                        <a class="opacity-0 h-full flex items-center justify-center hover:opacity-100 text-xl text-slate-200 font-medium" href="">Culinaria</a>
                    </li>
                    <li class="bg-[#383D9E] w-full h-4 hover:h-8 transition-[height]">
                        <a class="opacity-0 h-full flex items-center justify-center hover:opacity-100 text-xl text-slate-200 font-medium" href="">Politica</a>
                    </li>
                    <li class="bg-[#728A00] w-full h-4 hover:h-8 transition-[height]">
                        <a class="opacity-0 h-full flex items-center justify-center hover:opacity-100 text-xl text-slate-200 font-medium" href="">Esports</a>
                    </li>
                    <li class="bg-[#622181] w-full h-4 hover:h-8 transition-[height]">
                        <a class="opacity-0 h-full flex items-center justify-center hover:opacity-100 text-xl text-slate-200 font-medium" href="">Podcast</a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
import { PhList, PhMagnifyingGlass } from "phosphor-vue";
import logoIcon from "../../images/logo.png"
    export default {
        name: "App",
        components: {
            PhList,
            PhMagnifyingGlass,
        },
        data(){
            return [
                logoIcon,
                closeMenu,
                openMenu
            ]
        },
        methods: {
            closeMenu: function (){
                menuIsOpen.value = false
            },
            openMenu: function (){
                console.log('aberto');
                menuIsOpen.value = true
            }
        },
        mounted() {
            console.log('nav Component mounted.')
        }
    }
    const menuIsOpen = ref(true)

</script>
