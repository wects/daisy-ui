<template >
    <div class="container mx-auto">
        <div class="navbar">
            <div class="flex-1">
                <a class="btn btn-ghost normal-case text-xl">daisy UI</a>
            </div>
            <div class="flex-none">
                <ul class="menu menu-horizontal p-0">
                    <li><a>Item 1</a></li>
                    <li tabindex="0">
                        <a>
                            Parent
                            <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="20" height="20"
                                viewBox="0 0 24 24">
                                <path d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z" />
                            </svg>
                        </a>
                        <ul class="p-2 bg-base-100">
                            <li><a>Submenu 1</a></li>
                            <li><a>Submenu 2</a></li>
                        </ul>
                    </li>
                    <li><a>Item 3</a></li>
                </ul>
            </div>
        </div>
        <div class="hero min-h-screen"
            style="background-image: url(https://pocketbase.io/api/files/BHKW36mJl3ZPt6z/UP06yiygImYTMCI/Jgihz6urldOM1ve3EyXbHWYaVqVh0hkK.jpg);">
            <div class="hero-overlay bg-opacity-60"></div>
            <div class="hero-content text-neutral-content">
                <div class="max-w-md">
                    <h1 class="mb-5 text-5xl font-bold">Hello there</h1>
                    <p class="mb-5">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi
                        exercitationem
                        quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
                    <button class="btn btn-primary">Get Started</button>
                </div>
            </div>
        </div>


        <div class="flex my-10">
            <div class="card sm:w-full md:w-1/2 bg-base-100 shadow-xl mx-1">
                <figure><img src="https://placeimg.com/400/225/arch" alt="Shoes" /></figure>
                <div class="card-body">
                    <h2 class="card-title">Shoes!</h2>
                    <p>If a dog chews shoes whose shoes does he choose?</p>
                    <div class="card-actions justify-end">
                        <button class="btn btn-primary">Buy Now</button>
                    </div>
                </div>
            </div>
            <div class="card card-compact sm:w-full md:w-1/2 bg-base-100 shadow-xl mx-1">
                <figure><img src="https://placeimg.com/400/225/arch" alt="Shoes" /></figure>
                <div class="card-body">
                    <h2 class="card-title">Shoes!</h2>
                    <p>If a dog chews shoes whose shoes does he choose?</p>
                    <div class="card-actions justify-end">
                        <button class="btn btn-primary">Buy Now</button>
                    </div>
                </div>
            </div>
            <!--<div class="card w-1/2 glass mx-10">
          <figure><img src="https://placeimg.com/400/225/arch" alt="car!" /></figure>
          <div class="card-body">
            <h2 class="card-title">Life hack</h2>
            <p>How to park your car at your garage?</p>
            <div class="card-actions justify-end">
              <button class="btn btn-primary">Learn now!</button>
            </div>
          </div>
        </div>-->
        </div>

        <div class="flex">
            <div class="hero bg-base-200 pt-2">
                <div class="hero-content text-center">
                    <div class="max-w-md">
                        <h1 class="text-5xl font-bold">Hello there</h1>
                        <p class="py-6">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi
                            exercitationem
                            quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
                        <button class="btn btn-primary">Get Started</button>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>
  
<script setup>

</script>
  
<style lang="scss" scoped>

</style>