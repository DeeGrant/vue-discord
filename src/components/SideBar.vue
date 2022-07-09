<template>
<section class="fixed top-0 left-0 h-screen w-16 flex flex-col bg-gray-900 text-white shadow-lg">
  <side-bar-icon :fa-class="'fa fa-fire-flame-curved'"></side-bar-icon>
  <side-bar-icon :fa-class="'fa fa-plus'"></side-bar-icon>
  <side-bar-icon :fa-class="'fa fa-bolt-lightning'"></side-bar-icon>
  <side-bar-icon :fa-class="'fa fa-poo'"></side-bar-icon>
</section>
</template>

<script>
import SideBarIcon from "@/components/SideBarIcon";

export default {
  name: "SideBar",
  components: {
    SideBarIcon
  }
}
</script>
