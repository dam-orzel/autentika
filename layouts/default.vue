<template>
  <div>
    <Nuxt />
    <Loader />
    <Notification />
  </div>
</template>

<script>
import Loader from "@/components/Loader";
import Notification from "@/components/Notification";
export default {
  components: {
    Loader,
    Notification
  }
};
</script>
