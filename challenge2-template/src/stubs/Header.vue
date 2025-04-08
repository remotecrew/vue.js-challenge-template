<template>
  <header class="w-full flex justify-center items-center bg-gray-800 p-4">
    <!-- Logo -->
    <h2 class="text-white text-2xl font-semibold">
      THE MOVIE DB
    </h2>
  </header>
</template>

<script>
export default {
  name: 'HeaderComponent',
  data() {
    return {
      dropdownOpen: false,
    };
  },
  methods: {
    toggleDropdown() {
      this.dropdownOpen = !this.dropdownOpen;
    }
  }
}
</script>


