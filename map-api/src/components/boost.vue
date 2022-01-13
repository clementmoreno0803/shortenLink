<template>
  <div class="boost_link">
    <h2 id="boost_title">Boost your links today</h2>
    <div class="calltoaction">Get started</div>
  </div>
</template>

<script>
export default {
name: "boost",
}
</script>

<style>
.boost_link{
  position: relative;
  top: 100px;
  height: 250px;
  width: 100%;
  background: url('../assets/bg-boost-desktop.svg') hsl(257, 27%, 26%) ;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
#boost_title{
  color: var(--secondary);
  font-size: 2.5rem;
  margin-bottom: 15px;
  opacity: 1;
}
</style>
