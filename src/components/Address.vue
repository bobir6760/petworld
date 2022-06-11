<template>
  <div class="address">
    <div class="container">
      <div class="address-wrapper">
        <div class="address-body">
          <div class="address-wrapper__block">
            <div class="address-info">
              <div class="address-image">
                <img src="@/assets/img/12kg.svg" alt="" />
              </div>
              <div class="address-info__title">PETWORLD</div>
            </div>
            <div class="address-inbox">
              <div class="address-inbox__title">
                Updates right to your Inbox
              </div>
              <div class="address-inbox__item">
                <input
                  placeholder="Email address"
                  type="text"
                  name=""
                  value=""
                />
                <button class="address-btn">Send</button>
              </div>
            </div>
          </div>

          <div class="address-body">
            <div class="address-block__text">
              <div class="address-block">
                <div class="address-block__title">Our story</div>
                <div class="address-block-subtitle">FAQ</div>
                <div class="address-block-subtitle">Contact</div>
              </div>
              <div class="address-block">
                <div class="address-block__title">Pet care</div>
                <div class="address-block-subtitle">Treatments</div>
                <div class="address-block-subtitle">Health</div>
                <div class="address-block-subtitle">hygiene</div>
              </div>
              <div class="address-block">
                <div class="address-block__title">Shop</div>
                <div class="address-block-subtitle">Pet Food</div>
                <div class="address-block-subtitle">Toys</div>
                <div class="address-block-subtitle">Accessories</div>
              </div>
            </div>
          </div>
        </div>
        <div class="address__block">
          <div class="addres-item">
            <div class="address-wrapper__item">
              <div class="address-inbox__image">
                <img src="@/assets/img/artc.svg" alt="" />
              </div>
              <div class="address-wrapper__title">PETWORLD 2022</div>
            </div>
            <div class="address-item__title">Privacy policy</div>
            <div class="address-item__subtitle">Terms of use</div>
          </div>

          <div class="address-icon">
            <div class="address-wrapper__image">
              <img src="@/assets/img/facebook.svg" alt="" />
            </div>
            <div class="address-wrapper__image">
              <img src="@/assets/img/IN.svg" alt="" />
            </div>
            <div class="address-wrapper__image">
              <img src="@/assets/img/Instagram.svg" alt="" />
            </div>
            <div class="address-wrapper__image">
              <img src="@/assets/img/Twitter.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Address",
};
</script>

<style lang="scss" scoped>
.address {
  padding: 50px 0px;
}
.address-body {
  display: flex;
  justify-content: space-between;
}
.address-info {
  display: flex;
  gap: 10px;
  margin-bottom: 50px;
}
.address-image img {
  width: 100%;
  cursor: pointer;
}
.address-info__title {
  font-weight: bold;
  cursor: pointer;
}
.address-inbox__title {
  font-size: 20px;
  margin-bottom: 12px;
  cursor: pointer;
}
.address-btn {
  margin-left: 20px;
  border-radius: 7px;
  padding: 15px 30px 15px 30px;
  color: white;
  background-color: #3366ff;
  border: none;
  font-size: 20px;
  cursor: pointer;
}
.address-btn:active {
  color: black;
}
.address-btn:hover {
  transition: 0.5s;
  background-color: #dfbf70;
  border-radius: 3px;
}
.address-inbox__item {
  margin-bottom: 30px;
}
.address-inbox__item input {
  padding: 12px 100px 12px 20px;
  border-radius: 7px;
  font-size: 20px;
}
.address-inbox__image {
  width: 20px;
  height: 20px;
  object-fit: cover;
  cursor: pointer;
}
.address-wrapper__item {
  display: flex;
  align-items: baseline;
}
.addres-item {
  display: flex;
  gap: 20px;
}
.address-wrapper__title {
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
}
.address-item__title {
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
}
.address-item__subtitle {
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
}
.address__block {
  display: flex;
  justify-content: space-between;
}
.address-block__text {
  display: flex;
  gap: 20px;
  padding-bottom: 36px;
  cursor: pointer;
}
.address-block__title {
  font-weight: bold;
  font-size: 20px;
  padding-bottom: 20px;
  cursor: pointer;
}
.address-block-subtitle {
  padding-bottom: 16px;
}
.address-wrapper__image {
  margin-left: 20px;
  cursor: pointer;
}
.address-icon {
  display: flex;
  cursor: pointer;
}

@media screen and (max-width: 992px) {
  .address-info {
    margin-bottom: 10px;
  }
  .address-inbox__item {
    margin: 10px;
  }
  .address-btn {
    margin-top: 10px;
    font-size: 15px;
  }
  .address-inbox__item input {
    padding: 12px 10px 12px 20px;
    font-size: 15px;
  }
  .address-block__text {
    display: flex;
    gap: 20px;
    padding-bottom: 10px;
  }
  .address-wrapper__item {
    align-items: baseline;
  }
}

@media screen and (max-width: 768px) {
  .address-body {
    flex-direction: column;
  }
  .addres-item {
    gap: 5px;
  }
  .address-info {
    display: flex;
    justify-content: center;
    gap: 5px;
  }
  .address-wrapper__block {
    order: 1;
    text-align: center;
    padding-bottom: 30px;
  }
  .address-block__text {
    justify-content: space-around;
    padding-bottom: 30px;
  }
  .address-btn {
    margin-left: 0px;
  }
  .address-inbox__item input {
    padding: 10px 0px 10px 5px;
    font-size: 12px;
    margin-right: 5px;
  }
  .address-btn {
    margin-top: 10px;
    font-size: 12px;
    padding: 12px 30px 12px 30px;
  }
}

@media screen and (max-width: 576px) {
  .address-wrapper {
    display: flex;
    flex-direction: column;
  }
  .address-info {
    margin-bottom: 40px;
  }
  .address-inbox__item input {
    font-size: 17px;
  }

  .address-inbox__item {
    display: flex;
    flex-direction: column;
  }
  .address-block__title {
    display: flex;
    flex-direction: column;
  }
  .address-btn {
    margin: 15px 0px 35px 0px;
    font-size: 17px;
  }
  .address-wrapper__image {
    padding-right: 20px;
    margin: 0px;
  }
  .address-block-subtitle {
    flex-direction: column;
  }
  .address-block__text {
    display: flex;
    flex-direction: column;
    padding-bottom: 50px;
    align-items: center;
  }
  .address-block__title {
    padding: 0px;
  }
  .address-wrapper__item {
    display: flex;
    align-items: baseline;
  }
  .address-item__title {
    display: flex;
  }
  .address-item__subtitle {
    display: flex;
  }
  .addres-item {
    display: flex;
    flex-direction: column;
    margin-bottom: 40px;
  }
  .addres-item {
    gap: 20px;
  }
  .address__block {
    flex-direction: column;
  }
  .address-wrapper__block {
    padding: 0px;
  }
}
</style>
