<template>
  <login-form v-if="isLoginForm"></login-form>
  <registerForm v-if="isRegisterForm"></registerForm>
  <div>
    <header class="header">
      <div class="grid">
        <nav class="header__navbar hide-on-mobile-tablet">
          <ul class="header__navbar-list">
            <li
              class="header__navbar-item header__navbar-item-has-qr header__navbar-item--separete"
            >
              Vào cửa hàng trên ứng dụng F8-shop
              <div class="header__qr">
                <img src="../assets/img/QR_code.png" class="header__qr-img" />
                <div class="header__qr-apps">
                  <a href="" class="header__qr-link"
                    ><img
                      src="../assets/img/Google.png"
                      class="header__qr-download-img"
                  /></a>
                  <a href="" class="header__qr-link"
                    ><img
                      src="../assets/img/CHPlay.png"
                      class="header__qr-download-img"
                  /></a>
                </div>
              </div>
            </li>
            <li class="header__navbar-item">
              <span class="header__navbar-title--no-pointer">Kết nối</span>
              <a href="" class="header__navbar-icon-link">
                <i class="header__navbar-icon fab fa-facebook"></i>
              </a>
              <a href="" class="header__navbar-icon-link">
                <i class="header__navbar-icon fab fa-instagram"></i>
              </a>
            </li>
          </ul>
          <ul class="header__navbar-list">
            <li class="header__navbar-item header__navbar-item--has-notify">
              <a href="" class="header__navbar-icon-link">
                <i class="header__navbar-icon far fa-bell"></i>
                Thông báo</a
              >
              <div class="header__notify">
                <header class="header__notify-header">
                  <h3>Thông báo mới nhận</h3>
                </header>
                <ul class="header__notify-list">
                  <li class="header__notify-item header__notify-item--view">
                    <a href="" class="header__notify-link">
                      <img
                        src="../assets/img/Google.png"
                        class="header__notify-img"
                      />
                      <div class="header__notify-info">
                        <span class="header__notify-name"
                          >Mỹ phẩm shopee chính hãng</span
                        >
                        <span class="header__notify-description">
                          Mô tả mỹ phẩm shopee chính hãng
                        </span>
                      </div>
                    </a>
                  </li>
                  <li class="header__notify-item">
                    <a href="" class="header__notify-link">
                      <img
                        src="../assets/img/Google.png"
                        class="header__notify-img"
                      />
                      <div class="header__notify-info">
                        <span class="header__notify-name"
                          >Mỹ phẩm shopee chính hãng</span
                        >
                        <span class="header__notify-description">
                          Mô tả mỹ phẩm shopee chính hãng
                        </span>
                      </div>
                    </a>
                  </li>
                  <li class="header__notify-item">
                    <a href="" class="header__notify-link">
                      <img
                        src="../assets/img/Google.png"
                        class="header__notify-img"
                      />
                      <div class="header__notify-info">
                        <span class="header__notify-name"
                          >Mỹ phẩm shopee chính hãng</span
                        >
                        <span class="header__notify-description">
                          Mô tả mỹ phẩm shopee chính hãng
                        </span>
                      </div>
                    </a>
                  </li>
                </ul>
                <footer class="header__notify-footer">
                  <a href="" class="header__notify-ntn"> Xem tất cả </a>
                </footer>
              </div>
            </li>
            <li class="header__navbar-item">
              <a href="" class="header__navbar-icon-link">
                <i class="header__navbar-icon far fa-question-circle"></i>
                Trợ giúp</a
              >
            </li>
            <li
              @click="showRegisterForm()"
              class="header__navbar-item header__navbar-item--bold header__navbar-item--separete"
            >
              Đăng ký
            </li>
            <li
              @click="showLoginForm()"
              class="header__navbar-item header__navbar-item--bold"
            >
              Đăng nhập
            </li>
          </ul>
        </nav>
        <!-- khung tim kiem -->
        <div class="header__with-search">
          <div class="header__logo">
            <a>
              <img src="../assets/img/lazada.png" class="header__logo-img" />
            </a>
          </div>

          <!-- search history -->
          <div class="header__search">
            <div class="header__search-input-wrap">
              <input
                type="text"
                class="header__search-input"
                placeholder="Nhập để tìm kiếm sản phẩm"
              />
              <div class="header__search-history">
                <h3 class="header__search-history-heading">Lịch sử tìm kiếm</h3>
                <ul class="header__search-history-list">
                  <li class="header__search-history-item">
                    <a href="">Kem dưỡng da</a>
                  </li>
                  <li class="header__search-history-item">
                    <a href="">Kem tri mụn</a>
                  </li>
                  <li class="header__search-history-item">
                    <a href="">Kem đá</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="header__search-select">
              <span class="header__search-select-label">Trong shop</span>
              <i class="header__search-select-icon fas fa-angle-down"></i>
              <ul class="header__search-option">
                <li
                  class="header__search-option-item header__search-option-item--active"
                >
                  <span>Trong shop</span>
                  <i class="fas fa-check"></i>
                </li>
                <li class="header__search-option-item">
                  <span>Ngoài shop</span>
                  <i class="fas fa-check"></i>
                </li>
              </ul>
            </div>
            <button class="header__search-btn">
              <i class="header__search-btn-icon fas fa-search"></i>
            </button>
          </div>

          <!-- giỏ hàng -->
          <div class="header__cart">
            <div class="header__cart-wrap">
              <i class="header__cart-icon fas fa-shopping-cart"></i>
              <span class="header__cart-notice">3</span>
              <!-- không có sản phẩm: header__cart-list--no-cart -->
              <div class="header__cart-list">
                <img
                  src="../assets/img/R.png"
                  class="header__cart-list--no-cart-img"
                />
                <span class="header__cart-list--no-cart-msg"
                  >Chưa có sản phẩm</span
                >

                <!-- có sản phẩm -->
                <h4 class="header__cart--heading">Sản phẩm đã thêm</h4>
                <ul class="header__cart-list-item">
                  <li class="header__cart-item">
                    <img src="../assets/img/1.jpg" class="header__cart-img" />
                    <div class="header__cart-item-info">
                      <div class="header__cart-item-head">
                        <h5 class="header__cart-item-name">
                          Bộ kem đặc trị vùng mắt
                        </h5>
                        <div class="header__cart-item-price-wrap">
                          <span class="header__cart-item-price">2.000.000</span>
                          <span class="header__cart-item-multiply">x</span>
                          <span class="header__cart-item-qnt">1</span>
                        </div>
                      </div>
                      <div class="header__cart-item-body">
                        <span class="header__cart-item-decription"
                          >Phân loại bạc</span
                        >
                        <span class="header__cart-item-remove">xóa</span>
                      </div>
                    </div>
                  </li>
                  <li class="header__cart-item">
                    <img src="../assets/img/1.jpg" class="header__cart-img" />
                    <div class="header__cart-item-info">
                      <div class="header__cart-item-head">
                        <h5 class="header__cart-item-name">
                          Bộ kem đặc trị vùng mắt
                        </h5>
                        <div class="header__cart-item-price-wrap">
                          <span class="header__cart-item-price">2.000.000</span>
                          <span class="header__cart-item-multiply">x</span>
                          <span class="header__cart-item-qnt">1</span>
                        </div>
                      </div>
                      <div class="header__cart-item-body">
                        <span class="header__cart-item-decription"
                          >Phân loại bạc</span
                        >
                        <span class="header__cart-item-remove">xóa</span>
                      </div>
                    </div>
                  </li>
                  <li class="header__cart-item">
                    <img src="../assets/img/1.jpg" class="header__cart-img" />
                    <div class="header__cart-item-info">
                      <div class="header__cart-item-head">
                        <h5 class="header__cart-item-name">
                          Bộ kem đặc trị vùng mắt
                        </h5>
                        <div class="header__cart-item-price-wrap">
                          <span class="header__cart-item-price">2.000.000</span>
                          <span class="header__cart-item-multiply">x</span>
                          <span class="header__cart-item-qnt">1</span>
                        </div>
                      </div>
                      <div class="header__cart-item-body">
                        <span class="header__cart-item-decription"
                          >Phân loại bạc</span
                        >
                        <span class="header__cart-item-remove">xóa</span>
                      </div>
                    </div>
                  </li>
                </ul>
                <a class="header__cart-view-cart btn btn__primary"
                  >Xem giỏ hàng</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
import LoginForm from "@/views/login/loginForm.vue";
import registerForm from "@/views/register/registerForm.vue";
export default {
  name: "TheHeader",
  components: { LoginForm, registerForm },
  methods: {
    showLoginForm() {
      this.isLoginForm = true;
    },
    showRegisterForm() {
      this.isRegisterForm = true;
    },
  },
  data() {
    return {
      isLoginForm: false,
      isRegisterForm: false,
    };
  },
};
</script>

<style scoped></style>
