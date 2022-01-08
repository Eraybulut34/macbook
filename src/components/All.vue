<template>
  <div class="all">
    <h4 class="text1">Tüm</h4>
    <h2 class="text2">Macbook Air, Macbook Pro, Imac, Mac Pro ve Mac Mini</h2>
    <h1 class="text3">
      Apple marka bilgisayarlarınızı <br />
      adresinizden, <br />
      değerinde, nakit olarak satın alıyoruz.
    </h1>
    <h5 class="text4">
      Hizmetimiz 2020 model üzeri tüm ürünler için geçerlidir.
    </h5>
    <button class="contact">Bize Ulaşın</button>
<div class="text5">Whatsapp üzerinden ulaşabilirsiniz.></div>
  </div>
</template>

<script>
export default {
  name: "All",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.all {
  text-align: center;
  width: 700px;
  margin: auto;
  align-items: center;
  justify-content: center;
}
.text1 {
  margin-top: 100px;
  font-weight: 700;
  margin-bottom: 0.3em;
  background: rgba(0, 0, 0, 0);
  border-color: #bf4800;
  color: #f56300;
  line-height: 1.47059;
  letter-spacing: -0.022em;
  font-family: "SF Pro Text", "SF Pro Icons", "Helvetica Neue", "Helvetica",
    "Arial", sans-serif;
}
.text2 {
  font-size: 28px;
  line-height: 1.14286;
  font-weight: 600;
  letter-spacing: 0.007em;
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica",
    "Arial", sans-serif;
  color: #1d1d1f;
  margin-top: 10px;
}
.text3 {
  font-size: 56px;
  line-height: 1.07143;
  font-weight: 600;
  letter-spacing: -0.005em;
  font-family: "SF Pro Display", "SF Pro Icons", "Helvetica Neue", "Helvetica",
    "Arial", sans-serif;
  color: #1d1d1f;
    margin-top: 10px;
}
.text4 {
    font-size: 17px;
    line-height: 1.47059;
    font-weight: 400;
    letter-spacing: -.022em;
    font-family: "SF Pro Text","SF Pro Icons","Helvetica Neue","Helvetica","Arial",sans-serif;
  color: #1d1d1f;
      font-style: normal;
        margin-top: 10px;
}
.contact{
      cursor: pointer;
    display: inline-block;
    text-align: center;
    white-space: nowrap;
    font-size: 17px;
    line-height: 1.17648;
    font-weight: 400;
    letter-spacing: -.022em;
    font-family: "SF Pro Text","SF Pro Icons","Helvetica Neue","Helvetica","Arial",sans-serif;
    min-width: 28px;
width: 130px;
    padding-top: 8px;
    padding-bottom: 8px;
    border-radius: 980px;
    background: #0071e3;
    color: #fff;
    border-style: none;
      margin-top: 10px;
}
.text5{
    margin-top: 10px;
  color: #06c;
    letter-spacing: inherit;
        font-family: "SF Pro Text","SF Pro Icons","Helvetica Neue","Helvetica","Arial",sans-serif;
}
</style>
