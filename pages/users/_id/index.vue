<template>
  <h1>single user: {{ $route.params.id }}</h1>
</template>

<script>
export default {
  validate(data) {
    /* eslint-disable */
    return data.params.id == 1
  }
}
</script>
