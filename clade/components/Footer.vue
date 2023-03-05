<template>
  <div class="footer">
    <img src=".././assets/icons/icon2.png" alt="" />
    <a href="mailto:hello@clade.studio" target="_blank">
      Work with us — hello@clade.studio
    </a>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
.footer {
  margin-top: auto;
  margin-bottom: 44px;
  display: flex;
  gap: 6px;
  img {
    width: 32px;
    height: 32px;
  }
  a {
    max-width: 220px;
    font-weight: 500;
    font-size: 24px;
    line-height: 28px;
    color: #fff;
    text-decoration: none;
  }
}
</style>
