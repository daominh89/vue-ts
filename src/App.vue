<template>
  <div class="container">
    <button
      class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-6 rounded-full"
    >
      Find what
    </button>
    <button class="btn btn-blue">Find yes</button>

    <div
      class="bg-red-100 border border-red-400 text-red-600 px-4 py-3 rounded relative my-5"
      role="alert"
    >
      <strong class="font-bold">ALERT! </strong>
      <span class="block sm:inline">Please update your password</span>
    </div>
  </div>
  <div class="max-w-sm mx-auto flex p-6 bg-white rounded-lg shadow-xl">
    <div class="flex-shrink-0">
      <img src="/src/assets/logo.png" alt="" class="h-12 w-12" />
    </div>
    <div class="ml-6 py-1">
      <h4 class="text-xl text-grey-200 font-bold">Vue said:</h4>
      <p class="text-base text-grey-600">You've got mail!</p>
    </div>
  </div>
  <div class="container mt-5 mx-auto px-2">
    <!-- Flex on med screens and up -->
    <div class="md:flex">
      <div
        class="flex-1 text-gray-700 text-center bg-gray-400 px-5 py-5 m-2 rounded"
      >
        <div class="lg:flex lg:items-center">
          <div class="lg:flex-shrink-0">
            <img
              class="rounded-lg lg:w-64"
              src="https://i.ibb.co/mJJNkTJ/img2.jpg"
              alt=""
            />
          </div>
          <div class="mt-4 lg:mt-0 lg:ml-6">
            <div
              class="uppercase tracking-wide text-sm text-indigo-600 font-bold"
            >
              Networking
            </div>
            <a
              href="#"
              class="block mt-1 text-lg leading-tight font-semibold text-gray-900 hover:underline"
              >Finding connections to help your business grow</a
            >
          </div>
        </div>
      </div>
      <div
        class="flex-1 text-gray-700 text-center bg-gray-400 px-5 py-5 m-2 rounded"
      >
        <div class="lg:flex lg:items-center">
          <div class="lg:flex-shrink-0">
            <img
              class="rounded-lg lg:w-64"
              src="https://i.ibb.co/w4wGYvQ/img1.jpg"
              alt=""
            />
          </div>
          <div class="mt-4 lg:mt-0 lg:ml-6">
            <div
              class="uppercase tracking-wide text-sm text-indigo-600 font-bold"
            >
              Marketing
            </div>
            <a
              href="#"
              class="block mt-1 text-lg leading-tight font-semibold text-gray-900 hover:underline"
              >Finding customers for your new business</a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
