<template>
  <div class="main">
    <form action="" method="POST" class="form" id="register-form">
      <h3 class="heading">Đăng nhập</h3>
      <div class="icon-close sprite"></div>

      <div class="spacer"></div>

      <div class="form-group">
        <label for="email" class="form-label">Email</label>
        <input
          id="email"
          rules="required|email"
          name="email"
          type="text"
          placeholder="VD: email@domain.com"
          class="form-control"
        />
        <span class="form-message"></span>
      </div>

      <div class="form-group">
        <label for="password" class="form-label">Mật khẩu</label>
        <input
          id="password"
          rules="required|min:6"
          name="password"
          type="password"
          placeholder="Nhập mật khẩu"
          class="form-control"
        />
        <span class="form-message"></span>
      </div>

      <button class="form-submit">Đăng nhập</button>

      <a href="" class="forgot_password">Quên mật khẩu?</a>

      <span class="wrapper">
        <a href="" class="form_register">Tạo tài khoản mới</a>
      </span>
    </form>
  </div>
</template>

<script>
export default {
  name: "loginForm",
  props:[]
};
</script>

<style scoped>
</style>
