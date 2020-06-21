<template>
  <div>
    <header class="bg-dark">
      <nav-bar />
    </header>
    <main class="container" style="background: #333232;">
      <div class="row">
        <div class="col-md-8">
          <banner />
          <div class="row">
            <div class="col-md-12">
              <div class="d-flex justify-content-between mt-3 mb-3">
                <h4>
                  <i class="fa fa-plus-square" aria-hidden="true"></i> Phim bộ mới
                  cập nhật
                </h4>
                <a href="#" style="color:#DEDCDC">Xem tất cả >> </a>
              </div>
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
          </div>
          <!-- dsss -->
          <div class="row">
            <div class="col-md-12">
              <div class="d-flex justify-content-between mt-3 mb-3">
                <h4>
                  <i class="fa fa-plus-square" aria-hidden="true"></i> Phim lẻ
                  cập nhật
                </h4>
                <a href="#" style="color:#DEDCDC">Xem tất cả >> </a>
              </div>
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
          </div>
          <!-- fsdf -->
          <div class="row">
            <div class="col-md-12">
              <div class="d-flex justify-content-between mt-3 mb-3">
                <h4>
                  <i class="fa fa-plus-square" aria-hidden="true"></i> Phim sex
                  cập nhật
                </h4>
                <a href="#" style="color:#DEDCDC">Xem tất cả >> </a>
              </div>
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
            <div class="col-md-3 col-sm-6">
              <card />
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <h3 class="mt-3 text-uppercase">Tủ phim của bạn </h3>
          <div class="row">
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
          </div>
          <h3 class="mt-3 text-uppercase">Bảng xếp hạng</h3>
          <div class="row">
            <div class="col-md-12">
              <div class="row mb-3">
                <input type="button" value="Phim bộ" class="btn btn-primary col-md-3">
                <input type="button" value="Phim bộ" class="btn btn-warning col-md-3">
                <input type="button" value="Phim bộ" class="btn btn-danger col-md-3">
              </div>
            </div>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
          </div>
          <h3 class="mt-3 text-uppercase">Phim sắp chiếu  </h3>
          <div class="row">
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
            <card-nav></card-nav>
          </div>
        </div>
      </div>
    </main>
    <Footer/>
  </div>
</template>

<script>
import Navbar from "./layout/NavBar.vue";
import Banner from "./layout/Banner.vue";
import Card from "./layout/Card.vue";
import Footer from './layout/Footer.vue'
import CardNav from './items/CardNav.vue'
export default {
  name: "HomePage",
  components: {
    "nav-bar": Navbar,
    'banner': Banner,
    'card': Card,
    Footer,
    'card-nav': CardNav
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
