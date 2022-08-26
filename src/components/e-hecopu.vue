<template>
  <div>
    <nav class="navbar navbar-light bg-light">
      <div class="container-fluid">
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarToggleExternalContent2"
          aria-controls="navbarToggleExternalContent2"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
      </div>
    </nav>
    <div class="collapse" id="navbarToggleExternalContent2">
      <div class="bg-light shadow-3 p-4">
        <button class="btn btn-link btn-block border-bottom m-0">Link 1</button>
        <button class="btn btn-link btn-block border-bottom m-0">Link 2</button>
        <button class="btn btn-link btn-block m-0">Link 3</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderStandard",
  data() {
    return {
      menu: ["About-us", "Brand", "Projects", "Magazine", "Press", "Contacts"],
    };
  },
};
</script>

<style scoped lang="scss">
$H-outside: 15px;
.back {
  width: 100%;
  height: 72px;
  display: flex;
  font-family: "montserrat";
  color: #2c3e50;
}
.logo {
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
  .searchbar {
    padding: calc($H-outside / 2);
    width: 7%;
    display: flex;
    justify-content: center;
    .inp {
      border: none;
      border-bottom: 1px solid black;
      padding: 3px 5px;
      outline: none;
    }
    .ic {
      align-self: center;
      color: black;
    }
  }
}
@media screen and (max-width: 576px) {
  .searchbar {
    padding: calc($H-outside / 2);
    width: 35%;
    display: flex;
    justify-content: center;
    .inp {
      border: none;
      border-bottom: 1px solid black;
      padding: 3px 5px;
      outline: none;
    }
    .ic {
      align-self: center;
      color: black;
    }
  }
}
</style>
