<template>
    <header class="fixed top-0 z-50">
        <nav class="bg-buffetred text-white lg:text-gray-600 lg:bg-buffetgrey-300 fixed w-full h-16 top-0">
            <div class="lg:mx-10 mx-auto px-4">
                <div class="flex justify-between">
                    <div class="flex space-x-4">
                        <!-- logo -->
                        <div>
                            <a href="#" class="flex items-center py-5 px-2 text-lg md:text-xl lg:text-2xl">
                                <span class="font-bold hover:text-black uppercase">Einkehr</span>
                            </a>
                        </div>

                        <!-- primary nav -->
                        <div class="hidden lg:flex items-center space-x-1 text-lg lg:text-2xl">
                            <a href="#kaufen" class="py-5 px-3 hover:text-black">Shop</a>
                            <a href="#media" class="py-5 px-3 hover:text-black">Medien</a>
                            <a href="#support" class="py-5 px-3 hover:text-black">Unterstützung</a>
                            <a href="#about" class="py-5 px-3 hover:text-black">Über uns</a>
                            <a href="#contact" class="py-5 px-3 hover:text-black">Kontakt</a>
                        </div>
                    </div>

                    <!-- mobile button goes here -->
                    <div class="lg:hidden flex items-center">
                        <button class="mobile-menu-button" id="burger">
                            <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                                stroke="currentColor">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="M4 6h16M4 12h16M4 18h16" />
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- mobile menu -->
            <div class="bg-buffetred text-white mobile-menu hidden lg:hidden" id="menu">
                <a href="#kaufen" class="block py-2 px-4 text-lg menuitem">Shop</a>
                <a href="#media" class="block py-2 px-4 text-lg menuitem">Medien</a>

                <a href="#support" class="block py-2 px-4 text-lg menuitem">Unterstützung</a>
                <a href="#about" class="block py-2 px-4 text-lg menuitem">Über uns</a>
                <a href="#contact" class="block py-2 px-4 text-lg menuitem">Kontakt</a>
            </div>
        </nav>
    </header>
</template>
<script>
export default {
    name: "navigation",
    methods: {


    },
}
</script>
<style></style>