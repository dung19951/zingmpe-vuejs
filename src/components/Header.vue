<template>
  <div class="bg-red-500 min-h-screen bg-[#170f23]">
    <div class="max-w-screen-xl m-auto">
      <div class="w-full pt-4 flex justify-between px-8">
        <input @keyup.enter="search_key" v-model="search" class="pl-20 w-[230px] h-12 rounded-full" type="text" name="" id="">
        <a class="py-4 px-7 bg-green-400 rounded-full" href=""></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      search: ''
    }
  },
  methods: {
    search_key: function () {
      console.log(this.search)
    }
  }
}
</script>

<style scoped>

</style>