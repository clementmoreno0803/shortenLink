<template>
<div class="presentation">
      <div class="titre">
        <h1>More than just shorter links</h1>
        <h2>
          Build your brand's recognition and get detailed insights on how your
          links are performing.
        </h2>
        <div class="calltoaction">Get started</div>
      </div>
      <img
        src="../assets/illustration-working.svg"
        alt=""
        class="illustration"
      />
    </div>
</template>

<script>
export default {
name:"pres",
}
</script>

<style>
.calltoaction {
  width: max-content;
  padding: 10px 30px;
  background: var(--primary);
  border-radius: 25px;
  color: var(--secondaly);
  font-weight: 500;
  height: 25px;
  font-family: "Poppins";
  font-size: 1em;
}
.calltoaction:hover{
  opacity: 0.8;
  color: var(--secondary);
  transition : all 0.4s ease;
}
.presentation{
      display: flex;
    position: relative;
    margin-bottom: 200px;
    align-items: center;
}
.illustration {
  width: 50%;
  position: relative;
  left: 15%;
}
</style>
