<template>
  <div class="home container-fluid">
    <div class="row navbar">
      <div class="col-12">
        <nav class="navbar navbar-light bg-light fixed-top">
          <span class="navbar-brand mb-0 h1 text-left">Ben Kirby</span>
          <a class="navbar-brand text-right" href="#bio">About Me</a>
          <a class="navbar-brand text-right" href="#projects">Projects</a>
          <a class="navbar-brand text-right" href="#contact">Contact</a>
        </nav>
      </div>
    </div>
    <div class="row pt-5">
      <div id="top" class="bg-info text-white col-12 top">
        <h1 class="name">Ben Kirby</h1>
        <h3 class="title">Full Stack Web Developer</h3>
        <!-- <a href="#bio">Go To Contact</a> -->
      </div>
      <div id="languages" class="col-12 p-5 bg-warning">
        <h5>List of Languages / Frameworks</h5>
      </div>
      <div id="projects" class="col-12 p-5 bg-danger">
        <h5>Projects w/Links / Github</h5>
      </div>
      <div id="bio" class="col-12 bg-success p-5">
        <h5>Bio</h5>
      </div>
      <div id="contact" class="col-12 bg-primary p-5">
        <h5>Contact Info / Social Links</h5>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
<style>
.top {
  background-image: url("~@/assets/Gray-Background.png");
  background-position: center;
  min-height: 100vh;
}
.name {
  font-size: 70pt;
  text-shadow: 2px 2px black;
}
.title {
  font-size: 35pt;
  text-shadow: 2px 2px black;
}
#languages {
  min-height: 65vh;
}
#bio {
  min-height: 65vh;
}
#projects {
  min-height: 65vh;
}
#contact {
  min-height: 65vh;
}
</style>
