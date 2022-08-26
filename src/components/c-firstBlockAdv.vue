<template>
  <div class="container-fluid container-md">
    <!-- BLOCCO 1 -->
    <div class="blocco1">
      <div class="title my-4">
        {{ title1 }}<br />
        {{ title2 }}
      </div>
      <div
        class="content d-flex flex-md-row flex-column justify-content-md-between"
      >
        <div class="content1">
          {{ text1 }}
        </div>
        <div class="content2">
          {{ text2 }}
        </div>
      </div>
    </div>
    <!-- BLOCCO 2 -->
    <div class="blocco2 row row-cols-1 row-cols-md-2">
      <div class="col order-1 order-md-0">
        <div class="sizingCont">
          <div class="blocco2Content p-5">
            <div>
              <div class="top-title">{{ topTitle }}</div>
              <div class="title">{{ title3 }}</div>
            </div>
            <div>
              <div class="content">{{ content3 }}</div>
              <button
                type="button"
                id="mybtn"
                class="bottone btn btn-outline-dark"
              >
                Discover
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="col order-0 order-md-1">
        <div class="imagecont">
          <img
            class="image1"
            src="../assets/images/imgwinter.png"
            alt=""
            srcset=""
          />
        </div>
      </div>
      <div class="col order-2">
        <div class="imagecont">
          <img
            class="image1"
            src="../assets/images/imgnight.png"
            alt=""
            srcset=""
          />
        </div>
      </div>
      <div class="col order-3">
        <div class="sizingCont">
          <div class="blocco2Content pt-5">
            <div>
              <div class="top-title">{{ topTitle }}</div>
              <div class="title">{{ title4 }}</div>
            </div>
            <div>
              <div class="content">{{ content3 }}</div>
              <button type="button" class="bottone btn btn-outline-dark">
                Discover
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- BLOCCO 3 -->
    <div class="blocco3">
      <div class="title">
        <div class="h-100 bg-white">
          Press from <br />
          Watch Lab Studio
        </div>
      </div>
      <div class="blocco3Cont">
        <div class="first">
          <div class="cont">
            <div class="content">{{ content4 }}</div>
          </div>
        </div>
        <div class="second">
          <div class="cont">
            <div
              id="carouselControls"
              class="carousel slide"
              data-bs-ride="carousel"
            >
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img
                    src="../assets/images/image3block2.jpeg"
                    class="d-block w-100"
                    alt="..."
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="../assets/images/image3block2.jpeg"
                    class="d-block w-100"
                    alt="..."
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="../assets/images/image3block2.jpeg"
                    class="d-block w-100"
                    alt="..."
                  />
                </div>
              </div>
              <div class="model2 carouselArrow mt-5">
                <button
                  class="carousel-control-prev"
                  type="button"
                  data-bs-target="#carouselControls"
                  data-bs-slide="prev"
                >
                  <span
                    class="carousel-control-prev-icon"
                    aria-hidden="true"
                  ></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button
                  class="carousel-control-next"
                  type="button"
                  data-bs-target="#carouselControls"
                  data-bs-slide="next"
                >
                  <span
                    class="carousel-control-next-icon"
                    aria-hidden="true"
                  ></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
            </div>
          </div>
          <div class="infoCarousel">
            <div class="top-title">
              <div>PRESS</div>
              <div class="text">18 SETTEMBRE 2015</div>
            </div>
            <div class="title">
              Most Important <br />
              Days on Watchlab
            </div>
            <div class="carouselArrow mt-5">
              <button
                class="model1 carousel-control-prev"
                type="button"
                data-bs-target="#carouselControls"
                data-bs-slide="prev"
              >
                <span
                  class="carousel-control-prev-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="model1 carousel-control-next"
                type="button"
                data-bs-target="#carouselControls"
                data-bs-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- BLOCCO 4 -->
    <div class="blocco4">
      <div class="su1">
        <img
          src="../assets/images/last.jpeg"
          class="img-fluid"
          alt=""
          srcset=""
        />
        <div class="img-content">
          <div class="top-title">INSTAGRAM</div>
          <div class="main-title">
            Discover <br />
            Watch Lab
          </div>
        </div>
      </div>
      <div class="cont container-fluid">
        <div class="row row-cols-2">
          <div class="col">
            <div class="suMany">
              <img
                src="../assets/images/b1.png"
                class="img-fluid"
                alt=""
                srcset=""
              />
              <div class="imgCont">
                <div class="card mb-4 rounded-3 shadow-sm">
                  <div class="card-header py-3">
                    <h4 class="my-0 fw-normal">Free</h4>
                  </div>
                  <div class="card-body">
                    <h1 class="card-title pricing-card-title">
                      $0<small class="text-muted fw-light">/mo</small>
                    </h1>

                    <button
                      type="button"
                      class="w-100 btn btn-lg btn-outline-dark"
                    >
                      Sign up for free
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="suMany">
              <img
                src="../assets/images/b2.png"
                class="img-fluid"
                alt=""
                srcset=""
              />
            </div>
          </div>
          <div class="col">
            <div class="suMany">
              <img
                src="../assets/images/b3.png"
                class="img-fluid"
                alt=""
                srcset=""
              />
            </div>
          </div>
          <div class="col">
            <div class="suMany">
              <img
                src="../assets/images/b4.png"
                class="img-fluid"
                alt=""
                srcset=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "App",
  data() {
    return {
      carouselImages: ["../assets/images/image3block2.jpeg"],
      title1: "History and",
      title2: "Patriarcal season",
      text1:
        "On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire",
      text2:
        "But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No that are extremely painful",
      topTitle: "LONDON COLLECTION TITLE",
      title3: "Temporary Store",
      title4: "New Collection Henri London",
      title5: "Press from Watch Lab Studio",
      content3:
        "On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire",
      content4:
        "On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain trouble",
    };
  },
};
</script>
<style scoped lang="scss">
.bottone {
  margin-top: 4rem;
  border-radius: 0;
  width: 250px;
  height: 50px;
  font-family: "miller";
}
.blocco1 {
  font-family: "miller";
  .title {
    max-width: 45%;
    font-size: 60px;
    line-height: 70px;
  }
  .content1 {
    display: inline-block;
    width: 40%;
    color: gray;
    font-size: 1rem;
    line-height: 2em;
  }
  .content2 {
    width: 50%;
    display: inline-block;
    color: gray;
    font-size: 1rem;
    line-height: 2em;
  }
}
.blocco2 {
  margin: 100px 0;
  * {
    padding: 0;
  }
  .sizingCont {
    height: 100%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    .blocco2Content {
      height: 100%;
      align-self: center;
      display: flex;
      flex-direction: column;
      justify-content: space-around;
      padding: 0 4rem;
      text-align: center;
      .top-title {
        letter-spacing: 4px;
        margin-bottom: 2rem;
        word-spacing: 10px;
        font-size: 0.8rem;
        font-family: "montserrat-bold";
      }
      .title {
        font-family: "miller";
        word-spacing: 6px;
        letter-spacing: 2px;
        line-height: 3.8rem;
        font-size: 3.5rem;
      }
      .content {
        color: gray;
        font-size: 1rem;
        line-height: 2em;
      }
    }
  }
  .imagecont {
    height: 100%;
    overflow: hidden;
  }
  .imagecont:hover .image1 {
    transform: scale(1.1);
    filter: sepia(0.5);
  }
  .image1 {
    height: 100%;
    transition: transform 0.5s;
    width: 100%;
    background-color: red;
  }
}
.blocco3 {
  .title {
    background-color: #f7f9f8;
    font-family: "miller";
    font-size: 60px;
    .bg-white {
      width: 50%;
    }
  }
  .blocco3Cont {
    display: flex;
    .first {
      display: inline-block;
      width: 50%;
      .cont {
        .content {
          margin-top: 3rem;
          display: flex;
          width: 50%;
          color: gray;
          font-size: 1rem;
          line-height: 2em;
        }
      }
    }
    .second {
      display: flex;
      position: relative;
      padding-bottom: 3rem;
      width: 50%;
      background-color: #f7f9f8;

      .infoCarousel {
        padding: 0 2rem;
        transform: translate(70%);
        width: 50%;
        position: absolute;
        .top-title {
          letter-spacing: 4px;
          margin-bottom: 2rem;
          font-size: 0.8rem;
          font-family: "montserrat-bold";
          div:last-child {
            color: #ddcc92;
          }
        }
        .title {
          font-family: "miller";
          font-size: 2rem;
        }
      }
      .cont {
        transform: translateX(-50%);
        width: 70%;
      }
      .model2 {
      }
      .model1.carousel-control-next-icon,
      .model1.carousel-control-prev-icon {
        filter: invert(100%);
        transform: scale(0.5);
      }

      .model1.carousel-control-next,
      .model1.carousel-control-prev {
        position: static;
        display: inline;
        top: 0;
        height: fit-content;
        align-items: center;
        justify-content: center;
        width: 50px;
        padding: 0;
        color: #fff;
        text-align: center;
        background: 0 0;
        border: 0;
      }
    }
  }
}
.blocco4 {
  display: flex;
  $blockHeight: 650px;
  height: $blockHeight;
  margin: 4rem 0;
  .cont {
    width: 50%;
  }
  .row > * {
    padding: 0;
  }
  img {
    transition: transform 0.5s;
    z-index: -1;
    height: 100%;
    width: 100%;
  }
  .su1:hover .img-content {
    transform: scale(1.1);
  }
  .su1 {
    height: 100%;
    width: 50%;
    display: flex;
    align-content: center;
    align-items: center;
    justify-content: center;
    img {
      filter: contrast(0.5);
    }

    .img-content {
      transition: transform 0.5s;
      text-align: center;
      position: absolute;
      font-family: "miller";
      color: white;
      font-size: 2rem;
      .top-title {
        font-family: "montserrat";
        font-size: 0.7rem;
      }
      .main-title {
        margin: 5rem 0;
        font-size: 3rem;
      }
    }
  }
  .suMany:hover img {
    transform: scale(1.1);
    filter: contrast(0.5);
  }
  .suMany:hover .imgCont {
    display: block;
  }
  .suMany {
    position: relative;
    overflow: hidden;
    height: calc($blockHeight / 2);
    .imgCont {
      display: none;
      transition: transform 5s;
      width: 100%;
      position: absolute;
      bottom: 0;
      z-index: 100000;
    }
  }
}
@media screen and (min-width: 1200px) {
  .blocco3Cont {
    .model2 {
      display: none;
    }
    .model1 .carousel-control-next-icon,
    .model1 .carousel-control-prev-icon {
      filter: invert(100%);
      transform: scale(0.5);
    }
    .model1.carousel-control-next,
    .model1.carousel-control-prev {
      position: static;
      display: inline;
      top: 0;
      height: fit-content;
      align-items: center;
      justify-content: center;
      width: 50px;
      padding: 0;
      color: #fff;
      text-align: center;
      background: 0 0;
      border: 0;
    }
  }
}
@media screen and (max-width: 1200px) {
  .blocco3 {
    .title {
      .bg-white {
        width: 100%;
      }
    }
    .blocco3Cont {
      display: flex;
      flex-direction: column;
      .first {
        width: 100%;
        .cont {
          .content {
            margin-top: 2rem;
            margin-bottom: 1rem;
            display: flex;
            width: 100%;
            color: gray;
            font-size: 1rem;
            line-height: 2em;
            text-align: justify;
          }
        }
      }
      .second {
        display: flex;
        position: static;
        padding: 3rem;
        width: 100%;
        background-color: #f7f9f8;

        .infoCarousel {
          transform: translate(0%);
          position: relative;
          .top-title {
            letter-spacing: 4px;
            margin-bottom: 2rem;
            font-size: 0.8rem;
            font-family: "montserrat-bold";
            div:last-child {
              color: #ddcc92;
            }
          }
          .title {
            font-family: "miller";
            font-size: 2rem;
          }
        }
        .cont {
          transform: translateX(0%);
          width: 70%;
        }
        .model2 {
          display: none;
        }
        .model1 .carousel-control-next-icon,
        .model1 .carousel-control-prev-icon {
          filter: invert(100%);
          transform: scale(0.5);
        }
        .model1.carousel-control-next,
        .model1.carousel-control-prev {
          position: static;
          display: inline;
          top: 0;
          height: fit-content;
          align-items: center;
          justify-content: center;
          width: 50px;
          padding: 0;
          color: #fff;
          text-align: center;
          background: 0 0;
          border: 0;
        }
      }
    }
  }
}
@media screen and (max-width: 1000px) {
  .blocco1 {
    font-family: "miller";

    .title {
      width: 100%;
      max-width: 100%;
      font-size: 60px;
      line-height: 70px;
      br {
        display: none;
      }
    }
    .content1 {
      display: inline-block;
      width: 100%;
      color: gray;
      font-size: 1rem;
      line-height: 2em;
    }
    .content2 {
      width: 100%;
      display: inline-block;
      color: gray;
      font-size: 1rem;
      line-height: 2em;
    }
  }
  .infoCarousel {
    .title {
      font-size: 1.5rem !important;
    }
  }
  .blocco4 {
    flex-direction: column;
    $blockHeight: 250px;
    height: fit-content;
    margin: 4rem 0;
    .cont {
      width: 100%;
    }
    .row > * {
      padding: 0;
    }
    img {
      object-fit: cover;
      z-index: -1;
      height: 100%;
      width: 100%;
    }
    .su1 {
      width: 100%;
      height: 50%;
      display: flex;
      align-content: center;
      align-items: center;
      justify-content: center;
      img {
        filter: contrast(0.5);
      }
      .img-content {
        text-align: center;
        position: absolute;
        font-family: "miller";
        color: white;
        font-size: 2rem;
        .top-title {
          font-family: "montserrat";
          font-size: 0.7rem;
        }
        .main-title {
          margin: 5rem 0;
          font-size: 3rem;
        }
      }
    }
    .suMany {
      height: calc($blockHeight / 2);
    }
  }
}
@media screen and (max-width: 768px) {
  .blocco3 {
    .blocco3Cont {
      display: flex;
      flex-direction: column;
      .first {
        width: 100%;
        .cont {
          .content {
            margin-top: 2rem;
            margin-bottom: 1rem;
            display: flex;
            width: 100%;
            color: gray;
            font-size: 1rem;
            line-height: 2em;
            text-align: justify;
          }
        }
      }
      .second {
        display: flex;
        flex-direction: column-reverse;
        position: static;
        padding: 3rem;
        width: 100%;
        background-color: #f7f9f8;

        .infoCarousel {
          transform: translate(0%);
          width: 100%;
          padding: 0;
          position: relative;
          br {
            display: none;
          }
          .top-title {
            letter-spacing: 4px;
            margin-bottom: 1rem;
            font-size: 0.8rem;
            font-family: "montserrat-bold";
            div:last-child {
              color: #ddcc92;
            }
          }
          .title {
            width: 100%;
            font-family: "miller";
            font-size: 2rem;
          }
        }
        .cont {
          transform: translateX(0%);
          width: 100%;
        }
        .model2 {
          display: inline-block;
        }
        .model1.carousel-control-next,
        .model1.carousel-control-prev {
          display: none;
        }
      }
    }
  }
  .blocco4 {
    flex-direction: column;
    $blockHeight: 400px;
    height: fit-content;
    margin: 4rem 0;
    .cont {
      width: 100%;
    }
    .row > * {
      padding: 0;
    }
    img {
      object-fit: cover;
      z-index: -1;
      height: 100%;
      width: 100%;
    }
    .su1 {
      width: 100%;
      height: 100%;
      display: flex;
      align-content: center;
      align-items: center;
      justify-content: center;
      img {
        filter: contrast(0.5);
      }
      .img-content {
        text-align: center;
        position: absolute;
        font-family: "miller";
        color: white;
        font-size: 2rem;
        .top-title {
          font-family: "montserrat";
          font-size: 0.7rem;
        }
        .main-title {
          margin: 2rem 0;
          font-size: 3rem;
        }
      }
    }
    .suMany {
      height: calc($blockHeight / 2);
    }
  }
}
</style>
