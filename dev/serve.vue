<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { PrivateLibraryTestSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  PrivateLibraryTestSample,
  // }
});
</script>

<template>
  <div id="app">
    <private-library-test-sample />
  </div>
</template>
