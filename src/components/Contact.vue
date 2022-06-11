<template>
  <div class="contact">
    <div class="container">
      <div class="contact-wrapper">
        <div class="contact-info">
          <div class="contact-title">Let’s talk, <br />woof!</div>
          <div class="contact-subtitle">
            You can ask us questions about your pet, <br />and we will be happy
            to answer you!
          </div>
          <button class="contact-btn">Contact us</button>
        </div>
        <div class="contact-item">
          <div class="contact-image">
            <img src="@/assets/img/buldok.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style lang="scss" scoped>
.contact {
  padding: 50px 0px;
}
.contact-wrapper {
  display: flex;
  justify-content: center;
  gap: 150px;
  align-items: center;
}
.contact-title {
  font-size: 80px;
  font-weight: bold;
  margin-bottom: 30px;
  cursor: pointer;
}
.contact-subtitle {
  font-size: 20px;
  padding-bottom: 40px;
}
.contact-btn {
  padding: 15px 45px;
  font-size: 20px;
  color: white;
  background-color: #dfbf70;
  border-radius: 10px;
  border: none;
  cursor: pointer;
}
.contact-btn:hover {
  transition: 0.5s;
  background: #2a50c1;
}
.contact-image img {
  width: 100%;
  cursor: pointer;
}


@media screen and (max-width: 1200px) {
  .contact-title {
    font-size: 60px;
  }
}


@media screen and (max-width: 992px) {
  .contact-title {
    font-size: 40px;
  }
  .contact-subtitle {
    font-size: 15px;
    padding-bottom: 20px;
  }
  .contact-btn {
    font-size: 15px;
  }
}


@media screen and (max-width: 768px) {
  .contact-title {
    font-size: 30px;
    margin-bottom: 10px;
  }
  .contact-subtitle {
    font-size: 15px;
    padding-bottom: 10px;
  }
  .contact-btn {
    font-size: 13px;
    padding: 8px 30px;
    border-radius: 5px;
  }
  .contact-wrapper {
    gap: 100px;
  }
}


@media screen and (max-width: 576px) {
  .contact-wrapper {
    display: flex;
    flex-direction: column;
    gap: 60px;
  }
  .contact-info {
    text-align: center;
  }
  .contact-subtitle {
    padding-bottom: 40px;
  }
}
</style>
