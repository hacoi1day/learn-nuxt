<template>
  <h1>User ID Page: {{ $route.params.userId }}</h1>
</template>

<script>
export default {
  validate (context) {
    if (!Number(context.params.userId)) {
      return false
    }
    return true
  }
}
</script>
