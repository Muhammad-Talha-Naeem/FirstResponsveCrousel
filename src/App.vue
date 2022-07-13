<template>
<div class="bg-gray-100">
  <CrauselCom/>
</div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import CrauselCom from "@/components/CrauselCom.vue";
export default defineComponent({
  name: "App",
  components: { CrauselCom },
});
</script>

    