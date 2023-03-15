<template>
  <div class="hero">
    <h1 class="hero__headline">
      <img class="hero__headline-icon" src="../../assets/icons/icon1.png" />
      We are <span style="font-family: 'Italiana'">design studio</span> building
      digital experiences that are intuitive and easy to use for people of all
      skill levels.
    </h1>
    <p class="hero__description">
      Your brand's digital journey starts here. We'll help you create a tech
      stack that delivers a seamless and delightful online experience for your
      customers.
    </p>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped lang="scss">
.hero {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  margin-bottom: 60px;
  max-width: 842px;
  &__headline {
    line-height: 38px;
    font-size: 32px;
    font-weight: 300;
    margin-top: 120px;
    &-icon {
      transform: translateY(4px);
      height: 32px;
      aspect-ratio: 1;
    }
  }
  &__description {
    font-weight: 300;
    font-size: 24px;
    line-height: 28px;
    max-width: 720px;
  }
}
</style>
