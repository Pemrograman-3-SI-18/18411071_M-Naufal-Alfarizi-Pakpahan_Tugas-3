<template>
  <q-layout view="hHh Lpr fFf"> <!-- Be sure to play with the Layout demo on docs -->
    <q-page-container>
      <router-view>
      </router-view>
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: 'LoginRegisLayout',

  data () {
    return {
      leftDrawer: true
    }
  }
}
</script>
