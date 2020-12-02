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
              Mr. Coryat is a Web Developer with experience in building applications with JavaScript, Vue.js, Node.js, .Net and C#.  He recently graduated top of his class from Boise Codeworks – Immersive Full-Stack program.  His passion for solving problems and building user focused, solution applications motivated him to formally pursue this change in career.  
He is an experienced professional with a unique combination of technical expertise, managerial experience, business leadership, and design and production support.  
Mr. Coryat has a sincere interest in further expanding his talent to deliver quality software solutions by applying his recent training along with the prior six years of demonstrated strong analytical, leadership, engineering, business, and interpersonal skills
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
            <h5>Vue.Js Node.Js MongoDb Auth0</h5>
            <p>
              This is a mobile application that uses data from all an api that
              collects data from animal shelters all over the United States. You
              can search by your state and city to find animals that are near
              you. As well as favorite animals and contact the shelter for
              adoption.
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
            <h5>Vue.Js Node.Js MongoDb Auth0</h5>
            <p>
              This application lets you create boards that track lists and tasks
              as well as comments. You can move tasks from list to list as well
              as implement the full CRUD system.
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
    <section id="landing-contact" class="row d-flex justify-content-between">
      <article class="col-12 text-center text-light">
        <h4 class="m-4">Please Contact Me With Any Questions</h4>
      </article>
      <a href="mailto:tunnelvision77@gmail.com" class="text-center m-1">
        <i class="fa fa-envelope icon" aria-hidden="true"></i>
        <p class="text-light">Tunnelvision77@gmail.com</p>
      </a>
      <a href="https://www.linkedin.com/in/adam-coryat/" class="text-cener">
        <i class="fa fa-user-circle-o icon" aria-hidden="true"></i>
        <p class="text-light">LinkedIn</p>
      </a>
      <a
        href="https://github.com/AdamCoryat/AdamCoryat/blob/main/Assets/Coryat%20Adam%20Resume.pdf"
        class="text-center m-1"
      >
        <i class="fa fa-file-text icon" aria-hidden="true"></i>
        <p class="text-light">Resume</p>
      </a>
      <a href="tel:+1-208-880-3739" class="text-center m-1">
        <i class="fa fa-mobile icon" aria-hidden="true"></i>
        <p class="text-light m-1">208-880-3739</p>
      </a>
    </section>
  </main>
</template>

<script>
export default {
  name: "home",
  methods: {},
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
.icon {
  font-size: 4rem;
  color: rgb(0, 0, 0);
}
</style>
