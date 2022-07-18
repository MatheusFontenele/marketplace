<template>
    <div class="overflow-x-hidden">
        <Navbar />
        <main class="flex flex-col">
            <sidebar />
            <wrapper />
        </main>
    </div>
</template>

<script>
import Navbar from './Navbar.vue'
import Sidebar from './Sidebar.vue'
import Wrapper from './Wrapper.vue'
    export default {
        components: {
            Navbar,
            Sidebar,
            Wrapper
        },

       mounted() {
            console.log('Component mounted.')
        }
    }
</script>
