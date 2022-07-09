<template>
<section class="fixed top-0 left-0 h-screen w-16 flex flex-col bg-gray-900 text-white shadow-lg">
  <side-bar-icon :fa-class="'fa fa-fire-flame-curved'" :tooltip-text="'Hot!'"></side-bar-icon>
  <side-bar-icon :fa-class="'fa fa-plus'" :tooltip-text="'Add'"></side-bar-icon>
  <side-bar-icon :fa-class="'fa fa-bolt-lightning'" :tooltip-text="'Ouch'"></side-bar-icon>
  <side-bar-icon :fa-class="'fa fa-poo'" :tooltip-text="'Eeww :/'"></side-bar-icon>
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
