<template>
  <div class="FS">
    <div class="size">
      <Fieldset legend="About">
        <div class="text">
          <h1>953331</h1>
          <h1>Component-Based Software Develoment</h1>
          <p>622115507 Jiang Tao</p>
          <p>622115504 HAIZHAO LI</p>
          <p>632115505 ZHANG JUN</p>
          <p>|||</p>
        </div>
      </Fieldset>
    </div>
  </div>
</template>

<script>
export default {
  props: ['patients']
}
</script>

<style>
.FS {
  text-align: left;
  margin-top: 5%;
}

.photo {
  width: 250px;
  padding-left: 25%;
}

.size {
  padding-left: 10%;
  padding-right: 10%;
}

.text {
  text-align: center;
}
</style>