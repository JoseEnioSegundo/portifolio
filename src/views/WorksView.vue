<template>
  <main>
     <section class="works">
      <h2>Featured works</h2>
      <ul>
        <li>
          <p><img src="/image1.png" alt="Imagem de um dashboard" /></p>
          <h3>Designing Dashboards</h3>
          <p class="info"><span>2020</span> Dashboards</p>
          <p>
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit
            officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud
            amet.
          </p>
        </li>
        <li>
          <p><img src="/image2.png" alt="Vibrant Portraits" /></p>
          <h3>Vibrant Portraits of 2020</h3>
          <p class="info"><span>2018</span> Illustration</p>
          <p>
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet sint. Velit
            officia consequat duis enim velit mollit. Exercitation veniam consequat sunt nostrud
            amet.
          </p>
        </li>
      </ul>
    </section>
    </main>
</template>
<style scoped>
/* ============================================================================================
ESPECÍFICO
============================================================================================ */

section.banner {
  text-align: center;
  padding: 0 5%;
}

section.banner h1 {
  font-weight: bold;
  font-size: 2rem;
  margin: 10px 0;
}

section.banner p button {
  background: #ff6464;
  border: none;
  color: #ffffff;
  display: inline-block;
  margin: 10px 0 50px;
  padding: 5px 10px;
  font-size: 1.5rem;
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
  margin: 0 0 15px;
}

section.posts ul li p {
  font-size: 1rem;
  margin: 15px 0;
}

/* ============================================================================================
PÁGINA FT-WORKS
============================================================================================ */

section.dashb {
  padding: 20px 10px;
}

section.dashb h2 {
  font-size: 2rem;
  text-align: left;
  margin: 20px 0 40px;
}

section.dashb ul li {
  margin: 20px 0;
}

section.dashb ul li h3 {
  font-weight: bold;
  font-size: 1.4rem;
  line-height: 130%;
  margin: 0 0 15px 0;
}

section.dashb ul li p {
  margin: 15px 0;
  color: black;
}

section.dashb ul li p.info {
  color: #21243d;
}

section.dashb ul li p.info span {
  background: #ff7c7c;
  color: white;
  border-radius: 16px;
  padding: 5px 10px;
  font-weight: bold;
}

/* ============================================================================================
TELA PC
============================================================================================ */

@media (min-width: 900px) {
  section h2 {
    text-align: left;
    font-size: 1.5rem;
    margin: 10px;
  }

  section.banner {
    display: flex;
    flex-direction: row-reverse;
    text-align: left;
    padding: 5vw 10vw;
  }

  section.banner .texto {
    margin-right: 7vw;
  }

  section.posts,
  section.works {
    padding: 5vw 10vw;
  }

  section.posts ul,
  section.works ul {
    display: flex;
    justify-content: space-between;
  }

  section.posts ul li {
    padding: 2%;
  }

  section.posts ul li,
  section.works ul li {
    width: 45%;
  }

  section.posts ul li p.data {
    margin: 20px 0;
  }

  section.works ul {
    border-bottom: none;
  }
}
</style>
