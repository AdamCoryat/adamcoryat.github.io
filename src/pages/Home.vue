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
            <hr class="text-light" />
            <p class="card-text">
              Hi thanks for having me here today, It’s been a crazy year right?
              A lot has changed in my life as well as I’m sure it has with
              yours. One of the biggest changes in my life has been my growing
              passion as full stack software developer with emphasis on C# and
              JavaScript as well as the front end wire frame Vue2. As for the
              server side I code applications in .Net, Node, MongoDb and My Sql.
              I think I would make a great addition to your team because of my
              knowledge and skills that I have obtained through my work career.
              For example I helped create and run a successful Fiber Optic
              Company where I managed customer relations as well as accounting
              on top of the day to day work. In our first year we were able to
              gross six figures even though we started half way through the
              fiscal year. The next year we almost tripled that number. Through
              my interactions with our customer Century-Link I was able to
              double our work load to the point where the company needed to
              expand and hire more individuals to keep up with the work flow.
              One of my biggest goals is to expand my knowledge in application
              development as well as bec
            </p>
          </div>
        </div>
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
  background-color: #3c6c80;
  min-height: 70vh;
}

#about-card {
  border-radius: 50px;
  background: #3c6c80;
  box-shadow: 20px 20px 60px #335c6d, -20px -20px 60px #457c93;
  width: 60vw;
}
</style>
