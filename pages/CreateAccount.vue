<template>
  <section class="bg-white text-black auth-section hero-font">
    <div class="flex justify-center min-h-screen">
      <div
        class="hidden bg-cover lg:block lg:w-2/5"
        style="
          background-image: url('https://images.pexels.com/photos/5053847/pexels-photo-5053847.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2');
        "
      ></div>
      <div
        class="flex items-center w-full max-w-3xl p-8 mx-auto lg:px-12 lg:w-3/5"
      >
        <div class="w-full">
          <h1 class="text-2xl font-semibold tracking-wider capitalize">
            Create an account
          </h1>

          <p class="mt-4">
            Let’s get you all set up so you can verify your personal account and
            begin setting up your profile.
          </p>

          <form class="grid grid-cols-1 gap-6 mt-8 md:grid-cols-2">
            <div>
              <label class="block mb-2 text-sm">First Name</label>
              <input
                type="text"
                placeholder="John"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gray-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Last name</label>
              <input
                type="text"
                placeholder="Snow"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gre-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Gender</label>
              <input
                type="text"
                placeholder="John"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gray-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Date of birth</label>
              <input
                type="date"
                placeholder="Snow"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gre-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Phone number</label>
              <input
                type="text"
                placeholder="XXX-XX-XXXX-XXX"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gre-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Email address</label>
              <input
                type="email"
                placeholder="johnsnow@example.com"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gre-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Password</label>
              <input
                type="password"
                placeholder="Enter your password"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gre-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>

            <div>
              <label class="block mb-2 text-sm">Confirm password</label>
              <input
                type="password"
                placeholder="Enter your password"
                class="block w-full px-5 py-3 mt-2 text-gray-700 placeholder-gray-200 bg-gray-100 border border-gray-100 rounded-md border-gray-300 focus:border-gre-200 focus:ring-gray-200 focus:outline-none focus:ring focus:ring-opacity-40"
              />
            </div>
          </form>
          <form class="py-6">
            <button
              class="font-medium p-2 md:p-4 text-white uppercase w-full signin_btn flex items-center justify-center"
            >
              Submit
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6 ml-2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
                />
              </svg>
            </button>
            <div class="mb-6 py-8 text-md">
              Already have an Account with TechEd?
              <NuxtLink to="/login" class="hover:underline text-blue-500"
                >Sign In
              </NuxtLink>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.auth-secction {
  color: black;
}

.create_account {
  background-color: #b51c17;
  color: white;
}
</style>
