<template>
    <div class="bg-gray-800 text-center text-white">
        <div class="text-5xl font-bold pt-10 pb-10">Contact Me</div>
    </div>
  <div class="contact-page bg-gray-800 text-white pb-10">
    <div class="container mx-auto">
      <form @submit.prevent="submitForm" class="max-w-md mx-auto">
        <div class="mb-4">
          <label for="name" class="block text-sm font-medium">Your Name</label>
          <input v-model="formData.name" type="text" id="name" name="name" placeholder="Enter your name" class="mt-1 px-4 py-2 w-full border rounded-md bg-gray-800 text-white">
        </div>
        <div class="mb-4">
          <label for="email" class="block text-sm font-medium">Email</label>
          <input v-model="formData.email" type="email" id="email" name="email" placeholder="Enter your email" class="mt-1 px-4 py-2 w-full border rounded-md bg-gray-800 text-white">
        </div>
        <div class="mb-4">
          <label for="message" class="block text-sm font-medium">Message</label>
          <textarea v-model="formData.message" id="message" name="message" rows="4" placeholder="Enter your message" class="mt-1 px-4 py-2 w-full border rounded-md bg-gray-800 text-white"></textarea>
        </div>
        <div class="text-center">
          <button type="submit" class="px-6 py-3 bg-gray-600 text-white rounded-md hover:bg-verdun-green-300 transition duration-300">Send Message</button>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      formData: {
        name: '',
        email: '',
        message: ''
      }
    };
  },
  methods: {
    submitForm() {
      // You can handle form submission here, e.g., send data to backend or perform validation
      console.log('Form submitted:', this.formData);
      // Reset form data after submission
      this.formData = {
        name: '',
        email: '',
        message: ''
      };
    }
  }
};


useHead({
  title: 'Contact',
  meta: [
    { name: 'description', content: 'Esterline Audio Contact Page.' }
  ],
  script: [ { innerHTML: 'console.log(\'Welcome to the Contact Page\')' } ]
})

</script>

<style scoped>
/* Add your custom styles here if needed */
</style>