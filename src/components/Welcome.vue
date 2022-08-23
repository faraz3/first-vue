<template>
  <nav class="navbar bg-light mb-4">
    <div class="container-fluid">
      <RouterLink to="/personal" class="navbar-brand p-2" aria-current="page">
        <img src="@/assets/person.svg" alt="" width="30" height="24" class="d-inline-block align-text-top">
        Personal
      </RouterLink>
    </div>
  </nav>

  <nav class="navbar bg-light">
    <div class="container-fluid">
      <RouterLink to="/skill" class="navbar-brand p-2" aria-current="page">
        <img src="@/assets/mortarboard.svg" alt="" width="30" height="24" class="d-inline-block align-text-top me-3">
        Skill
      </RouterLink>
    </div>
  </nav>
</template>

<script>
  export default {
    name: 'Welcome'
  }
</script>

<style>

</style>