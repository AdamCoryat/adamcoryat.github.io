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
          <a href="#landing-about"><h2 class="text-light">About Me</h2></a>
        </div>
      </article>
      <section
        id="landing-about"
        class="about-bg col-12 d-flex flex-wrap justify-content-center align-items-center text-light"
      >
        <article id="about-card" class="card">
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
        </article>
      </section>
    </section>
    <section id="landing-skills" class="row flex-wrap align-items-center">
      <articl class="col-12 text-center text-light">
        <h1>Languages and Tools</h1>
      </articl>
      <article class="col-2 fill"></article>
      <article class="col-8 text-center">
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
      </article>
      <article class="col-2 fill"></article>
    </section>
    <section id="landing-applications" class="row">
      <article id="application-title" class="col-12 text-center text-light p-4">
        <h1>Applications</h1>
      </article>
      <article class="col-12 d-flex justify-content-center">
        <a
          class="application card contents m-2"
          href="https://petpal7.herokuapp.com/#/"
        >
          <img class="card-img-top" src="../assets/Petpal.png" alt="" />
          <div class="overlay text-center text-light p-1">
            <h3>PetPal</h3>
            <p>
              Full Stack Mobile Application. Utilizing Vue.js client as well as
              a Node.js Server with Auth0. I created this app by utilizing an
              api that collects data from mutilple animal shelters. This is
              meant to make a one stop shop for adopting an animal by your
              location and being able to save and contact the shelter for more
              information.
            </p>
          </div>
        </a>
        <a
          class="application contents card m-2"
          href="https://kanban77.herokuapp.com/"
        >
          <img class="card-img-top" src="../assets/Kanban.png" alt="" />
          <div class="overlay text-center text-light p-1">
            <h3>KanBan</h3>
            <p>
              Full Stack Application. Utilzing Vue.js clientside as well as a
              Node.Js Server with Auth0. This application lets you create boards
              that track lists and tasks as well as comments. You can move tasks
              from list to list as well as implement the full CRUD system.
            </p>
          </div>
        </a>
        <a
          class="application contents card m-2"
          href="https://bug-spray.herokuapp.com/"
        >
          <img class="card-img-top" src="../assets/Bugspray.png" alt="" />
          <div class="overlay text-center text-light p-1">
            <h3>Bug-Log</h3>
            <h5>Vue.Js, Node.Js, MongoDb, Auth0</h5>
            <p>
              This application lets you post bugs as well as comment and close
              them after you have found the solution. A bug is never deleted but
              closed and still able to refrence later down the line.
            </p>
          </div>
        </a>
      </article>
      <article class="col-12 d-flex justify-content-center">
        <a
          class="application contents card m-2"
          href="https://adamcoryat.github.io/Inspire-checkpoint--4/"
        >
          <img class="card-img-top" src="../assets/Inspire.png" alt="" />
          <div class="overlay text-center text-light p-1">
            <h3>Inspire</h3>
            <h5>JavaScript, BootStrap, MVCS</h5>
            <p>
              This application is built to provide you with a homepage that
              utilizes several apis. The background, Quote, Weather all are from
              various api's. You can change the clock from 12/24hr as well as
              add to the to-do list.
            </p>
          </div>
        </a>
        <div class="application in-progress contents card m-2">
          <div class="overlay text-center text-light p-1">
            <h1 class="text-danger">Coming Soon</h1>
            <h3>Keeper</h3>
            <h5>Vue.Js, .Net, MySql, Auth0</h5>
            <p>
              This application is a mock of pintrest. You can view all the
              post's and user profiles as well as Vaults. If you login you can
              create vaults and add other users posts to your vaults.
            </p>
          </div>
        </div>
        <a
          class="application contents card m-2"
          href="https://adamcoryat.github.io/click-game/"
        >
          <img class="card-img-top" src="../assets/Global-Gold.png" />
          <div class="overlay text-center text-light p-1">
            <h3>ClickGame</h3>
            <h5>JavaScript, Html, CSS</h5>
            <p>
              This application is a simple but fun clicker game where you mine a
              planet and purchase upgrades and get all that Gold!
            </p>
          </div>
        </a>
      </article>
    </section>
    <section id="landing-github" class="row flex-wrap align-items-center">
      <article class="col-12 text-center">
        <h1 class="p-2 text-light">Find More of My work Here</h1>
        <a
          href="https://github.com/AdamCoryat"
          type="button"
          class="m-2 btn btn-success"
        >
          My GitHub
        </a>
      </article>
    </section>
    <section id="landing-contact" class="row">
      <article class="col-12"></article>
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
  min-height: 70vh;
  background: black;
}
.logo {
  height: 14vh;
}
.fill {
  min-width: 3vw;
}
.card {
  width: 25vw;
  border: 1px solid black;
}

.application {
  transition: 0.5s ease;
}
.application:hover {
  transform: scale(1.05);
}
.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;

  opacity: 0;
  transition: 0.5s ease;
  background-color: #040607b9;
}

.contents:hover .overlay {
  opacity: 1;
}
.in-progress {
  background-image: url("../assets/keepr.jpeg");
  background-position: center;
  background-size: cover;
}
#landing-github {
  min-height: 40vh;
  background-color: black;
}
#landing-contact {
  min-height: 30vh;
  background-color: rgb(65, 65, 65);
}
</style>
