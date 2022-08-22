<template>
  <div>
    <h1 class="content-title">
      <font-awesome-icon icon="user-circle" class="icon" /> About
    </h1>
    <div>
      <div class="about">
        <div class="me">
          <h2><font-awesome-icon icon="pen" class="icon" /> Name</h2>
          <p class="text">Athiprat Kanha</p>
        </div>

        <div class="me">
          <h2><font-awesome-icon icon="school" class="icon" /> Education</h2>
          <p class="text">
            Junior Software Developer <br />
            @Generation Thailand
          </p>
        </div>

        <div class="me">
          <h2>
            <font-awesome-icon icon="birthday-cake" class="icon" /> Birthday
          </h2>
          <p class="text">07-09-1994</p>
        </div>
      </div>

      <h2><font-awesome-icon icon="search" class="icon resent" /> About Me</h2>
      <p class="text">
        I have decided to lead my career path into the tech industry <br />
        I learn all the time, nowadays I learn programming seriously every day
      </p>
    </div>
  </div>
</template>

<style scoped>
.about {
  display: inline-flex;
  padding-left: 5%;
  padding-right: 5%;
}

.resent {
  margin-top: 50px;
}

.me {
  margin: 0 50px;
}

.text {
  font-weight: 300;
}

@media screen and (max-width: 768px) {
  .about {
    flex-direction: column;
  }

  .me {
    margin: 0 auto;
  }
}
</style>
