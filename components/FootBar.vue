<template>
  <!--footer-->
  <div class="black py-8">
    <div class="container mx-auto flex justify-center items-center">
        <div class="text-md font-bold">© {{ year }} MSCPO-服务器集体宣传组织</div>
    </div>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const year = ref(new Date().getFullYear())

</script>
