<template>

    <div class="flex justify-center min-h-screen hero-font">
        <div class="hidden bg-cover lg:block lg:w-2/5"
        style="background-image: url('https://images.pexels.com/photos/5053847/pexels-photo-5053847.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2')">
    </div>
        <div class="flex items-center w-full max-w-3xl p-8 mx-auto lg:px-12 lg:w-3/5">
            <div class="w-full">
                <h1 class="text-2xl font-semibold tracking-wider capitalize ">
                    Reset Password
                </h1>

                <p class="mt-4 ">
                    Having issues remembering your password? You can recover it using the
                    email associated with your account.
                </p>
                <form class="p-10 md:p-12">
                    <div class="flex items-center text-lg mb-6 md:mb-8">
                        <svg class="absolute ml-3 icon" width="24" viewBox="0 0 24 24">
                            <path
                                d="M20.822 18.096c-3.439-.794-6.64-1.49-5.09-4.418 4.72-8.912 1.251-13.678-3.732-13.678-5.082 0-8.464 4.949-3.732 13.678 1.597 2.945-1.725 3.641-5.09 4.418-3.073.71-3.188 2.236-3.178 4.904l.004 1h23.99l.004-.969c.012-2.688-.092-4.222-3.176-4.935z" />
                        </svg>
                        <input type="text" id="email" class="bg-gray-200 pl-12 py-2 md:py-4 focus:outline-none w-full"
                            placeholder="name@sample.com" />
                    </div>
                    <button
                        class=" font-medium p-2 md:p-4 text-white uppercase w-full signin_btn flex items-center justify-center">Proceed
                        to
                        dasboard <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24"
                            stroke-width="1.5" stroke="currentColor" class="w-6 h-6 ml-2">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
                        </svg></button>
                    <!-- Forgot Password Link -->
                    <div class="mb-6 py-8 text-md">
                        Remember your password? <NuxtLink to="/login" class="hover:underline text-blue-500">Sign
                            In
                        </NuxtLink>
                    </div>
                </form>

            </div>
        </div>
    </div>
</template>

<style>
#icon {
    color: #B51C17 !important;
}

.signin_btn {
    background-color: #B51C17;
    color: white
}
</style>