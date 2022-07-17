<template>
    <div class="w-full h-full mt-20">
        <div class="w-full bg-gray-100 h-full ">
            <div class="w-full px-10 max-w-6xl mx-auto">
                <section class="flex items-center justify-center gap-4 flex-col p-8 border-b border-b-gray-300">
                    <span class="text-gray-600 text-lg">VIOLÊNCIA EM ALTA</span>

                    <h1 class="text-[#126D97] text-4xl text-center font-bold">Três assassinatos e duas tentativas de homicídio são registrados em menos de 24h na Grande Ilha</h1>
                    <span class="text-gray-500 text-center">Segundo a polícia, os crimes foram ocasionados por arma de fogo e branca e entre as vítimas há dois adolescentes.</span>
                </section>

                <div class="flex gap-4 py-8 justify-center items-center">
                    <div class="">
                        <span class="text-3xl text-gray-500 font-medium border-b-4  border-b-[#126D97]">AÇÃO CRIMINOSA</span>
                        <h1 class="text-4xl my-4 text-gray-500 font-bold">Bandidos realizam assaltos residências e coletivos em São Luís</h1>
                        <p class="text-base text-gray-500">
                            Os criminosos, além de roubar objetos de valor, levaram dinheiro e, segundo a polícia, uma das vítimas se identificou como promotor de Justiça aposentado.
                        </p>

                        <ul class="flex flex-col my-4 gap-2 max-w-sm list-disc">
                            <li class="">
                                <p class="text-blue-500 whitespace-nowrap overflow-hidden text-ellipsis cursor-pointer">
                                    Dois homens são presos suspeitos de roubar mais de 40 metros de cabos de fiação telefônica em Paço do Lumiar
                                </p>
                            </li>
                            <li class="hover:undeline">
                                <p class="text-blue-500 whitespace-nowrap overflow-hidden text-ellipsis cursor-pointer">
                                    Jovem de 18 anos é preso suspeito de roubar celular em São José de Ribamar
                                </p>
                            </li>
                            <li class="hover:undeline">
                                <p class="text-blue-500 whitespace-nowrap overflow-hidden text-ellipsis cursor-pointer">
                                    Criminosos roubam caminhão-tanque carregado com cerca de 25 mil litros de combustível na BR-222
                                </p>
                            </li>
                        </ul>
                    </div>
                    <img class="max-w-xl" src="../../images/banner.webp" alt="">
                </div>
            </div>
        </div>
        <div class="w-full flex my-8">
            <div class="mx-auto">
                <div class="">
                    <span class="text-lg">ESTUDOS SOBRE O MA</span>

                    <h1>Maranhense é contratado por multinacional após produzir estudo</h1>
                    <span>Maranhense se emociona ao conquistar aposentadoria após anos de trabalho na roça e vídeo viraliza</span>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
