<template>
<div class="sidebar-icon group">
  <i :class="faClass"></i>
  <span class="sidebar-tooltip group-hover:scale-100">{{tooltipText}}</span>
</div>
</template>

<script>
export default {
  name: "SideBarIcon",
  props: ['faClass', 'tooltipText']
}
</script>
