<template>

    <div class="flex justify-center min-h-screen hero-font">
        <div class="hidden bg-cover lg:block lg:w-2/5"
            style="background-image: url('https://images.pexels.com/photos/5053847/pexels-photo-5053847.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2')">
        </div>
        <div class="flex items-center w-full max-w-3xl p-6 mx-auto lg:px-12 lg:w-3/5">
            <div class="w-full">
                <div class="mb-6 py-4 text-md flex justify-end  text-md font-extra-bold">
                    Not on TechEd portal yet? <NuxtLink to="/createaccount" class="hover:underline text-blue-500"> Register Now!
                    </NuxtLink>
                </div>
                <h1 class="text-2xl font-semibold tracking-wider capitalize ">
                    Sign In
                </h1>
                <p class="pt-3 ">
                    Enter your email address and password to securely log in to
                    TechEd Student Portal
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
                    <div class="flex items-center text-lg mb-6 md:mb-8">
                        <svg class="absolute ml-3" viewBox="0 0 24 24" width="24" id="icon">
                            <path
                                d="m18.75 9h-.75v-3c0-3.309-2.691-6-6-6s-6 2.691-6 6v3h-.75c-1.24 0-2.25 1.009-2.25 2.25v10.5c0 1.241 1.01 2.25 2.25 2.25h13.5c1.24 0 2.25-1.009 2.25-2.25v-10.5c0-1.241-1.01-2.25-2.25-2.25zm-10.75-3c0-2.206 1.794-4 4-4s4 1.794 4 4v3h-8zm5 10.722v2.278c0 .552-.447 1-1 1s-1-.448-1-1v-2.278c-.595-.347-1-.985-1-1.722 0-1.103.897-2 2-2s2 .897 2 2c0 .737-.405 1.375-1 1.722z" />
                        </svg>
                        <input type="password" id="password"
                            class="bg-gray-200 pl-12 py-2 md:py-4 focus:outline-none w-full" placeholder="Password" />
                    </div>
                    <!-- Remember Me Checkbox -->
                    <div class="mb-4 flex items-center">
                        <input type="checkbox" id="remember" name="remember" class="text-blue-500">
                        <label for="remember" class="text-gray-600 ml-2">Remember Me</label>
                    </div>
                    <button class=" font-medium p-2 md:p-4 text-white uppercase w-full signin_btn">Login</button>

                    <!-- Forgot Password Link -->
                    <div class="mb-6 py-8 text-md">
                        Forgot your password? <NuxtLink to="/resetpassword" class="hover:underline text-blue-500">Reset
                            Now!
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