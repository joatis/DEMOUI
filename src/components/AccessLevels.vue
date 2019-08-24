<template>
  <div>
    <h1>Access Levels</h1>
    <md-layout>
      <md-layout-item>
        <!-- <SpotLightSearch/>
        <AccessTable/> -->
        Left Pane
      </md-layout-item>
      <md-layout-item>Right Pane</md-layout-item>
    </md-layout>
  </div>
</template>

<script>
import accessLevels from '../assets/accessLevels.json';
import readers from '../assets/readers.json';
import readerTypes from '../assets/readerTypes.json';
import SpotLightSearch from '../components/SpotLightSearch';
import AccessTable from '../components/AccessTable';

export default {
  name: 'AccessLevels',
  components: {
    SpotLightSearch,
    AccessTable,
  },
  data() {
    return {
      accessLevels,
      readers,
      readerTypes,
    };
  },

};
</script>
