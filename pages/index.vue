<template>
  <UserLayout>
    이렇게 레이아웃이 적용이 되는건가요?
  </UserLayout>
</template>
<script>
import UserLayout from "../layouts/UserLayout";
import defineNuxtRouteMiddleware from "../middleware/auth"
export default {
  components: {UserLayout}
}

</script>