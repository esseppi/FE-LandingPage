<template>
  <div class="mb-0">
    <div class="top-footer text-center">
      <img class="myimg img-fluid" src="../assets/images/getinTouch.jpeg" />
      <div class="cont">
        <div class="col-12 col-lg-4 mx-auto">
          <div class="d-flex flex-column h-100">
            <div class="title">Get in Touck</div>
            <div class="content my-3">
              DISCOVER MORE ABOUT NEWS, <br />
              EXCLUSIVE EVENTS AND DISCOUNT
            </div>
            <div class="d-flex justify-content-center">
              <div class="mailInput">
                <div class="input-group has-validation">
                  <input
                    type="email"
                    placeholder="type your email"
                    class="form-control emailInp"
                    id="validationTooltipEmail"
                    aria-describedby="validationTooltipEmailPrepend"
                    required
                  />
                  <div class="invalid-tooltip">
                    Please choose a valid email.
                  </div>
                </div>
              </div>
              <button type="submit" class="btn btn-outline-light">ok</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="_footer px-5 py-3">
      <footer class="py-5">
        <div class="row justify-content-start">
          <div class="title col-4 mb-3">WATCH/LAB</div>
        </div>
        <div class="row justify-content-start">
          <div class="col-12 col-md-4 mb-3">
            <ul class="nav flex-column">
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">
                  <span class="me-3"> Watch/Lab Innovation</span>
                  <span> brings success</span></a
                >
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links"
                  >Via Borgogna 5, Milan</a
                >
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Italy</a>
              </li>
            </ul>
          </div>
          <div class="col-md-2 col-4 mb-3">
            <ul class="nav flex-column">
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">About us</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Brand</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Project</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Magazine</a>
              </li>
            </ul>
          </div>
          <div class="col-md-2 col-4 mb-3">
            <ul class="nav flex-column">
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Press</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Contacts</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Privacy Polocy</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">Search</a>
              </li>
            </ul>
          </div>
          <div class="col-md-3 col-4 mb-3">
            <ul class="nav flex-column">
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links">T. +39 392 9133937</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link p-0 f-links"
                  >M. info@watch-lab.it</a
                >
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link exeption2 p-0">FACEBOOK</a>
              </li>
              <li class="nav-item mb-2">
                <a href="#" class="nav-link exeption2 p-0">INSTAGRAM</a>
              </li>
            </ul>
          </div>
        </div>
      </footer>
    </div>
    <div class="bottom-footer p-3">
      <div class="container">
        <div class="w-100 d-flex text-light justify-content-between">
          <span>Copyright Watch/Lab all rights reserved</span>
          <span>website by nssfactory</span>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "App",
};
</script>
<style scoped lang="scss">
.top-footer {
  position: relative;
  height: 250px;
  color: white;
  .cont {
    z-index: 2;
    display: flex;
    align-items: center;
    height: 100%;
    width: 100%;
  }
  .myimg {
    z-index: -1;
    position: absolute;
    filter: contrast(0.5) sepia(0.5);
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
  }
  .title {
    font-family: "miller";
    font-size: 3rem;
  }
  .content {
    font-family: "montserrat";
    font-size: small;
  }
  .btn {
    border-radius: 0;
  }
  .mailInput {
    margin-right: 2rem;

    .emailInp {
      border-radius: 0;
      padding: 1rem;
      background-color: transparent;
      color: white;
      border-color: white;
      font-family: "miller";
    }
    .emailInp::placeholder {
      color: white;
    }
  }
}
._footer {
  background-color: #323332;
  .title {
    font-family: "montserrat-bold";
    color: #ffeed6;
    font-size: 2rem;
  }
  .exeption2 {
    font-family: "montserrat-bold";
    color: #d1c4b5;
    font-size: smaller;
    letter-spacing: 3px;
  }
  .f-links {
    font-family: "miller";
    color: #d1c4b5;
  }
}
.bottom-footer {
  font-family: "merryweather";
  background-color: #303030;
  span {
    font-size: xx-small;
    color: #d1c4b5;
  }
}
</style>
