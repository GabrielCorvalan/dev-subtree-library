<script>
import { defineComponent } from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { DevSubtreeLibrarySample } from '@/entry.esm';

export default defineComponent({
  name: 'ServeDev',
  // components: {
  //  DevSubtreeLibrarySample,
  // }
});
</script>

<template>
  <div id="app">
    <dev-subtree-library-sample />
  </div>
</template>
