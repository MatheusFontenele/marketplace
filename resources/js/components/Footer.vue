<template>
    <footer class="w-screen h-full bg-black ">
        <div
            style="background: linear-gradient(90deg,#f36300 50%,#622181 0)" class="w-full h-4"
        >
            <div class="w-full px-20 max-w-7xl mx-auto">
                <ul class="flex mx-auto justify-between ">
                    <li class="bg-[#f36300] w-full h-4 transition-[height]">
                        <p class="opacity-0 h-full flex items-center justify-center text-xl text-slate-200 font-medium" href="">Na mira</p>
                    </li>
                    <li class="bg-[#126D97] w-full h-4  transition-[height]">
                        <p class="opacity-0 h-full flex items-center justify-center text-xl text-slate-200 font-medium" href="">Noticias</p>
                    </li>
                    <li class="bg-[#B30000] w-full h-4 transition-[height]">
                        <p class="opacity-0 h-full flex items-center justify-center text-xl text-slate-200 font-medium" href="">Culinaria</p>
                    </li>
                    <li class="bg-[#383D9E] w-full h-4 transition-[height]">
                        <p class="opacity-0 h-full flex items-center justify-center text-xl text-slate-200 font-medium" href="">Politica</p>
                    </li>
                    <li class="bg-[#728A00] w-full h-4 transition-[height]">
                        <p class="opacity-0 h-full flex items-center justify-center text-xl text-slate-200 font-medium" href="">Esports</p>
                    </li>
                    <li class="bg-[#622181] w-full h-4 transition-[height]">
                        <p class="opacity-0 h-full flex items-center justify-center text-xl text-slate-200 font-medium" href="">Podcast</p>
                    </li>
                </ul>
            </div>
        </div>
        <div class="w-full flex justify-center items-center">
            <div class="max-w-6xl flex flex-col md:flex-row md:gap-12 p-8 mx-auto">
                <div class="flex flex-col p-4">
                    <div class=""><img src="../../images/logo.png" alt=""/></div>
                    <div class="flex items-center justify-center gap-4">
                        <ph-instagram-logo :size="32" color="#f7f7f7" weight="bold" />
                        <ph-facebook-logo :size="32" color="#f7f7f7" weight="bold" />
                        <ph-twitter-logo :size="32" color="#f7f7f7" weight="bold" />
                        <ph-youtube-logo :size="32" color="#f7f7f7" weight="bold" />
                    </div>
                </div>
                <div class="text-white p-4">
                    <span class="text-xl">imirante.com</span>
                    <ul class="mt-4">
                        <li><a href="">Esporte</a></li>
                        <li><a href="">Na mira</a></li>
                        <li><a href="">Culinaria</a></li>
                        <li><a href="">Noticias</a></li>
                        <li><a href="">Videos</a></li>
                        <li><a href="">Podcasts</a></li>
                    </ul>
                </div>
                <div class="text-white p-4">
                    <span class="text-xl">Grupo Mirante</span>
                    <ul class="mt-4">
                        <li><a href="">Mirante AM</a></li>
                        <li><a href="">Mirante FM</a></li>
                        <li><a href="">TV Mirante</a></li>
                    </ul>
                </div>
                <div class="text-white flex flex-col max-w-xs p-4">
                    <span class="text-xl mb-4">Fale com a redação</span>
                    <span class="w-[250px]">Mande sua mensagem para redação agora mesmo</span>
                    <span>(98) 99209-2383</span>
                    <span>imirante@mirante.com.br</span>
                </div>
            </div>
        </div>
        <div class="text-white  max-w-6xl mx-auto p-4 border-t border-t-gray-600">
            <div class="flex flex-col lg:flex-row justify-between">
                <span>©2022 - Todos os direitos reservados.</span>

                <div class="flex gap-4">
                    <span>política de privacidade e segurança</span>
                    <span>anuncie conosco</span>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
import { PhInstagramLogo,PhFacebookLogo, PhTwitterLogo, PhYoutubeLogo } from "phosphor-vue";
import logoIcon from "../../images/logo.png"
    export default {
        name: "App",
        components: {
            PhInstagramLogo,
            PhFacebookLogo,
            PhTwitterLogo,
            PhYoutubeLogo
        },
        data(){
            return [
                logoIcon
            ]
        },
        mounted() {
            console.log('nav Component mounted.')
        }
    }

</script>
