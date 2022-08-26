<template>
  <div class="back justify-content-between">
    <div class="logo text-white d-none d-md-inline-block">WATCH/LAB</div>
    <div class="btn-group dropend d-inline-block d-md-none">
      <div
        class="logo text-white dropdown-toggle"
        data-bs-toggle="modal"
        data-bs-target="#exampleModal"
      >
        W/L
      </div>
    </div>
    <!-- MENU MODAL -->
    <div
      class="modal fade"
      id="exampleModal"
      tabindex="-1"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title w-100" id="exampleModalLabel">
              <div class="logo text-white">
                WATCH/LAB

                <button
                  type="button"
                  class="btn-close"
                  data-bs-dismiss="modal"
                  aria-label="Close"
                ></button>
              </div>
            </h5>
          </div>
          <div class="modal-body text-center">
            <ul class="drop-ul">
              <li class="drop-item" v-for="(name, i) in menu" :key="i">
                <a class="dropdown-item me-3" href="#">
                  {{ name }}
                  <i :class="icons[i]"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="menu d-none d-md-flex">
      <span class="links" v-for="(name, i) in menu" :key="i">{{ name }}</span>
    </div>
    <div class="searchbar">
      <input class="inp w-50" type="search" />
      <i class="fas fa-search ic"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderStandard",
  data() {
    return {
      menu: ["About-us", "Brand", "Projects", "Magazine", "Press", "Contacts"],
      icons: [
        "fa-solid fa-address-card",
        "fa-brands fa-stumbleupon",
        "fa-solid fa-diagram-project",
        "fa-solid fa-newspaper",
        "fa-solid fa-print",
        "fa-solid fa-address-book",
      ],
    };
  },
};
</script>

<style scoped lang="scss">
$H-outside: 15px;
.drop-ul {
  list-style: none;
  padding: 0;
  .drop-item {
    line-height: 2rem;
  }
  .dropdown-item:hover {
    color: #cec4b4;
  }
}
.modal-header {
  justify-content: center;
}
.links {
  cursor: pointer;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border-bottom: transparent 3px solid;
}
.links:hover {
  color: #cec4b4;
  border-bottom: #cec4b4 3px solid;
}
.back {
  width: 100%;
  height: 72px;
  display: flex;
  font-family: "montserrat";
  color: #2c3e50;
}
.logo {
  cursor: pointer;
  display: flex;
  font-size: 2rem;
  padding: $H-outside 30px;
  flex-direction: row;
  background-color: #cec4b4;
  align-items: center;
  font-family: "montserrat-bold";
}
.menu {
  display: flex;
  font-size: 0.9rem;
  flex-direction: row;
  flex-grow: 1;
  justify-content: space-around;
  align-items: center;
}
.searchbar {
  padding: $H-outside;
  width: 15%;
  display: flex;
  justify-content: center;
  .inp {
    border: none;
    border-bottom: 1px solid black;
    padding: 5px 10px;
    outline: none;
  }
  .ic {
    align-self: center;
    color: black;
  }
}
@media screen and (max-width: 768px) {
}
@media screen and (max-width: 576px) {
  .searchbar {
    padding: calc($H-outside / 2);
    width: 35%;
    display: flex;
    justify-content: center;
  }
}
</style>
