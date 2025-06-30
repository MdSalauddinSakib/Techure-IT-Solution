<script setup>

</script>

<template class="">
  <!-- Navbar Section -->
  <section class="bg-[#f6f1fa] fixed top-0 left-0 right-0 z-50">
    <nav class="container mx-auto max-w-7xl">
      <div class="flex justify-between items-center px-8 py-4">
        <div class="flex items-center gap-4">
          <img src="../assets/img/logo-techure.png" alt="Logo" class="w-12 h-12">
          <h1 class="text-3xl font-bold">Techure</h1>
        </div>
        <ul class="flex space-x-6 text-lg">
          <li><a href="#" class="text-[#031F42] font-bold  hover:text-blue-500">Home <i
                class="fa-solid fa-chevron-down"></i></a></li>
          <li><a href="#" class="text-[#031F42] font-bold  hover:text-blue-500">About Us</a></li>
          <li><a href="#" class="text-[#031F42] font-bold  hover:text-blue-500">Services <i
                class="fa-solid fa-chevron-down"></i></a></li>
          <li><a href="#" class="text-[#031F42] font-bold  hover:text-blue-500">Projects <i
                class="fa-solid fa-chevron-down"></i></a></li>
          <li><a href="#" class="text-[#031F42] font-bold  hover:text-blue-500">Blog <i
                class="fa-solid fa-chevron-down"></i></a></li>
          <li><a href="#" class="text-[#031F42] font-bold  hover:text-blue-500">Contact</a></li>
        </ul>
        <div class="flex items-center gap-2.5">
          <img src="../assets/img/call.svg" alt="">
          <span class="font-bold">(629) 555-0129</span>
          <button class="cursor-pointer ml-10"><img src="../assets/img/menu-icon.svg" alt=""></button>
        </div>
      </div>
    </nav>
  </section>
  <!-- Hero Section -->
  <section class="justify-center relative top-16">
    <!-- Background effect -->
    <div class="absolute  inset-0 flex justify-around">
      <div class="relative w-[412px] h-[412px] rounded-full bg-[#8FD45F] opacity-20 blur-[90px]"></div>
      <div class="relative w-[412px] h-[412px] rounded-full bg-[#573DB8] opacity-20 blur-[90px] top-[190px]"></div>
    </div>

    <!-- Content -->
    <div class="container mx-auto font-DM-Sans">
      <!-- header text -->
      <h1 class="text-xl text-center text-[90px] font-light"><span class="font-bold">Elevate with IT </span>Solutions
        <br>
        Tech Excellence
      </h1>
    </div>
    <!-- Image section -->
    <div class="flex justify-around">
      <!-- side bar -->
      <div class="flex flex-col gap-18 -mt-22">
        <a href="#"><i class="fa-brands fa-pinterest-p"></i></a>
        <a href="#"><i class="fa-brands fa-linkedin"></i></a>
        <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
        <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
      </div>
      <!-- main content -->
      <div class="flex items-center justify-between w-[1280px]">
        <div class="w-1/3">
          <div>
            <img class="absolute" src="../assets/img/image_1.png" alt="">
            <img class="relative top-7 left-18" src="../assets/img/video_icon.png" alt="">
          </div>
          <div class="pt-18">
            <p class="text-[#716F73] text-lg font-medium pb-7">Information Technology is a rapidly <br> evolving field
              that encompasses <br> the
              study and application
            </p>
            <div class="flex items-center gap-2.5">
              <img class="" src="../assets/img/happy_clients.png" alt="">
              <p class="font-bold text-lg">Happy Clients</p>
            </div>
          </div>
        </div>

        <div class="w-1/3">
          <img class="" src="../assets/img/cover-man.png" alt="">
        </div>

        <div class="w-1/3">
          <div class="flex items-center gap-5">
            <div>
              <h2 class="font-bold text-7xl">140+</h2>
            </div>
            <div>
              <p class="text-lg font-medium text-[#716F73]">Business <br> People</p>
            </div>
          </div>
          <hr class="w-3/4 border-t-2 border-[#573DB8] my-4">
          <div class="flex items-center gap-5">
            <div>
              <h2 class="font-bold text-7xl">99%</h2>
            </div>
            <div>
              <p class="text-lg font-medium text-[#716F73]">Customer <br> Satisfaction </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End of Hero Section -->
</template>

<style scoped></style>
