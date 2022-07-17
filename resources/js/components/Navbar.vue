<template>
    <header class="w-screen h-20 bg-[#03ABF8] ">
        <div class=" h-full px-20 flex items-center justify-between max-w-7xl mx-auto">
            <ph-list :size="38" weight="bold" color="#FFF"  />
            <img src="../../images/logo.png" alt="">
            <ph-magnifying-glass :size="38" color="#f7f7f7" weight="bold"/>
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
                logoIcon
            ]
        },
        mounted() {
            console.log('nav Component mounted.')
        }
    }

</script>
