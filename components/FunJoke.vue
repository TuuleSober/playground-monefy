<!-- Please remove this file from your project -->
<template>
  <div
    class="relative flex items-top justify-center flex-col min-h-screen bg-gray-100 sm:items-center sm:pt-0"
  >
    <a class="mb-4">When do you want to hear racecar noises?</a>
    <button v-on:click="say">
    Click to reveal {{aa}}
  </button>
  </div>
</template>

<script>
export default {
  name: 'SoberIndustries',
  methods: {
    say: () => {
      alert('neooowwww')
    }
  },
  data: () => ({
    aa: "joke",
  })
}
</script>
