<template>
  <div class="dylan">
    <div class="container">
      <div class="dylan-wrapper">
        <div class="dylan-info">
          <div class="dylan-image">
            <img src="@/assets/img/Dylan.png" alt="" />
          </div>
        </div>
        <div class="dylan-wrapper__item">
          <div class="dylan-wrapper__image">
            <img src="@/assets/img/Art.svg" alt="" />
          </div>
          <div class="dylan-wrapper__title">
            We love using 'PETWORLD' products. Environmentally friendly and
            sustainable. We have the sustainable dog bowls and regularly use the
            mint scented poo bags which were all such great value for money.
          </div>
          <div class="dylan-wrapper__subscribe">Dylan Shaw</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Dylan",
};
</script>

<style lang="scss" scoped>
.dylan {
  padding: 50px 0px;
  background-color: #ece7fb;
}
.dylan-wrapper {
  display: flex;
  gap: 50px;
  align-items: center;
}
.dylan-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.dylan-wrapper__image {
  padding-bottom: 20px;
}
.dylan-wrapper__title {
  font-size: 18px;
  font-weight: bold;
  padding-bottom: 50px;
}


@media screen and (max-width: 768px) {
  .dylan-wrapper {
    display: flex;
    flex-direction: column;
  }
}


@media screen and (max-width: 576px) {
  .dylan-image img {
    width: 100%;
  }
}
</style>
