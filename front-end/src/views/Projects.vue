<template>
  <div class="projects">
    <h1>Personal</h1>
    <div class="subheader"><p>This summer I took an online Flutter Mobile Programming course.
    The following is a selection of apps I made with the course and apps from the course that
    I personalized.</p></div>

    <div class="row">
      <div class="column"><img src="../assets/bmi.gif"/>
        <a href="https://github.com/njf26/bmi-calculator-flutter">GitHub</a> for BMI Calculator
      </div>
      <div class="column"><img src="../assets/bitcoin.gif"/>
        <a href="https://github.com/njf26/bitcoin-ticker-flutter">GitHub</a> for Bitcoin Ticker
      </div>
      <div class="column"><img src="../assets/clima.gif"/>
        <a href="https://github.com/njf26/clima-flutter">GitHub</a> for Clima Weather
      </div>
    </div>

    <div class="row">
      <div class="column"><img src="../assets/quizzler.gif"/>
        <a href="https://github.com/njf26/quizzler-flutter">GitHub</a> for Quizzler
      </div>
      <div class="column">
        <video controls>
          <source src="../assets/xylophone.mp4" type="video/mp4">
        </video>
        <a href="https://github.com/njf26/xylophone-flutter">GitHub</a> for Xylophone
      </div>
      <div class="column"><img src="../assets/todoey.gif"/>
        <a href="https://github.com/njf26/todoey-flutter">GitHub</a> for Todoey
      </div>
    </div>

    <div class="row">
      <div class="column"><img src="../assets/knights.gif"/>
        <a href="https://github.com/njf26/knights.git">GitHub</a> for Knights
      </div>
      <div class="subheader">
        <p>After completing the course I made an original Flutter app called
        Knights. It features a small game to solve.</p>
        <p>The purpose of the game is to traverse the 8x8 board like a Knight in
        Chess and mark every spot on the board one time. The app times your
        solving speed.</p>
        <p>I'm currently implementing a
        Google Firebase database to allow users to make accounts that store their
        top scores.</p>
      </div>
    </div>

<!--
    <div class="row">
      <div class="subheader"><p>
        I've also recently learned how to make a browser extension using the Vue framework.
        Here is a Tab-organizing extension I made to save tab sessions and
        restore desired sessions whenever you'd like.
      </p></div>
      <div class="column"><img src="../assets/extension.gif"/>
        <a href="https://github.com/njf26/todoey-flutter">GitHub</a> for Tab Organizer
      </div>
    </div>
  -->

    <h1>Work</h1>

    <div class="subheader"><p>In April 2020 I started working as an undergraduate
    Research Assistant at the Usable Security and Privacy Lab at
    Brigham Young University.</p></div>

    <div class="subheader"><p>My team is currently developing an authentication
    system that eliminates the need for passwords.</p></div>

    <div class="row" style="flex-direction: column">
      <div class="column"><img src="../assets/extension.gif"/></div>
      <div class="subheader" style="width: 60%">
        <p>
          My main contribution is the (ongoing) development of the 1Key browser extension
          that allows a user to login to websites automatically. The browser extension implements various cryptographic functions and
          interacts with a Client Authority built by the team.
        </p><p>
          There are also various pages that show user info such as the list of
          authenticating devices they have registered under their account, the list
          of websites that they are registered with using 1Key, and the list of
          those websites that they are currently logged-in to.
        </p>
      </div>
    </div>

    <div class="row">
      <div class="subheader"><p>
        I learned Flutter to help with app development for the system.
        This is a Spotify clone app that I made to interact with the team's mobile
        app version of 1Key. The only functionality of the Spotify app is
        logging in and out.
      </p></div>
      <div class="column"><img src="../assets/spotify.gif"/>  </div>
    </div>

    <h1>School</h1>

    <div class="row">
      <div class="column"><img src="../assets/familymap.gif"/>  </div>
      <div class="list">
        <p>My most notable school projects include:</p>
        <ul>
          <li>Relational Database, built in C++ (Discrete Mathematics)</li>
          <li>Collection of websites on this domain (Web Programming)
            <ul>
              <li><a href="https://lab5.natworth.com/">Photo Sharing Website</a></li>
              <li><a href="https://creative4.natworth.com/">Controversial Question Voting</a></li>
              <li><a href="https://lab3.natworth.com/">Comic Website</a></li>
              <li><a href="https://lab1.natworth.com/">Photographer Website</a></li>
              <li><a href="https://creative1.natworth.com/">Procrasis Quesoaris</a></li>
              <li><a href="https://creative2.natworth.com/">Lyric Fetcher</a></li>
              <li><a href="https://creative3.natworth.com/">Restaurant Finder</a></li>
            </ul>
          </li>
          <li>Family History App and Server. This was
          built using java and is only available on Android.
          You can see an example of it's functionality here. (Adv Programming Concepts)</li>
          <li>Implementation of Data Structures such as linked lists, maps, binary search tree, and AVL tree. All built in C++ (Data Structures)</li>
        </ul>
        <p>
          To prevent plagiarism issues, I have put most of these projects in private GitHub repositories.
          Contact me if you would like Github permission to access these code bases.
        </p>
      </div>
    </div>


  </div>
</template>

<style scoped>

.projects {
  display: flex;
  flex-direction: column;
  align-items: center;
}

h1 {
  color: var(--white);
}

.subheader {
  width: 40%;
  margin-left: 5%;
  margin-right: 5%;
}

.column {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: var(--white);
}

.column img {
  width: 80%;
  margin: 4%;
}

.column video {
  width: 80%;
  margin: 4%;
}

.row {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  margin-bottom: 8%;
}

a {
  color: var(--purple-highlt);
}

.list {
  text-align: left;
  width: 50%;
  margin-right: 3%;
}

/* Mobile Styles */
@media only screen and (max-width: 750px) {

  .row {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-bottom: 8%;
  }

  .subheader {
    width: 80%;
  }

  .list {
    text-align: left;
    width: 85%;
  }

}

</style>
