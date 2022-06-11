<template>
  <div class="beco">
    <div class="container">
      <div class="beco-wrapper">
        <div class="beco-info">
          <div class="beco-image">
            <div class="beco-wrapper__image">
              <img src="@/assets/img/Nestle.svg" alt="" />
            </div>
            <div class="beco-wrapper__image">
              <img src="@/assets/img/Apple.svg" alt="" />
            </div>
            <div class="beco-wrapper__image">
              <img src="@/assets/img/Beco.svg" alt="" />
            </div>
            <div class="beco-wrapper__image">
              <img src="@/assets/img/Amazon.svg" alt="" />
            </div>
            <div class="beco-wrapper__image">
              <img src="@/assets/img/Google.svg" alt="" />
            </div>
            <div class="beco-wrapper__image">
              <img src="@/assets/img/Walmart.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Beco",
};
</script>

<style lang="scss" scoped>
.beco {
  padding: 50px 0px;
}
.beco-image {
  display: flex;
  justify-content: space-around;
}
.beco-image img {
  width: 100px;
  height: 100px;
  object-fit: contain;
  cursor: pointer;
}


@media screen and (max-width: 992px) {
  .beco-image {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  .beco-wrapper__image {
    display: flex;
    justify-content: center;
  }
  .beco-image img {
    width: 100px;
  }
}


@media screen and (max-width: 768px) {
  .beco-image {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  .beco-image img {
    width: 100px;
  }
}
@media screen and (max-width: 576px) {
  .beco-image {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  .beco-image img {
    width: 100px;
  }
}
</style>
