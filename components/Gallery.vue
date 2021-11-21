<template>
  <section class="grid justify-items-center p-14 text-5xl">
    <h2>Gallery</h2>
    <p class="p-14">
      Some images of cars
    </p>

    <div class="flex justify-evenly gap-x-16 gap-y-16 flex-wrap p-14">
      <nuxt-img
        src="images/image1.jpg"
        sizes="sm:300px md:400px lg:500px"
      />
      <nuxt-img
        src="images/image2.jpg"
        sizes="sm:300px md:400px lg:500px"
      />
      <nuxt-img
        src="images/image3.jpg"
        sizes="sm:300px md:400px lg:500px"
      />
    </div>
  </section>
</template>