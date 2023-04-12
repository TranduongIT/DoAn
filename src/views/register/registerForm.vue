<template>
  <div class="main">
    <form action="" method="POST" class="form" id="register-form">
      <h3 class="heading">Đăng ký</h3>
      <p class="desc">Bạn muốn đăng ký tài khoản của shop NGOCDUONG</p>

      <div class="spacer"></div>

      <div class="form-group">
        <label for="fullname" class="form-label">Tên đầy đủ</label>
        <input
          id="fullname"
          rules="required"
          name="fullname"
          type="text"
          placeholder="VD: Trần Dương"
          class="form-control"
        />
        <span class="form-message"></span>
        <span></span>
      </div>

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

      <button class="form-submit">Đăng ký</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "registerForm",
};
</script>

<style scoped></style>
