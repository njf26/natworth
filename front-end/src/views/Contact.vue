<template>
  <div class="contact">
    <h1>Contact Me</h1>
    <div class="row">
      <img width="15%" src="../assets/contact.jpg"/>
      <div class="contactInfo">
        <p>Phone: 636-295-3947</p>
        <p>Email: farnsworth.natalie@gmail.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/natalie-farnsworth">https://www.linkedin.com/in/natalie-farnsworth</a></p>
        <p>GitHub: <a href="https://github.com/njf26">https://github.com/njf26</a></p>
      </div>
    </div>
  </div>
</template>

<style scoped>

.row {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}

.contactInfo {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  text-align: left;
  color: var(--white);
  font-size: 110%;
  margin: 3%;
}

p {
  margin: 1%;
}

a {
  color: var(--purple-highlt);
}

/* Mobile Styles */
@media only screen and (max-width: 750px) {

  .row {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  .row img {
    width: 50%;
    margin-bottom: 3%;
  }

  .contactInfo {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    color: var(--white);
    font-size: 110%;
    margin: 3%;
  }

}

</style>
