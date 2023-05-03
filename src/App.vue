<template>
  <div>
    <header class="p-3">
      <a href="#" class="site-icon"
        ><span class="text-primary">G</span><span class="text-danger">o</span
        ><span class="text-warning">o</span><span class="text-primary">g</span
        ><span class="text-success">l</span><span class="text-danger">e</span>
        <span class="text-secondary"> Переводчик</span></a
      >
      <a href="https://translate.google.co.uz/"
        ><button class="bg-primary btn text-white">Перевести</button></a
      >
    </header>
    <h1 class="text1">
      Вы сможете понимать других и выражать свои мысли на разных языках
    </h1>
    <div class="wrapper">
      <a
        href="https://play.google.com/store/apps/details?id=com.google.android.apps.translate"
        ><img src="./components/google-play-badge.webp" alt="img"
      /></a>
      <a href="https://apps.apple.com/us/app/apple-store/id414706506"
        ><img src="./components/app-store-badge.webp" alt="img" class="icon2"
      /></a>
    </div>
    <img src="./components/banner.webp" alt="img" class="banner-img" />
  </div>
</template>
<script>
export default {};
</script>
<style>
a {
  text-decoration: none;
}
button {
  border: none;
}
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.site-icon {
  font-size: 1.303rem;
}
.btn {
  border-radius: 6px;
  padding: 10px 20px 10px 20px;
}
.text1 {
  font-size: 55px;
  font-weight: 400;
  width: 800px;
  text-align: center;
  margin: 50px auto;
}
.wrapper img {
  width: 150px;
  height: 50px;
}
.wrapper {
  display: flex;
  justify-content: center;
}
.icon2 {
  margin-left: 15px;
}
.banner-img {
  width: 700px;
  height: 470px;
  display: flex;
  align-items: center;
  margin: 20px auto;
}
</style>
