<template>
  <main class="main__section">
    <b-container>
      <b-row
        v-for="(items, index) in data"
        :key="index"
        class="align-items-center mb-5"
      >
        <b-col lg="6" class="order-2 order-lg-1">
          <section class="desc_application mt-4 mt-lg-0">
            <h1>
              Balikpapan Enak
            </h1>
            <h4>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Alias
              eaque sed culpa rerum fuga facere vel, praesentium ducimus dolorem
              similique, porro voluptate ab.
            </h4>
            <button class="btn_launch py-3 mt-4 mt-lg-4 px-5">
              Launch Website
            </button>
          </section>
        </b-col>
        <b-col lg="6" class="order-1 order-lg-2">
          <section>
            <img
              class="imageHeaderApplication1"
              src="../../../assets/Images/MainThema/exampleImage.svg"
              alt="imageHeaderApplication1"
            />
          </section>
        </b-col>
      </b-row>
    </b-container>
    <section class="waves">
      <img
        src="../../../assets/Images/SecondaryThema/DownWave.svg"
        alt="waves"
      />
    </section>
  </main>
</template>
<script>
export default {
  name: 'MainSection',
  data() {
    return {
      data: 1
    }
  }
}
</script>
<style scoped>
.main__section {
  padding-top: 130px;
}
.imageHeaderApplication1 {
  width: 100%;
}
.desc_application {
  font-family: 'Poppins', sans-serif;
}
.desc_application h4 {
  font-size: 20px;
}
.desc_application h1 {
  font-family: 'Arvo', serif;
  font-size: 35px;
}
.btn_launch {
  border-radius: 11px;
  border: none;
  font-size: 19px;
  font-weight: 700;
  background: #a6e3e9;
  color: #ffffff;
  outline: none;
  box-shadow: 5px 6px 5px #cbf1f5;
}
.btn_launch:hover {
  background: #71c9ce;
  transition: 0.5s;
}
</style>
