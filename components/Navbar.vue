<template>
  <nav>
    <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
      <div class="relative flex items-center justify-between h-16">
        <div class="flex-1 flex items-center justify-center">
          <div class="flex-shrink-0 flex items-center mr-auto">
            <h1 class="text-custom-blue font-bold text-2xl font-custom-bold">
              Landkit.
            </h1>
          </div>
          <div class="mx-auto">
            <div class="flex space-x-4 navbar">
              <a
                href="#"
                class="text-custom-gray block px-3 py-2 rounded-md text-base font-normal"
                >Products</a
              >
              <a
                href="#"
                class="text-custom-gray block px-3 py-2 rounded-md text-base font-normal"
                >Developers</a
              >
              <a
                href="#"
                class="text-custom-gray block px-3 py-2 rounded-md text-base font-normal"
                >Company</a
              >
              <a
                href="#"
                class="text-custom-gray block px-3 py-2 rounded-md text-base font-normal"
                >Pricing</a
              >
            </div>
          </div>
        </div>
        <div
          class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0"
        >
          <a
            href="#"
            class="text-custom-gray block px-3 py-2 rounded-md text-base font-normal"
            >Login</a
          >
          <button class="bg-custom-blue text-white py-1 px-3 rounded ml-3">
            Sign In
          </button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>