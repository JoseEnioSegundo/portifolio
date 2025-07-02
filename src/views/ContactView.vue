<script setup>

</script>

<template>
  <main>
    <section class="banner">
      <div class="imagem">

      </div>
      <div class="texto">
        <h1>Contact</h1>
        <p>
          Não entre em contato.
        </p>
        <section class="fofo"><img src="/dormin.jpg" alt="Imagem de um dashboard" /></section>

        <p>
          <button class="whatsapp">
            <span class="fa-brands fa-whatsapp"></span> 47 99669-7913
          </button>
        </p>
      </div>
    </section>
  </main>
</template>

<style scoped>
section.banner {
  text-align: center;
  padding: 0 5%;
}

section.banner h1 {
  font-weight: bold;
  font-size: 2rem;
  margin: 10px 0;
}

button.whatsapp {
  background: #25d366;
  border: none;
  color: #ffffff;
  display: inline-block;
  margin: 10px 0 50px;
  padding: 10px 15px;
  font-size: 1.2rem;
  border-radius: 5px;
  cursor: pointer;
}

button.whatsapp:hover {
  background: #1ebe57;
}

section.posts {
  background: #edf7fa;
  padding: 10px;
}

section.posts ul li {
  background: white;
  padding: 15px;
  margin: 12px 0;
}

section.posts ul li h3 {
  font-weight: bold;
  font-size: 1.3rem;
  margin-bottom: 15px;
}

section.posts ul li p {
  font-size: 1rem;
  margin: 15px 0;
}

section.works {
  padding: 20px 10px;
}

section.works ul li {
  margin: 10px 0;
}

section.works ul li h3 {
  font-weight: bold;
  font-size: 1.4rem;
  line-height: 130%;
}

section.works ul li p.info {
  color: #8695a4;
}

section.works ul li p {
  margin: 10px 0;
}

section.works ul li p.info span {
  color: white;
  background: #142850;
  font-weight: bold;
  padding: 5px 10px;
  border-radius: 16px;
}

section.works ul {
  border-bottom: 1px solid #e0e0e0;
}
section.fofo {
  margin: 20px 0;
}
section.fofo img {
  width: 200px;
  border-radius: 50%;
}
</style>


