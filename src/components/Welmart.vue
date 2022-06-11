<template>
  <div class="welmart">
    <div class="container">
      <div class="welmart-wrapper">
        <div class="welmart-info">
          <div class="welmart-image">
            <img src="@/assets/img/volk.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Welmart",
};
</script>

<style lang="scss" scoped>
.welmart {
  padding: 50px 0px;
  background-color: #f2faf8;
}
.welmart-image {
  width: 70%;
  cursor: pointer;
}
.welmart-info {
  display: flex;
  justify-content: center;
}
.welmart-image img {
  border-radius: 10px;
  width: 100%;
}


@media screen and (max-width: 576px) {
  .welmart-image img {
    border-radius: 10px;
    width: 100%;
  }
  .welmart-image {
    width: 100%;
  }
}
</style>
