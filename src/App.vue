<template>
  <div class="container">
    <form class="card">
      <h2>IT-Labs o'quv markazi grandi uchun ro'yxatdan o'tish</h2>

      <div class="form-control">
        <label for="name">Ismingizni kiriting</label>
        <input type="text" id="name" placeholder="Ismingizni kiriting" />
      </div>

      <div class="form-control">
        <label for="age">Yoshingizni kiriting</label>
        <input type="number" id="age" value="14" min="14" />
      </div>

      <div class="form-control">
        <label for="city">Qaysi viloyatdansiz?</label>
        <select id="city">
          <option selected value="tosh">Toshkent</option>
          <option value="and">Andijon</option>
          <option value="far">Farg'ona</option>
          <option value="nam">Namangan</option>
          <option value="sam">Samarqand</option>
          <option value="sir">Sirdaryo</option>
          <option value="jiz">Jizzax</option>
          <option value="qas">Qashqadaryo</option>
          <option value="sur">Surxandaryo</option>
          <option value="nav">Navoiy</option>
          <option value="bux">Buxoro</option>
          <option value="xrm">Xorazm</option>
          <option value="qor">Qoraqalpog'iston</option>
        </select>
      </div>

      <div class="form-checkbox">
        <span class="label">Jinsingiz</span>
        <div class="checkbox">
          <label><input type="radio" name="gen" /> Erkak</label>
        </div>
        <div class="checkbox">
          <label><input type="radio" name="gen" /> Ayol</label>
        </div>
      </div>

      <div class="form-checkbox">
        <span class="label">Qaysi yo'nalishda o'qishni istaysiz?</span>
        <div class="checkbox">
          <label><input type="checkbox" /> Front-End </label>
        </div>
        <div class="checkbox">
          <label><input type="checkbox" /> Back-End </label>
        </div>
        <div class="checkbox">
          <label><input type="checkbox" /> Flutter </label>
        </div>
      </div>

      <div class="form-checkbox">
        <span class="label">Shartlar bilan tanishish</span>
        <label>
          <input type="checkbox" /> Barcha shartlarga
          roziman</label>
      </div>

      <button class="btn primary">Ro'yxatdan o'tish</button>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style></style>