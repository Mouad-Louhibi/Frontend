<template>
  <div class="row no-gutters">
    <div class="col-md-6 no-gutters">
      <div class="leftside d-flex justify-content-center align-items-center"></div>
    </div>
    <div class="col-md-6 no-gutters">
      <div class="rightside d-flex justify-content-center align-items-center"></div>
    </div>
  </div>
</template>
<script>
export default {
  components: {},
};
</script>

<style>
.leftside,
.rightside {
  height: 50vh;
  width: 100%;
}

@media screen and (min-width: 768px) {
  .leftside, .rightside{
    height: 100vh;
  }
}

.leftside {
  background: red;
}

.rightside {
  background: blue;
}
</style>
