<template>
  <div class="best">
    <div class="container">
      <div class="best-wrapper">
        <div class="best-info">
          <div class="best-title">Pet Store <br />& Beyond</div>
          <div class="best-subvtitle">
            This is a sample landing page, created with Figma <br />and Anima.
            No coding involved.
          </div>
          <button class="best-btn">Get Started</button>
        </div>
        <div class="best-item">
          <div class="best-image">
            <img src="@/assets/img/animals.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Best",
};
</script>

<style lang="scss" scoped>
.best {
  padding: 50px 0px;
  background-color: #f7f5fd;
}
.best-wrapper {
  display: flex;
  justify-content: space-between;
}
.best-title {
  font-style: normal;
  font-weight: bold;
  font-size: 80px;
  margin-bottom: 20px;
  cursor: pointer;
}
.best-subvtitle {
  font-size: 20px;
  margin-bottom: 40px;
}
.best-btn {
  padding: 15px 45px;
  color: white;
  background-color: #dfbf70;
  border-radius: 15px;
  border: none;
  cursor: pointer;
  font-size: 20px;
}
.best-btn:hover {
  transition: 0.5s;
  background-color: #2a50c1;
  border-radius: 5px;
}
.best-image img {
  width: 100%;
  cursor: pointer;
}


@media screen and (max-width: 1200px) {
  .best-title {
    font-size: 70px;
  }
}


@media screen and (max-width: 992px) {
  .best-wrapper {
    display: flex;
  }
  .best-title {
    font-size: 50px;
  }
  .best-image {
    text-align: end;
  }
  .best-image img {
    width: 80%;
  }
  .best-btn {
    font-size: 15px;
  }
}


@media screen and (max-width: 768px) {
  .best-wrapper {
    flex-direction: column;
    align-items: center;
  }
  .best-image {
    text-align: center;
  }
  .best-title {
    font-size: 50px;
  }
  .best-subvtitle {
    font-size: 18px;
  }
  .best-btn {
    margin-bottom: 50px;
  }
  .best-info {
    text-align: center;
  }
}


@media screen and (max-width: 576px) {
  .best-image img {
    width: 100%;
  }
  .best-title {
    font-size: 40px;
  }
  .best-subvtitle {
    font-size: 17px;
  }
  .best-btn {
    padding: 10px 35px;
    font-size: 15px;
  }
}
</style>
