<template>
  <div class="home">
    <div class="bio">
      <div class="innerBio">
        <img src="../assets/portrait.jpg"/>
        <div class="title">Natalie Farnsworth</div>
        Computer Science student of fine taste. Respector of pandemics. Good at everything she does.
      </div>
    </div>
    <div class="resume">
      My resume...

      I v good hire me.
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
  width: 30%;
  margin-right: 5%;
  background: var(--plum);
  color: var(--purple-highlt);
  height: 50%;
}

.innerBio {
  border: 1px var(--purple-highlt) solid;
  background: var(--plum);
  width: 88%;
  margin: 3%;
  height: 88%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 3%;
}

.innerBio img {
  width: 60%;
  border-radius: 100px;
  margin: 10%;
}

.title {
  font-family: 'Lexend Zetta', sans-serif;
  font-size: 110%;
  font-weight: bold;
  margin-bottom: 5%;
}

.resume {
  width: 65%;
  background: var(--lt-plum);
}

</style>
