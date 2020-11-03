<template>
  <main class="home container-fluid">
    <section id="landing-body" class="row">
      <article
        id="landing-hero"
        class="col-12 d-flex justify-content-center align-items-center header-bg"
      >
        <div class="text-center">
          <h1 class="text-light">
            Full-Stack Software Developer
          </h1>
          <button type="button" class="btn-primary btn">Learn More</button>
        </div>
      </article>
      <article
        id="landing-about"
        class="about-bg col-12 d-flex flex-wrap justify-content-center align-items-center text-light"
      >
        <div id="about-card" class="card">
          <div class="card-body">
            <h4 class="card-title text-center">About Me</h4>
            <hr class="line-break" />
            <p class="card-text">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dicta
              dignissimos velit omnis doloremque repellendus corporis, dolore
              eum officia temporibus in at voluptates ad corrupti eius
              reprehenderit! Placeat accusantium ad Lorem ipsum dolor sit amet,
              consectetur adipisicing elit. Accusantium maiores ipsum tempore
              eos necessitatibus? Itaque, qui voluptatum et quasi reprehenderit
              quam repudiandae, quod debitis unde asperiores iure quas omnis
              nobis. Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Ipsa, aut! Molestiae labore, distinctio odit dignissimos optio est
              unde eligendi, magni voluptates voluptate tenetur voluptas nobis
              nemo temporibus ratione deserunt consectetur. Lorem ipsum dolor
              sit amet consectetur adipisicing elit. Nihil eum consequatur nulla
              commodi sequi. Debitis dolores odit pariatur aspernatur nostrum
              minima eos cumque laboriosam dolore. Debitis aut omnis nostrum
              autem!
            </p>
          </div>
        </div>
      </article>
      <article id="landing-skills" class="">
        <div class="col-2 fill"></div>
        <div class="col-8">
          <img class="logo m-1" src="../assets/CSS.png" />
          <img class="logo m-1" src="../assets/HTML.png" />
          <img class="logo m-1" src="../assets/Bootstrap.png" />
          <img class="logo m-1" src="../assets/SASS.png" />
          <img class="logo m-1" src="../assets/VueLogo.png" />
          <img class="logo m-1" src="../assets/JS.png" />
          <img class="logo m-1" src="../assets/Csharp.png" />
          <img class="logo m-1" src="../assets/NET.png" />
          <img class="logo m-1" src="../assets/Mysql.png" />
          <img class="logo m-1" src="../assets/Mongo.png" />
          <img class="logo m-1" src="../assets/GIT.png" />
        </div>
        <div class="col-2 fill"></div>
      </article>
    </section>
  </main>
</template>

<script>
export default {
  name: "home",
};
</script>
<style scoped>
.header-bg {
  background-image: url("../assets/headerhero.jpeg");
  min-height: 95vh;
  background-position: center;
  background-size: cover;
}
.about-bg {
  background-color: #000000;
  min-height: 70vh;
}

#about-card {
  border-radius: 50px;
  background: #c03b67;
  width: 60vw;
}
.line-break {
  color: white;
}
#landing-skills {
  min-height: 50vh;
  background: black;
}
.logo {
  height: 12vh;
}
.fill {
  min-width: 15vw;
}
</style>
