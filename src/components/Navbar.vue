<template>
  <nav class="navbar navbar-expand-lg bg-light">
  <div class="container-fluid">
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <RouterLink to="/personal" class="nav-link fw-semibold fs-5" aria-current="page">Personal</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/skill" class="nav-link fw-semibold fs-5">Skill</RouterLink>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
    name: 'Navbar',
}
</script>

<style>

</style>