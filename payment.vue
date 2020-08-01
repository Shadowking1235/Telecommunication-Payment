<template>
<md-field>
      <label>Number</label>
      <md-input v-model="number" type="number"></md-input>
    </md-field>
    
</template>
<script>
  export default {
    name: 'TextFields',
    data: () => ({
      initial: 'Initial Value',
      number: null,
    })
  }
</script>