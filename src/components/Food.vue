<template>
  <div class="food">
    <div class="container">
      <div class="food-wrapper">
        <div class="food-info">
          <div class="food-wrapper__block">
            <div class="food-image">
              <img src="@/assets/img/kost.svg" alt="" />
            </div>
            <div class="food-wrapper__title">Best quality pet food</div>
            <div class="food-wrapper__subscribe">
              Super delicious food. Available in a range of delicious flavors.
            </div>
          </div>

          <div class="food-wrapper__block">
            <div class="food-image">
              <img src="@/assets/img/shar.svg" alt="" />
            </div>
            <div class="food-wrapper__title">Best quality pet food</div>
            <div class="food-wrapper__subscribe">
              Super delicious food. Available in a range of delicious flavors.
            </div>
          </div>

          <div class="food-wrapper__block">
            <div class="food-image">
              <img src="@/assets/img/Medical.svg" alt="" />
            </div>
            <div class="food-wrapper__title">Best quality pet food</div>
            <div class="food-wrapper__subscribe">
              Super delicious food. Available in a range of delicious flavors.
            </div>
          </div>

          <div class="food-wrapper__block">
            <div class="food-image">
              <img src="@/assets/img/qaychi.svg" alt="" />
            </div>
            <div class="food-wrapper__title">Best quality pet food</div>
            <div class="food-wrapper__subscribe">
              Super delicious food. Available in a range of delicious flavors.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Food",
};
</script>

<style lang="scss" scoped>
.food {
  padding: 50px 0px;
}
.food-info {
  display: flex;
  align-items: center;
  text-align: center;
  gap: 30px;
}
.food-image img {
  width: 100px;
  height: 100px;
  object-fit: contain;
}
.food-wrapper__title {
  font-size: 20px;
  font-weight: bold;
  margin-bottom: 20px;
}
.food-wrapper__subscribe {
  display: flex;
}


@media screen and (max-width: 992px) {
  .food-info {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
}


@media screen and (max-width: 576px) {
  .food-info {
    display: flex;
    flex-direction: column;
  }
}
</style>
