<template>
  <div class="home">
    <ul v-for="item in items" :key="item.message">
      {{
        item.message
      }}
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {},
  data: function() {
    return {
      items: [
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' },
        { message: 'Foo' },
        { message: 'Bar' }
      ]
    };
  }
};
</script>

<style>
.home {
  text-align: center;
}
</style>
