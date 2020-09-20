<template>
  <div class="home">
    <div class="bio">
      <div class="innerBio">
        <img src="../assets/portrait.jpg"/>
        <div class="title">Natalie Farnsworth</div>
        Computer Science student of fine taste. Respecter of pandemics. Eater of delicious pies. Coder of cool things.
      </div>
    </div>
    <div class="resume">
      <div class="aboutMe">About Me</div>
      <div class="about">Studying Computer Science: Software Engineering at Brigham Young University</div>
      <div class="about">Junior expected to graduate April 2022</div>
      <div class="about">My hobbies (outside of coding) include cooking, singing,
      enjoying high quality media, and sleeping for profoundly long periods of time.
      I also speak Spanish as a second language and I'm currently learning Mandarin.
      My English is probably as good as it's ever gonna get.</div>
      <div class="about">I've created this website to showcase some projects I've worked on over the past couple of years
      in school, work, and for fun. You can download my resume <a href="Resume.pdf" download="FarnsworthResume">here</a>.</div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style scoped>

.home {
  display: flex;
  flex-direction: row;
  margin: 0% 10% 5% 10%;
}

.bio {
  margin-right: 5%;
  background: var(--plum);
  color: var(--purple-highlt);
  width: 35%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.innerBio {
  border: 1px var(--purple-highlt) solid;
  background: var(--plum);
  height: 88%;
  margin: 3%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 3%;
  font-size: 90%;
}

.innerBio img {
  width: 60%;
  border-radius: 150px;
  margin: 10%;
}

.title {
  font-family: 'Lexend Zetta', sans-serif;
  font-size: 100%;
  font-weight: bold;
  margin-bottom: 5%;
}

.resume {
  background: var(--lt-plum);
  align-items: flex-start;
  flex-direction: column;
  display: flex;
  text-align: left;
  padding-bottom: 5%;
  width: 70%;
}

.aboutMe {
  font-family: 'Lexend Zetta', sans-serif;
  font-size: 150%;
  font-weight: bold;
  padding: 5%;
  padding-bottom: 3%;
}

.about {
  font-size: 100%;
  padding-left: 5%;
  padding-right: 5%;
  padding-top: 3%;
}

a {
  color: white
}

/* Mobile Styles */
@media only screen and (max-width: 750px) {

  .home {
    display: flex;
    flex-direction: column;
    margin: 0% 10% 5% 10%;
  }

  .bio {
    width: 100%;
    margin-top: 10%;
    margin-right: 5%;
    margin-bottom: 10%;
    background: var(--plum);
    color: var(--purple-highlt);
    height: 50%;
  }

  .resume {
    background: var(--lt-plum);
    align-items: flex-start;
    flex-direction: column;
    display: flex;
    text-align: left;
    padding-bottom: 5%;
    width: 100%;
  }

}

</style>
