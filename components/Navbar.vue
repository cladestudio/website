<template>
  <div class="navbar">
    <div class="navbar__brand">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
      >
        <circle cx="12" cy="12" r="12" fill="#2F5FE9" />
      </svg>
      <h1>clade.studio</h1>
    </div>
    <a class="navbar__link" href="mailto:hello@clade.studio" target="_blank">
      Contact
    </a>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped lang="scss">
.navbar {
  margin-top: 62px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  &__brand {
    display: flex;
    align-items: center;
    gap: 6px;
    h1 {
      font-weight: 600;
      font-size: 28px;
    }
  }
  &__link {
    font-size: 18px;
    font-weight: 300;
    color: #fff;
    text-decoration: none;
  }
}
</style>
