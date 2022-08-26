<template>
  <div class="hero px-4 py-5 text-center text-white">
    <!-- <div class="background-hero"></div> -->
    <img
      src="../assets/images/hero_img.jpeg"
      class="img-fluid heroImg first"
      alt=""
      srcset=""
    />
    <!-- CENTRAL CONTENT -->
    <div class="content">
      <div class="content-top">LONDON COLLECTION SEASON</div>
      <div class="title mt-3 mt-md-5">
        New Selection Of <br />
        Herny London
      </div>
      <div class="col-lg-6 mx-auto">
        <div class="lead mb-4">
          An estimable experience in the modern collection house
        </div>
        <button type="button" id="mybtn" class="btn btn-outline-light mt-4">
          Discover
        </button>
      </div>
    </div>

    <!-- OROLOGIO ADV -->
    <div class="bol">
      <img
        src="../assets/images/orologio.jpeg"
        class="heroImg2"
        alt=""
        srcset=""
      />
      <div class="advertise">
        <div class="advertise-content text-start">
          The Path to Success <br />
          with Watchlab
        </div>
        <div class="btn-next">Next ></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "HeroStand",
};
</script>
<style scoped lang="scss">
.hero {
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-content: center;
  position: relative;
  height: 80vh;
}

#mybtn {
  border-radius: 0;
  width: 250px;
  height: 50px;
  font-family: "miller";
}
.content {
  z-index: 1;
  .content-top {
    word-spacing: 6px;
    font-size: 0.9rem;
    font-family: "montserrat-bold";
    margin-bottom: 2rem;
  }
  .title {
    font-family: "miller";
    word-spacing: 6px;
    letter-spacing: 2px;
    line-height: 4rem;
    font-size: 3.8rem;
  }
  .lead {
    margin-top: 2rem;
    font-family: "montserrat", sans-serif;
    font-size: 0.7rem;
    font-weight: 700;
  }
}
.bol {
  position: absolute;
  width: 25%;
  height: 40%;
  min-height: 200px;
  right: 0px;
  bottom: 0;
}
.advertise {
  align-self: flex-end;
  position: relative;
  height: 100%;
  width: 100%;
}
.advertise-content {
  font-family: "miller", sans-serif;
  z-index: 1;
  position: absolute;
  top: 2rem;
  font-size: larger;
  left: 1rem;
}
.btn-next {
  position: absolute;
  letter-spacing: 4px;
  font-family: "montserrat", sans-serif;
  word-spacing: 1.8rem;
  bottom: 2rem;
  right: 2rem;
  z-index: 1;
  cursor: pointer;
}
.heroImg.first {
  position: absolute;
  transition: transform 0.5s;
  filter: brightness(60%);
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.heroImg2 {
  border-radius: 0rem;
  position: absolute;
  transition: transform 0.5s;
  filter: brightness(60%);
  bottom: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.hero:hover .heroImg.first {
  transform: scale(1.1);
}

@media screen and (max-width: 768px) {
  .bol {
    margin-top: 6rem;
    position: relative;
    width: 100%;
    height: 23%;
    min-height: fit-content;
    .heroImg2 {
      border-radius: 50px;
    }
  }
}
@media screen and (max-width: 576px) {
  .bol {
    display: none;
    min-height: fit-content;
  }
  .content {
    z-index: 1;
    .content-top {
      word-spacing: 6px;
      font-size: 0.9rem;
      font-family: "montserrat-bold";
      margin-bottom: 2rem;
    }
    .title {
      font-family: "miller";
      word-spacing: 6px;
      letter-spacing: 2px;
      line-height: 3.5rem;
      font-size: 3rem;
    }
    .lead {
      margin-top: 2rem;
      font-family: "montserrat", sans-serif;
      font-size: 0.7rem;
      font-weight: 700;
    }
  }
}
</style>
