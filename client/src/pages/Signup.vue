<template>
  <q-page>
    <q-form @submit="onSubmit">
      <div>
        <q-input type="text" label="FIRST NAME" dense />
        <q-input type="text" label="LAST NAME" dense />
        <q-input type="email" label="EMAIL" dense />
        <q-input type="text" label="USERNAME" dense />
        <q-input type="password" label="PASSWORD" dense />
      </div>
      <div>
        <q-input type="text" label="ADDRESS" dense />
        <q-input type="text" label="CITY" dense />
        <q-btn-dropdown label="STATE" dense />
        <q-input type="number" label="ZIP" dense />
      </div>
      <q-btn type="submit" label="Submit" />
    </q-form>
  </q-page>
</template>

<script>
export default {
  name: 'signup',
  methods: {
    onSubmit() {
      console.log('signed up');
    },
  },
};
</script>

<style scoped>

</style>
