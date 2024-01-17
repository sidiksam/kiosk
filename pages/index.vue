<template>
  <div class="mx-auto px-10 py-6">
    <!-- Navigation -->
    <nav>
      <div>
        <div class="flex justify-between">
          <div>button</div>
          <div>logo</div>
          <div>cart</div>
        </div>
      </div>
    </nav>

    <!-- Cards -->
    <div class="px-10 pt-12">
      <div class="flex space-x-12">
        <div class="space-y-12 w-80">
          <div class="bg-card shadow-sm">
            <div>
              <div class="flex justify-between px-5 py-3">
                <p class="button-color rounded-md text-xs">
                  <UButton color class="text-white">New</UButton>
                </p>
                <p class="text-gray-500 font-semibold">Le50.00</p>
              </div>
              <div>
                <img
                  class="w-full object-cover h-44"
                  src="https://template.hasthemes.com/hurst-v1/hurst/img/banner/1.jpg"
                  alt="Funiture"
                />
              </div>
              <div class="flex justify-between px-5 py-3 items-center">
                <p class="text-gray-600 font-semibold text-lg">
                  product name <br />
                  <span class="text-sm text-500 font-normal ">funiture</span>
                </p>
                <p class="text-xs px-1">
                  <UButton
                    color
                    size="sm"
                    class="text-gray-600 border px-3  border-gray-500"
                    >Buy now</UButton
                  >
                </p>
              </div>
            </div>
          </div>
          <div class="bg-card">
            <div class="flex justify-between px-5 py-3">
              <div class="">
                <img
                  class="h-full object-fill w-auto"
                  src="https://template.hasthemes.com/hurst-v1/hurst/img/banner/2.jpg"
                  alt="Table"
                />
              </div>
              <div class="">
                <p class="text-gray-600 font-semibold text-lg">
                  New product 2024
                </p>
                <p class="w-28 text-xs">
                  Lorem Ipsum is simply dummy text of the printing and types
                  sate industry. Lorem Ipsum has been the industry.
                </p>
                <p class="text-xs px-1 pt-5">
                  <UButton
                    color
                    size="sm"
                    class="text-gray-600 border px-4 border-gray-500"
                    >Buy now</UButton
                  >
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-card w-full">car</div>
      </div>

  
    </div>
  </div>
</template>
<style scoped>
.bg-card {
  background-color: #efefef;
}
.button-color {
  background-color: #c8a165;
}
</style>
