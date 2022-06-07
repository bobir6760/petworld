<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar-wrapper">
        <div class="navbar-info">
          <div class="navbar-wrapper__image">
            <img src="@/assets/img/12kg.svg" alt="" />
          </div>
          <div class="navbar-title">RETWORLD</div>
        </div>
        <div class="navbar-item">
          <div class="navbar-item__title">Sign-up</div>
          <button class="navbar-btn">Log in</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  padding: 50px 0px;
}
.navbar-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.navbar-info {
  display: flex;
  gap: 10px;
}
.navbar-title {
  font-weight: bold;
}
.navbar-item {
  display: flex;
  gap: 30px;
  align-items: center;
}
.navbar-btn {
  padding: 15px 45px;
  font-size: 20px;
  color: white;
  background-color: #2a50c1;
  border-radius: 10px;
  border: none;
  cursor: pointer;
}
.navbar-btn:active {
  color: black;
}
.navbar-item__title {
  font-size: 18px;
  font-weight: bold;
}
.navbar-wrapper__image img {
  width: 100%;
}


@media screen and (max-width: 992px) {
  .navbar-btn {
    font-size: 15px;
  }
}


@media screen and (max-width: 576px) {
  .navbar-wrapper {
    flex-direction: column;
    margin: 0px;
  }
  .navbar-info {
    padding-bottom: 30px;
  }
  .navbar-btn {
    padding: 10px 35px;
    font-size: 15px;
  }
}
</style>
