<template>
  <section class="md:px-24 md:py-10">
    <h1 class="text-center text-white text-5xl font-bold py-4">
      <span :style="{ color: '#37b1d1' }">Technology</span> We Used
    </h1>

    <div class="grid grid-cols-12 place-items-center">
      <div class="technology-card col-span-3 w-64 px-6 py-6 my-6">
        <img
          src="https://devxhub.com/storage/uploads/SkillOrTechnology/1616083284-90x90-robot-removebg-preview.png"
          class="mx-auto"
          alt="devXhub"
        />
        <h5 class="text-2xl font-bold text-center py-4">ROBOTIC</h5>
      </div>
      <div class="technology-card col-span-3 w-64 px-6 py-6 my-6">
        <img
          src="https://devxhub.com/storage/uploads/SkillOrTechnology/1616067836-90x90-b_1_-removebg-previewfff.png"
          class="mx-auto"
          alt="devXhub"
        />
        <h5 class="text-2xl font-bold text-center py-4">DATA SCIENCE</h5>
      </div>
      <div class="technology-card col-span-3 w-64 px-6 py-6 my-6">
        <img
          src="https://devxhub.com/storage/uploads/SkillOrTechnology/1616067836-90x90-b_1_-removebg-previewfff.png"
          class="mx-auto"
          alt="devXhub"
        />
        <h5 class="text-2xl font-bold text-center py-4">CYBER SECURITY</h5>
      </div>
      <div class="technology-card col-span-3 w-64 px-6 py-6 my-6">
        <img
          src="https://devxhub.com/storage/uploads/SkillOrTechnology/1616067836-90x90-b_1_-removebg-previewfff.png"
          class="mx-auto"
          alt="devXhub"
        />
        <h5 class="text-2xl font-bold text-center py-4">CYBER SECURITY</h5>
      </div>
      <div class="technology-card col-span-3 w-64 px-6 py-6 my-6">
        <img
          src="https://devxhub.com/storage/uploads/SkillOrTechnology/1616068369-90x90-b11111-removebg-preview.png"
          class="mx-auto"
          alt="devXhub"
        />
        <h5 class="text-2xl font-bold text-center py-4">BLOCKCHAIN</h5>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
section {
  background-image: url(https://engitech.s3.amazonaws.com/images/bg-icon-box5.jpg);
  background-size: cover;
}
.technology-card {
  @apply h-auto text-white border-2 border-gray-500;
}
.technology-card:hover {
  @apply bg-indigo-900 border-blue-400 text-white transition-all duration-500 ease-in-out;
}
</style>
