<template>
<div class="sidebar-icon">
  <i :class="faClass"></i>
</div>
</template>

<script>
export default {
  name: "SideBarIcon",
  props: ['faClass']
}
</script>
