<template>
    <div>
        <nav class="relative container mx-auto p-6">
            <div class="flex items-center justify-between">
                <div class="pt-2">
                    <img src="../assets/vue.svg" alt="">
                </div>
                <div class="hidden md:flex space-x-6">
                    <a href="#" class="hover:text-orange-600">Pricing</a>
                    <a href="#" class="hover:text-orange-600">Product</a>
                    <a href="#" class="hover:text-orange-600">About Us</a>
                    <a href="#" class="hover:text-orange-600">Careers</a>
                    <a href="#" class="hover:text-orange-600">Community</a>
                </div>
                <a href="#"
                    class="hidden md:block p-3 px-6 pt-2 text-white bg-orange-600 rounded-full baseline hover:bg-orange-400">Get
                    Started</a>

                <button id="menu-btn" class="block hamburger md:hidden focus:outline-none">
                    <span class="hamburger-top"></span>
                    <span class="hamburger-middle"></span>
                    <span class="hamburger-bottom"></span>
                </button>
            </div>

            <div class="md:hidden">
                <div id="menu"
                    class="absolute flex-col items-center self-end hidden py-8 mt-10 space-y-6 font-bold bg-white sm:w-auto sm:self-center left-6 right-6 d">
                    <a href="#" class="hover:text-orange-600">Pricing</a>
                    <a href="#" class="hover:text-orange-600">Product</a>
                    <a href="#" class="hover:text-orange-600">About Us</a>
                    <a href="#" class="hover:text-orange-600">Careers</a>
                    <a href="#" class="hover:text-orange-600">Community</a>
                </div>
            </div>
        </nav>

        <section id="hero">
            <div class="container flex flex-col-reverse md:flex-row px-6 mx-auto mt-5 md:mt-10 space-y-0 md:space-y-0">
                <div id="left" class="flex flex-col mb-32 space-y-12 md:w-1/2">
                    <h1 class="max-w-md text-4xl font-bold text-center md:text-5xl md:text-left">
                        Bring everyone together to build better products
                    </h1>
                    <p class="max-w-sm text-center text-gray-400 md:text-left">
                        Manage makes it simple for software teams to plan day-to-day tasks while keeping the larger team
                        goal in view
                    </p>
                    <div class="flex justify-center md:justify-start">
                        <a href="#"
                            class="p-3 px-6 pt-2 text-white bg-orange-600 rounded-full baseline hover:bg-orange-400">Get
                            Started</a>
                    </div>
                </div>
                <div id="img" class="md:w-1/2">
                    <img src="https://pocketbase.io/api/files/BHKW36mJl3ZPt6z/UP06yiygImYTMCI/Jgihz6urldOM1ve3EyXbHWYaVqVh0hkK.jpg"
                        alt="" class="">
                </div>
            </div>
        </section>

        <section id="features">
            <div class="container flex flex-col px-4 mx-auto mt-10 space-y-12 md:space-y-0 md:flex-row">
                <div class="flex flex-col space-y-12 md:w-1/2">
                    <h2 class="max-w-md text-4xl font-bold text-center md:text-left">
                        What's different about Mananger?
                    </h2>
                    <p class="max-w-sm text center text-gray-400 md:text-left">
                        Manage makes it simple for software teams to plan day-to-day tasks while keeping the larger team
                        goal in view Manage makes it simple for software teams to plan day-to-day tasks while keeping
                        the larger team
                        goal in view
                    </p>
                </div>
                <div class="flex flex-col space-y-8 md:w-1/2">
                    <div class="flex flex-col space-y-3 md:space-y-0 md:space-x-6 md:flex-row">
                        <div class="rounded-l-full bg-orange-400 md:bg-transparent">
                            <div class="flex items-center space-x-2">
                                <div class="px-4 py-2 text-white rounded-full md:py-1 bg-orange-600">01</div>
                                <h3 class="text-base font-bold md:mb-4 md:hidden">
                                    Track company-wide prgress
                                </h3>
                            </div>
                        </div>
                        <div>
                            <h3 class="hidden mb-4 text-lg font-bold md:block">
                                Track company-wide prgress
                            </h3>
                            <p class="text-gray-500 text-sm">
                                Manage makes it simple for software teams to plan day-to-day tasks while keeping the
                                larger
                                team

                            </p>
                        </div>
                    </div>
                    <div class="flex flex-col space-y-3 md:space-y-0 md:space-x-6 md:flex-row">
                        <div class="rounded-l-full bg-orange-400 md:bg-transparent">
                            <div class="flex items-center space-x-2">
                                <div class="px-4 py-2 text-white rounded-full md:py-1 bg-orange-600">02</div>
                                <h3 class="text-base font-bold md:mb-4 md:hidden">
                                    Advanced built-in report
                                </h3>
                            </div>
                        </div>
                        <div>
                            <h3 class="hidden mb-4 text-lg font-bold md:block">
                                Advanced built-in report
                            </h3>
                            <p class="text-gray-500 text-sm">
                                Manage makes it simple for software teams to plan day-to-day tasks while keeping the
                                larger
                                team
                                goal in view Manage makes it simple for software teams to plan day-to-day tasks while
                                keeping the larger team
                                goal in view Manage makes it simple for software teams to plan day-to-day tasks while
                                keeping the larger team
                                goal in view Manage makes it simple for software teams to plan day-to-day tasks while
                                keeping the

                            </p>
                        </div>
                    </div>
                    <div class="flex flex-col space-y-3 md:space-y-0 md:space-x-6 md:flex-row">
                        <div class="rounded-l-full bg-orange-400 md:bg-transparent">
                            <div class="flex items-center space-x-2">
                                <div class="px-4 py-2 text-white rounded-full md:py-1 bg-orange-600">03</div>
                                <h3 class="text-base font-bold md:mb-4 md:hidden">
                                    Track company-wide prgress
                                </h3>
                            </div>
                        </div>
                        <div>
                            <h3 class="hidden mb-4 text-lg font-bold md:block">
                                Track company-wide prgress
                            </h3>
                            <p class="text-gray-500 text-sm">
                                Manage makes it simple for software teams to plan day-to-day tasks while keeping the
                                larger
                                team
                                goal in view Manage makes it simple for software teams to plan day-to-day tasks while
                                keeping the larger team
                                goal in view Manage makes it simple for software teams to plan day-to-day tasks while
                                keeping the larger team
                                goal in view Manage makes it simple for software teams to plan day-to-day tasks while

                            </p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <section>
            <div class="max-w-6xl px-5 mx-auto mt-32 text-center">
                <h2 class="text-4xl font-bold text-center">What's different about manage?</h2>
                <div class="flex flex-col mt-24 md:flex-row md:space-x-6">
                    <div class="flex flex-col items-center p-6 space-y-6 rounded-lg bg-gray-100 md:w-1/3">
                        <img src="../assets/vue.svg" alt="" class="w-16 -mt-14">
                        <h5 class="text-lg font-bold">Anisha Li</h5>
                        <p class="text-sm text-black"> goal in view Manage makes it simple for software teams to plan
                            day-to-day tasks while
                            keeping the larger team
                            goal in view Manage makes it simple for software teams to plan day-to-day tasks while</p>
                    </div>
                    <div class="hidden md:flex flex-col items-center p-6 space-y-6 rounded-lg bg-gray-100 md:w-1/3">
                        <img src="../assets/vue.svg" alt="" class="w-16 -mt-14">
                        <h5 class="text-lg font-bold">Anisha Li</h5>
                        <p class="text-sm text-black"> goal in view Manage makes it simple for software teams to plan
                            day-to-day tasks while
                            keeping the larger team
                            goal in view Manage makes it simple for software teams to plan day-to-day tasks while</p>
                    </div>
                    <div class="hidden md:flex flex-col items-center p-6 space-y-6 rounded-lg bg-gray-100 md:w-1/3">
                        <img src="../assets/vue.svg" alt="" class="w-16 -mt-14">
                        <h5 class="text-lg font-bold">Anisha Li</h5>
                        <p class="text-sm text-black"> goal in view Manage makes it simple for software teams to plan
                            day-to-day tasks while
                            keeping the larger team
                            goal in view Manage makes it simple for software teams to plan day-to-day tasks while</p>
                    </div>
                </div>
                <div class="my-16">
                    <a href="#"
                        class="p-3 px-6 pt-2 text-white bg-orange-600 rounded-full baseline hover:bg-orange-400">Get
                        Started</a>
                </div>
            </div>
        </section>

        <section id="cta" class="bg-orange-400">
            <div
                class="container flex flex-col items-center justify-between px-6 py-24 mx-auto space-y-12 md:py-12 md:flex-row md:space-y-0">
                <h2
                    class="text-5xl font-bold leading-tight text-center text-white md:text-4xl md:max-w-xl md:text-left">
                    Simplify how your team works today!
                </h2>
                <div>
                    <a href="#"
                        class="p-3 px-6 pt-2 text-orange-600 bg-white shadow-2xl rounded-full baseline hover:bg-orange-900">Get
                        Started</a>
                </div>
            </div>

        </section>

        <section>
            <footer class="bg-gray-700">
                <div
                    class="container flex flex-col-reverse justify-between px-6 py-10 mx-auto space-y-8 md:flex-row md:space-y-0">
                    <div
                        class="flex flex-col-reverse items-center justify-between space-y-12 md:flex-col md:space-y-0 md:items-start">

                        <div class="mx-auto my-6 text-center text-white md:hidden"> Copyright &copy; 2022, all rights
                            reserved</div>

                        <div class=""><img src="../assets/vue.svg" class="h-12" alt=""></div>

                        <div class="flex justify-center space-x-5">
                            <a href="" class=""><img src="../assets/vue.svg" alt=""></a>
                            <a href="" class=""><img src="../assets/vue.svg" alt=""></a>
                            <a href="" class=""><img src="../assets/vue.svg" alt=""></a>
                            <a href="" class=""><img src="../assets/vue.svg" alt=""></a>
                        </div>
                    </div>

                    <div class="flex justify-around space-x-32">
                        <div class="flex flex-col space-y-3 text-white">
                            <a href="" class="hover:text-orange-400">Home</a>
                            <a href="" class="hover:text-orange-400">Pricing</a>
                            <a href="" class="hover:text-orange-400">Prodcuts</a>
                            <a href="" class="hover:text-orange-400">About</a>
                        </div>
                        <div class="flex flex-col space-y-3 text-white">
                            <a href="" class="hover:text-orange-400">Carrers</a>
                            <a href="" class="hover:text-orange-400">Community</a>
                            <a href="" class="hover:text-orange-400">Privacy Policy</a>
                            <a href="" class="hover:text-orange-400">Help</a>
                        </div>
                    </div>

                    <div class="flex flex-col justify-between">
                        <form action="">
                            <div class="flex space-x-3">
                                <input type="text" class="flex-1 px-4 rounded-full focus:outline-none"
                                    placeholder="Updated in your inbox">
                                <button
                                    class="px-6 py-2 text-white rounded-full bg-orange-500 hover:bg-oraange-200 focus:outline-none">Go</button>
                            </div>
                        </form>
                        <div class="hidden text-white md:block">
                            Copyright &copy; 2022, all rights reserved
                        </div>
                    </div>

                </div>
            </footer>
        </section>

    </div>
</template>

<script setup>
import { onMounted } from 'vue';


onMounted(() => {
    const btn = document.getElementById('menu-btn')
    const nav = document.getElementById('menu')
    btn.addEventListener('click', () => {
        btn.classList.toggle('open')
        nav.classList.toggle('flex')
        nav.classList.toggle('hidden')
    })
})
</script>

<style lang="scss" scoped>

</style>