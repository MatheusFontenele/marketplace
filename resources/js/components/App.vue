<template>
    <div class="overflow-x-hidden">
        <Navbar />
        <main class="flex flex-col">
            <sidebar />
            <wrapper />
        </main>
        <Footer />
    </div>
</template>

<script>
import Navbar from './Navbar.vue'
import Sidebar from './Sidebar.vue'
import Wrapper from './Wrapper.vue'
import Footer from './Footer.vue'
    export default {
        components: {
            Navbar,
            Sidebar,
            Wrapper,
            Footer
        },

       mounted() {
            console.log('Component mounted.')
        }
    }
</script>
