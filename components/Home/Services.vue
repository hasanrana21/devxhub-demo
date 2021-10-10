<template>
  <section class="md:px-24 md:pt-24 md:pb-8">
    <h1 class="text-center text-5xl font-bold">
      Our <span :style="{ color: '#37b1d1' }">Services</span>
    </h1>

    <div class="grid grid-cols-12 gap-4 place-items-center md:py-10">
      <div class="service-card col-span-4 border-2 border-gray-200 px-6 py-14">
        <div>
          <img
            src="https://devxhub.com/storage/uploads/services/1617459000-96x96-web-design-logo.png"
            class="mx-auto"
            alt="devXhub"
          />
        </div>
        <h3 class="text-3xl font-bold text-center py-4">Web Design</h3>
        <p class="text-xl font-semibold">
          At present, Mobile Apps are the major part of a good website. So we
          made it very carefully, beautiful and user friendly.
        </p>
      </div>
      <div class="service-card col-span-4 border-2 border-gray-200 px-6 py-14">
        <div>
          <img
            src="https://devxhub.com/storage/uploads/services/1616071487-96x96-coding.png"
            class="mx-auto"
            alt="devXhub"
          />
        </div>
        <h3 class="text-3xl font-bold text-center py-4">Web Development</h3>
        <p class="text-xl font-semibold">
          DevXHub is always used modern and new technology for web development.
          We are able to fulfill your all requirements.
        </p>
      </div>
      <div class="service-card col-span-4 border-2 border-gray-200 px-6 py-14">
        <div>
          <img
            src="https://devxhub.com/storage/uploads/services/1616071360-96x96-application.png"
            class="mx-auto"
            alt="devXhub"
          />
        </div>
        <h3 class="text-3xl font-bold text-center py-4">
          Mobile App Devlopment
        </h3>
        <p class="text-xl font-semibold">
          At present, Mobile Apps are the major part of a good website. So we
          made it very carefully, beautiful and user friendly.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.service-card:hover {
  background: url(https://engitech.s3.amazonaws.com/images/bg-icon-box1.jpg)
    center center;
  @apply text-white bg-gray-300 bg-opacity-75;
}
</style>
