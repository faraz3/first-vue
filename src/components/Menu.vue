<template>
  <div class="data">
    <div class="umur">
      <h3 class="mt-5 fs-4 fw-bold me-5">Age</h3>
      <h3 class="fw-normal text-secondary ms-5">17</h3>
    </div>

    <div class="alamat">
      <h3 class="fs-4 fw-bold me-5">Address</h3>
      <h3 class="fw-normal text-secondary ms-2 gg">Sukamaju Baru, Tapos, Depok</h3>
    </div>

    <div class="email">
      <h3 class="fs-4 fw-bold mail">Email</h3>
      <h3 class="fw-normal text-secondary ms-5">farazyanuar1@gmail.com</h3>
    </div>

    <div class="phone">
      <h3 class="fs-4 fw-bold me-4">Phone</h3>
      <h3 class="fw-normal text-secondary ms-5">+6281213517814</h3>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Menu',
}
</script>

<style>
.umur {
  display: flex;
}
.umur h3{
  margin-top: 43px;
}

.alamat {
  display: flex;
  margin-top: -20px;
}
.alamat h3{
  margin-top: 40px;
}
.alamat .gg {
  margin-top: 35px;
}

.email {
  display: flex;
}
.email h3{
  margin-top: 19px;
}
.email .mail {
  margin-right: 35px;
}

.phone {
  display: flex;
}
.phone h3{
  margin-top: 16px;
}
</style>