<template>
  <div class="foo">
    This is a <strong>Foo</strong> page! <br>
    <button type="button" @click="goToBar">Go To Bar</button>
  </div>
</template>

<script>
export default {
  name: 'foo',
  layout: 'foolayout',
  components: {

  },
  methods: {
      goToBar(){
          this.$router.push('/bar')
      }
  }
}
</script>
